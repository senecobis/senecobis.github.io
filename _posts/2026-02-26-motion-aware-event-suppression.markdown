---
layout: post
title: "Motion-aware Event Suppression for Event Cameras"
date: 2026-02-26 16:53:36 +00:00
image: /images/motion-aware-event-suppression.jpg
categories: research
author: "Roberto Pellerito"
authors: "Roberto Pellerito, Nico Messikommer, Giovanni Cioffi, Marco Cannici, Davide Scaramuzza"
venue: "RSS 2026"
arxiv: https://arxiv.org/abs/2602.23204
paper: /pdfs/Motion-aware_Event_Suppression_for_Event_Cameras.pdf
video: https://rpg.ifi.uzh.ch/event_suppression/static/videos_/video_draft.mp4
code: https://github.com/uzh-rpg/event_suppression
website: https://rpg.ifi.uzh.ch/event_suppression/
---

We introduce the first framework for Motion-aware Event Suppression, which learns to filter events triggered by
independently moving objects and ego-motion in real time. The model jointly segments independently moving objects in the
current event stream while predicting their future motion, enabling anticipatory suppression of dynamic events before
they occur. The lightweight architecture achieves 173 Hz inference on consumer-grade GPUs with less than 1 GB of memory
usage, outperforming previous state-of-the-art methods on the challenging EVIMO benchmark by 67% in segmentation
accuracy while operating at a 53% higher inference rate. The method also accelerates Vision Transformer inference by 83%
via token pruning and improves event-based visual odometry accuracy, reducing Absolute Trajectory Error by 13%.
