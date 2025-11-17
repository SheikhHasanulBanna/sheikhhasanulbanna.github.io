---
title: "Implement and Modify WestwoodBR Congestion Control Algorithm"
collection: projects
author_profile: true
layout: single
permalink: /projects/westwood/
excerpt: "Implemented Westwood BR and modified the congestion window updation algorithm and monitored for change in performance"
---
**Overview**  
Implemented Westwood BR and modified the congestion window updation algorithm and monitored for change in performance.

**Key Points**

- Implemented Westwood BR congestion control algorithm according to the research paper.
- Made small modifications to the algorithm by adding an extra level that further controls the window size according
  to the traffic level.
- Afterwards, monitored the throughput, drop rate and window size change in various wireless networks.
- The modified algorithm performed better than base Westwood and Newreno in almost all cases. The change in
  window size was more varied than Westwood but more conservative than Newreno.

**Tech Stack**

- C++, NS2, Bash

<div id="mklogaCarousel" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner rounded-2 shadow">
    <div class="carousel-item active">
      <img src="/images/projects/westwood/Screenshot_1.png" class="d-block w-100" alt="Westwood output Layout 1">
    </div>
    <div class="carousel-item">
      <img src="/images/projects/westwood/Screenshot_2.png" class="d-block w-100" alt="westwood output Layout 2">
    </div>
  </div>

<button class="carousel-control-prev" type="button" data-bs-target="#mklogaCarousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#mklogaCarousel" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
