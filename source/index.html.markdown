---
title: "Workout"
---
<div class="w3-content" style="max-width:1100px;margin-top:80px;margin-bottom:80px">

  <div class="w3-panel">
    <h1 id="workout-title"><b>Happy Coding!</b></h1>
    <p>Ruby Methods</p>
    <div class="pull-right">
      <button type="button" id="btn_back"  class="w3-button w3-green w3-padding-large"><span class="fa fa-arrow-left" aria-hidden="true"></span> Back</button>
      <button type="button" id="btn_next"  class="w3-button w3-green w3-padding-large">Next <span class="fa fa-arrow-right" aria-hidden="true"></span></button>
    </div>
  </div>

  <!-- Grid -->
  <div class="w3-row-padding">
    <div class="w3-col s6 w3-margin-bottom">
      <ul class="w3-ul w3-border w3-center w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Text Editor</li>
        <li class="w3-padding-16">
          <div id="editor" class="w3-input w3-border"></div>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <button class="w3-button w3-green w3-padding-large" id="btn_run">Run <span class="fa fa-play" aria-hidden="true"></span></button>
          <button class="w3-button w3-teal w3-padding-large" id="btn_clear">clear <span class="fa fa-remove" aria-hidden="true"></span></button>
        </li>
      </ul>
    </div>
    <div class="w3-col s6 w3-margin-bottom">
      <ul class="w3-ul w3-border w3-center w3-hover-shadow">
        <li class="w3-dark-grey w3-xlarge w3-padding-32">Code Output</li>
        <li class="w3-padding-16">
          <div id="output" class="w3-input w3-border"></div>
        </li>
      </ul>
    </div>
  </div>
</div>

<script>Opal.load('workout');</script>
