---
collection: personal life
permalink: /life/
---

When I’m not working, you’ll find me exploring nature through hiking and adventure, capturing moments with my camera, or diving into a good book. These things keep me inspired and balanced, blending creativity, curiosity, and a love for discovery.

<h1>My Hiking Clips</h1>
<div class="image-grid">
  <!-- Image 1 -->
  <div class="image-item">
    <img src="../images/Narayanthanmy.jpg" alt="Narayanthan">
    <p class="caption">Hike is a scenic trekking route in Nepal, offering stunning views of lush green hills and the Kathmandu Valley. It is a moderate trail, ideal for beginners and nature enthusiasts, with opportunities to explore serene landscapes and local villages. The hike typically leads to Narayanthan Temple, a peaceful spot rich in cultural and spiritual significance.</p>
  </div>
  <!-- Image 2 -->
  <div class="image-item">
    <img src="../images/N1.jpg" alt="Hiking">
    <p class="caption">Serenity in Nature</p>
  </div>
  <!-- Image 3 -->
  <div class="image-item">
    <img src="../images/n2.jpg" alt="Adventure">
    <p class="caption">Exploring Hidden Trails</p>
  </div>
  <!-- Image 4 -->
  <div class="image-item">
    <img src="../images/Sikles1.jpg" alt="Sikles">
    <p class="caption">The Sikles Experience</p>
  </div>
</div>

<style>
  .image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); /* Responsive columns */
    gap: 15px; /* Spacing between images */
    padding: 10px;
  }

  .image-item {
    text-align: center;
    display: flex;
    flex-direction: column; /* Stack image and caption */
    align-items: center;
    justify-content: center;
  }

  .image-item img {
    width: 100%; /* Ensure images fill their container */
    height: auto;
    border-radius: 10px; /* Rounded corners for a modern look */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Add some shadow for depth */
    transition: transform 0.3s ease, box-shadow 0.3s ease; /* Hover animation */
  }

  .image-item img:hover {
    transform: scale(1.05); /* Slight zoom on hover */
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3); /* Enhanced shadow on hover */
  }

  .caption {
    margin-top: 8px; /* Space between the image and caption */
    font-size: 0.9rem; /* Adjust font size for captions */
    color: #555; /* Caption color */
    text-align: center; /* Center the caption */
    word-wrap: break-word; /* Ensure long text wraps correctly */
    overflow-wrap: break-word; /* For long words that can't fit */
    max-width: 100%; /* Ensure it doesn't overflow */
  }
</style>
