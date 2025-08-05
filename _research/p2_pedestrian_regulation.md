---
title: "Robot-Assisted Pedestrian Regulation: Learning optimal human-robot interaction (past project)"
excerpt: "Overview: This project investigates an emerging application of assistive robots in pedestrian regulation. We propose a novel robot-assisted pedestrian regulation framework that utilizes the dynamic pedestrian-robot interaction during their collective movements. The insights of the effect of pedestrian-robot interaction on the pedestrian movements and the optimal robot motion for desired pedestrian regulation objectives are provided.  Adaptive dynamic programming (ADP) algorithm and deep reinforcement learning algorithms are designed to learn optimal control of robot motion. The proposed adaptive learning framework is applied to a merging flow scenarios to reduce the risk of crowd disasters. Furthermore, to address the challenge of feature representation of complex human motion dynamics under the effect of HRI, an end-to-end robot motion planner based on deep neural network is proposed and trained using a deep reinforcement learning algorithm. The new approach avoids hand-crafted feature detection and extraction and thus improves the learning capability for complex dynamic problems. "
collection: portfolio
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Assistive Robotic Manipulation</title>
  <style>
    /* Container */
    .content {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }
    
    /* Section headings */
    h2 {
      font-size: 1.5rem;
      margin-top: 2rem;
      margin-bottom: 1rem;
      border-bottom: 2px solid #ddd;
      padding-bottom: 0.5rem;
    }
    
    /* Figure grid */
    .figure-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin: 1rem 0 2rem;
    }
    
    figure {
      margin: 0;
      text-align: center;
    }
    
    figure img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    
    figcaption {
      margin-top: 0.5rem;
      font-size: 0.9rem;
      color: #666;
    }
    
    /* List styling */
    .approach-list {
      margin: 0 0 1.5rem 1.2rem;
    }
    .approach-list li {
      margin-bottom: 0.8rem;
    }
    
    /* Citation style */
    .citation {
      font-size: 0.85rem;
      color: #999;
      margin-left: 0.3rem;
    }
  </style>
</head>
<body>
  <div class="content">
  
    <h2>1. Skill-Based Adaptive Shared Autonomy</h2>
    <div class="figure-grid">
      <figure>
        <img src="/images/Main_diagram-6.png" alt="Optimization overview">
        <figcaption>Overview of our shared autonomy method for assistive robotic manipulation. At the core of our method is a skill-inference-based adaptive arbitration between user control and autonomous assistance. [1]</figcaption>
         <video
            controls
            width="100%"
            style="border-radius:8px; box-shadow:0 2px 6px rgba(0,0,0,0.1); margin-top:12px;"
          >
            <source src="/images/RAL_video_final.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
          <figcaption>Demonstration of pick-and-place and cup-stacking tasks.</figcaption>
      </figure>
    </div>
        
    <h2>Publications:</h2>
    <ul class="references-list">
      <li>[1] Atan, U., Bharadwaj, V.R. and Jiang, C. (2025). A probabilistic Inference Approach for Skill-Based Shared Autonomy in Assistive Robotic Manipulation. IEEE Robotics and Automation Letters (RA-L), 2025</li>
      <li>[2] Atan, U., Bharadwaj, V.R. and Jiang, C. (2024). Assistive Control of Robot Arms via Adaptive Shared Autonomy. In 2024 IEEE International Conference on Advanced Intelligent Mechatronics (AIM), pp. 1096-1102</li>
    </ul>
    
  </div>
</body>
</html>
