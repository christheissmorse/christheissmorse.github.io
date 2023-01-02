---
collection: projects
downloads:
  paper: /files/publications/vae.pdf
  repo: https://github.com/morse165/testing-openpilot/tree/main/VisionModel
identifier: "vae_id"
title: "VAE-Guided Testing Framework for OpenPilot’s Vision Model"
year: 2022
abstract: "The control of autonomous driving systems is largely based on their visual predictions. However, due to the uncertainty and complexity of real-world driving environments, these systems will need to safely handle unfamiliar inputs. Otherwise, a misinterpretation of these inputs can lead to costly real-world misbehaviors. We examine the vision model from OpenPilot, an open-source autonomous driving system that has been widely deployed in recent years. Since the majority of their training data has been collected from users on highways, we suspect that there are underrepresented features in the training set that have led to the insufficient training of their vision model. To detect these high-risk features, we introduce a VAE-guided approach for the extraction of rare features from OpenPilot’s training set and a framework for the independent testing of their vision model. Our results suggest that there are rare features that cause uncertainty in OpenPilot’s visual predictions for their Automated Lane Centering (ALC) system."
teaser: /publications/car.gif
---
