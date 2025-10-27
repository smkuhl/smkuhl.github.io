---
title: "Music Recommendation Algorithm"
excerpt: "Generates personalized classical music recommendations by identifying pieces with similar characteristics using content-based and collaborative filtering. <br/><img src='/images/4-chief-sealth-side-by-side.jpg'  width='50%'/>"
collection: portfolio
---

![Seattle Symphony](/images/4-chief-sealth-side-by-side.jpg)
[Photo: Seattle Symphony](https://www.seattlesymphony.org/)

This project integrates data from [Open Opus](https://openopus.org/) and Spotify to generate personalized classical music recommendations. It first retrieves classical music specific metadata such as composer, period, and genre from Open Opus and merges it with general track metadata from Spotify such as temp, time signature, and key. Using this enriched dataset, the model applies content-based filtering (matching pieces with similar musical attributes) and collaborative filtering (using similarities in user behavior and preference) to recommed works that align with a user's existing playlist. This approach aims to ensure suggestions are both musically coherent and informed by community listening behavior.

[GitHub Repo](https://github.com/smkuhl/classical-music-recommender/tree/main)