---
layout: post
title: "Neural Events: Discrete Asynchronous Autoencoders for Event-Based Vision"
date: 2026-06-18 06:26:25 +00:00
image: /images/neural-events.jpg
categories: research
author: "Roberto Pellerito"
authors: "Roberto Pellerito, Daniel Gehrig, Shintaro Shiba, Davide Scaramuzza"
venue: "arXiv preprint"
arxiv: https://arxiv.org/abs/2606.19835
paper: https://arxiv.org/pdf/2606.19835
code: https://github.com/uzh-rpg/NeuralEvents
website: https://rpg.ifi.uzh.ch/neural_events/
---

We introduce neural events, a compact asynchronous representation that summarizes local patterns in raw event streams
using discrete learned codes. A discrete asynchronous encoder processes incoming events and emits a neural event only
when the assigned code changes, preserving precise timing while reducing redundant data. Networks trained on neural
events match or exceed state-of-the-art performance on object detection and classification while reducing the event
rate by a factor of 2.0.
