---
collection: personal life
permalink: /life/
---

When I’m not working, you’ll find me exploring nature through hiking and adventure, capturing moments with my camera, or diving into a good book. These things keep me inspired and balanced, blending creativity, curiosity, and a love for discovery.

<h1>My Projects</h1>
<div class="projects-section">
  <!-- Project 1 -->
  <div class="project-card">
    <img src="../images/project1.jpg" alt="PowerElectronics Project">
    <div class="card-content">
      <h3>PowerElectronics Project (Undergraduate Thesis)</h3>
      <p>Developed a leakage current mitigation strategy using T6 topology for Solar Energy Integration in Grid.</p>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="project-card">
    <img src="../images/project2.jpg" alt="PLMD - IoT Project">
    <div class="card-content">
      <h3>PLMD - IoT (Undergrad 7th Semester Project)</h3>
      <p>Developed an IoT-based house energy monitoring device for demand-side response.</p>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="project-card">
    <img src="../images/project3.jpg" alt="UNET">
    <div class="card-content">
      <h3>UNET</h3>
      <p>Implemented the UNET model from scratch for image segmentation tasks in Python.</p>
    </div>
  </div>

  <!-- Project 4 -->
  <div class="project-card">
    <img src="../images/project4.jpg" alt="Neural Style Transfer">
    <div class="card-content">
      <h3>Neural Style Transfer</h3>
      <p>Replicated the neural style transfer technique to apply artistic styles to images.</p>
    </div>
  </div>
</div>

<h1>My Hiking Clips</h1>
<div class="image-grid">
  <div>
    <img src="../images/Narayanthanmy.jpg" alt="Narayanthan">
    <p>Narayanthan Hiking Trail</p>
  </div>
  <div>
    <img src="../images/N1.jpg" alt="Hiking">
    <p>Serenity in Nature</p>
  </div>
  <div>
    <img src="../images/n2.jpg" alt="Adventure">
    <p>Exploring Hidden Trails</p>
  </div>
  <div>
    <img src="../images/Sikles1.jpg" alt="Sikles">
    <p>The Sikles Experience</p>
  </div>
</div>

<style>
  .projects-section, .image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 10px;
  }

  .project-card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
  }

  .project-card img, .image-grid img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
  }

  .project-card .card-content, .image-grid div {
    text-align: center;
    padding: 10px;
  }

  .image-grid img {
    height: auto;
  }

  .image-grid p {
    margin-top: 5px;
    font-size: 0.9rem;
    color: #555;
  }
</style>
