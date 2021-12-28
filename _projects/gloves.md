---
layout: project
title: 'Project Gloves'
caption: Exploring Self-Supervised Learning and MLOps
description: >
  This project was for exploring generative algorithms along with MLOps technologies.
date: '01-01-2021'
image: 
  path: /assets/img/projects/mittens_1.jpg
  srcset: 
    1920w: /assets/img/projects/mittens_1.jpg
    
    #960w:  /assets/img/projects/hydejack-site@0,5x.jpg
    #480w:  /assets/img/projects/hydejack-site@0,25x.jpg
links:
  - title: Github
    url: https://github.com/Benjamin-Etheredge/gloves
  - title: Weights & Biases
    url: https://hydejack.com/
    
sitemap: false
---

# Project Gloves

The original goal of the project was simple: Create a facial recognition system
for my pets. It was named in ommage to one of my cats, Mr. Murder Mittens (picutred above).

But it ended up taking many twists and turns and has not yet reached its end goal. 


## Sidetracks
It ended up mostly servering as a code base
for exploring next MLOps technologies.

#### Kubeflow
This was one of the first projects I adapted for Kubeflow. This was at a rare point 
in time where the Kubeflow installation was still possible in one attempt.

See <link> for my experience with Kubeflow. Spoiler alert, it was not positive.

Since then, I have not been able to get a working version of Kubeflow 

## Future Work
I want to get the networks running on embeded hardward (like a jetson nano). 

I want to add some optimization steps to the project to trim down the network and optimize it for inference on a chosen embeded hardware platform (e.g., pruning, qunatizing, etc.).


### Technologies Used
- Tensorflow / Keras
- Docker
- Kubeflow