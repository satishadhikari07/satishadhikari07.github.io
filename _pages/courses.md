---
collection: Courses
permalink: /courses/
---

<h1 style="text-align: left; margin-bottom: 40px;">📜 Online Courses and Certification</h1>

<style>
  .courses-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    padding: 0 20px;
  }

  .certificate-card {
    border: 1px solid #e0e0e0;
    border-radius: 12px;
    padding: 16px;
    flex: 1 1 calc(33.333% - 40px);
    max-width: 340px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .certificate-card:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
  }

  .certificate-card img {
    width: 100%;
    height: 200px; /* make image taller */
    object-fit: cover; /* keeps image from stretching */
    border-radius: 8px;
  }

  @media (max-width: 992px) {
    .certificate-card {
      flex: 1 1 calc(45% - 40px);
    }
  }

  @media (max-width: 600px) {
    .certificate-card {
      flex: 1 1 100%;
    }

    .certificate-card img {
      height: auto;
    }
  }
</style>

<section class="courses-section">

  <!-- Certificate 1 -->
  <div class="certificate-card">
    <img src="https://your-image-link.com/ml-specialization.jpg" alt="Machine Learning Specialization">
    <h3 style="margin-top: 15px;">Unsupervised Learning, Recommenders, Reinforcement Learning</h3>
    <a href="https://coursera.org/verify/YOUR_CERTIFICATE_ID" target="_blank" style="text-decoration: none; color: #007acc;">🔗 View Certificate</a>
  </div>

  <!-- Certificate 2 -->
  <div class="certificate-card">
    <img src="../images/Certificate_Advanced Learning Algorithm.png" alt="AI for Everyone">
    <h3 style="margin-top: 15px;">Advanced Learning Algorithm</h3>
    <a href="https://www.coursera.org/account/accomplishments/verify/BY6CVHMA9COE" target="_blank" style="text-decoration: none; color: #007acc;">🔗 View Certificate</a>
  </div>

  <!-- Certificate 3 -->
  <div class="certificate-card">
    <img src="../images/Certificate_Supervised Machine Learning Regression and Classification.png" alt="Deep Learning Specialization">
    <h3 style="margin-top: 15px;">Supervised Machine Learning Regression and Classification</h3>
    <a href="https://www.coursera.org/account/accomplishments/verify/645YUM5RE5TN" target="_blank" style="text-decoration: none; color: #007acc;">🔗 View Certificate</a>
  </div>

</section>
