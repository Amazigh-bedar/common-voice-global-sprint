---
layout: simple
title: "Leaderboard"
---

# Be proud of your progress

<h2>
  <span class="capitalize">T</span>
  <span class="capitalize-content">
    his is the current ranking. Scores are calculated by assigning<br />1 point for each report and 3 for each issue.
  </span>
</h2>

<div class="content-box">
  <h3 class="content-title content-title--uppercase">
    <span class="title-frame"></span>
    Leaderboard
    <span class="title-frame title-frame--rotate-180"></span>
  </h3> 

  <table id="leaderboard" class="hidden">
    <tbody>
    </tbody>
  </table>

  <p id="loading">Loading...</p>
  <p id="no-results" class="hidden">There are currently no reports.</p>
</div>

<script src='https://cdnjs.cloudflare.com/ajax/libs/tabletop.js/1.5.1/tabletop.min.js'></script>
<script src="{{ site.baseurl }}/js/leaderboard.js"></script>