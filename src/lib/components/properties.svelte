<script>
    let properties = [
      { 
        title: "Apartment ni Denzel", 
        location: "Downtown", 
        price: "₱10,000/mo", 
        image: "/assets/apartment1.jpg",
        description: "A luxurious apartment with stunning city views and modern amenities."
      },
      { 
        title: "Labubu studio", 
        location: "Uptown", 
        price: "₱12,000/mo", 
        image: "/assets/sample1.jpg",
        description: "A cozy studio perfect for single living or couples."
      },
      { 
        title: "Massive Loft", 
        location: "Midtown", 
        price: "₱18,000/mo", 
        image: "/assets/sample1.jpg",
        description: "A spacious loft with high ceilings and an open floor plan."
      },
    ];
  </script>
  
  <section class="properties">
    <h2>Featured Properties</h2>
    <div class="property-list">
      {#each properties as property}
        <div class="property-card">
          <img src="{property.image}" alt="{property.title}" class="property-image" />
          <h3>{property.title}</h3>
          <p>{property.location}</p>
          <p>{property.price}</p>
          <p class="description">{property.description}</p>
        </div>
      {/each}
    </div>
  </section>
  
  <style>
    .properties {
      padding: 50px 20px;
      text-align: center;
    }
    .property-list {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .property-card {
      border: 1px solid #ddd;
      padding: 20px;
      margin: 10px;
      width: 320px; /* Adjusted width to accommodate image */
      border-radius: 5px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Optional shadow for depth */
      transition: transform 0.3s; /* Smooth transition */
    }
    .property-card:hover {
      transform: translateY(-5px); /* Slight lift on hover */
    }
    .property-image {
      width: 100%; /* Make the image responsive */
      height: 150px; /* Fixed height for uniformity */
      object-fit: cover; /* Cover the card without stretching */
      border-radius: 5px 5px 0 0; /* Rounded top corners */
    }
    .description {
      margin-top: 10px; /* Space above the description */
      color: #666; /* Subtle color for description */
    }
  </style>
  