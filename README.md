<h1 align="center">My team page</h1>

<div align="center">
   Solution for a challenge from  <a href="http://devchallenges.io" target="_blank">Devchallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://fernandonz.github.io/devChallenge_my-team-page/">
      Demo
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenges/hhmesazsqgKXrTkYkt0U">
      Challenge
    </a>
  </h3>
</div>

## Overview

- What was your experience?
- What have you learned/improved?

At first I was very confused by the measures of the grid cells with the measures of my "card", I thought that defining the "grid-template-column and grid-template-row" defined the size of my "card" but I was wrong, gtc and gtr only define the size of my "card" if it does not have a defined size. When I understood this. I just had to specify my "card" a size less than the cell size, and use "align-self: end" on the container children to get to the result. I think I could have also used a margin.

I also discovered something new in css: writing-mode: vertical-lr  ☺️
