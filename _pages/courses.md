---
collection: courses
permalink: /courses/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        h2 {
            border-bottom: 2px solid #4f9efd;
            display: inline-block;
            margin-bottom: 20px;
        }
        .certificate-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .certificate-card {
            padding: 15px;
            border-radius: 8px;
            width: 100%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }
        .certificate-card img {
            width: 100%;
            height: auto; /* Allow the height to adjust automatically */
            max-height: 250px; /* Limit the max height */
            object-fit: contain; /* Ensures image is fully contained without being cut off */
            border-radius: 4px;
            aspect-ratio: 16 / 9; /* Maintain a proper aspect ratio (16:9, you can change this if needed) */
        }
        .certificate-title {
            font-size: 14px; /* Reduced font size for the certificate title */
            margin: 10px 0;
        }
        .view-button {
            background-color: #4f9efd;
            color: white;
            padding: 8px 12px; /* Reduced padding for smaller button */
            border: none;
            border-radius: 4px;
            text-decoration: none;
            display: inline-block;
            text-align: center;
            font-size: 12px; /* Reduced font size for the button */
            transition: background-color 0.3s ease;
        }
        .view-button:hover {
            background-color: #3b7dd8;
        }
    </style>
</head>
<body>
    <h2>Machine Learning Specialization</h2>
    <div class="certificate-container">
        <div class="certificate-card">
            <img src="/mnt/data/image.png">
            <div class="certificate-title">Unsupervised Learning, Recommenders, Reinforcement Learning</div>
            <a href="https://example.com/certificate1" class="view-button" target="_blank">VIEW CERTIFICATE</a>
        </div>

<div class="certificate-card">
            <img src="../images/Certificate_Advanced Learning Algorithm.png">
            <div class="certificate-title">Advanced Learning Algorithm</div>
            <a href="https://www.coursera.org/account/accomplishments/verify/BY6CVHMA9COE" class="view-button" target="_blank">VIEW CERTIFICATE</a>
        </div>

 <div class="certificate-card">
            <img src="../images/Certificate_Supervised Machine Learning Regression and Classification.png">
            <div class="certificate-title">Supervised Machine Learning Regression and Classification</div>
            <a href="https://www.coursera.org/account/accomplishments/verify/645YUM5RE5TN" class="view-button" target="_blank">VIEW CERTIFICATE</a>
        </div>
    </div>
</body>
</html>
