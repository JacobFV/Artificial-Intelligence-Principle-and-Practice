---
layout: home
title: Home
permalink: /
description: Free 8-day journey to the cutting-edge artificial intelligence theory and technique.

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

<p style="background-color: dark-grey">
<b>Lecture</b> (1:00 - 1:50pm): interactive undergraduate-style lecture<br> 
<b>Lab</b> (2:00 - 2:50pm): hands-on engineering experience<br>
<b>Deep Dive</b> (3:00 - 3:50pm): graduate-style paper and peer-focused discussion<br>
Times may be adjusted per general student availability.
</p>

Day 1: <b>Oct. 4 / Oct. 5, 2021</b>

---

We will study:
<ul>
    <li>Symbolic approaches</li>
    <li>Machine learning</li>
    <li>Neural networks and deep learning</li>
    <li>Computer vision</li>
    <li>Sequence modeling</li>
    <li>Natural language processing</li>
    <li>Reinforcement learning (including multi-agent RL)</li>
    <li>Human-level artificial intelligence</li>
    <li>AI safety and ethics</li>
</ul>

---

We will use:
<ul>
    <li>Python</li>
    <li>SciPy suite</li>
    <li>Jax</li>
    <li>PyTorch</li>
    <li>TensorFlow (python, tflite and tf.js)</li>
    <li>Huggingface</li>
    <li>OpenAI Gym</li>
    <li>PettingZoo</li>
    <li>TDW</li>
    <li>Docker</li>
    <li>Cload Compute</li>
</ul>

---

Student expectations:
<ul>
<li>calculate the derivative of a function</li>
<li>apply probability & statistics to toy problems</li>
<li>write simple Python programs</li>
</ul>

If many students already have deeper roots in math, statistics, information theory, physics, biology, neuroscience, or psychology, we will discuss advanced principles of artificial intelligence engineering from those perspectives.

---

Course expectations:
 ❌ no homework <br>
 ❌ no tests <br>
 ❌ no costs (this course is free) <br>
 ⚠️ <b>This course is not accredited by UTA</b><br>
 ✔️ individualized activities <br>
 ✔️ machine learning <br>
 ✔️ (most importantly) human learning <br>

<div style="background-color: white; padding: 6pt;">
If your neurons have accumulated sufficient presynaptic evidence and your reward estimator feels like it's ready to explode, please join me on this exciting journey!

[More information](https://jacobfv.github.io/Artificial-Intelligence-Principle-and-Practice/details)
</div>

---

<form id="signup">
    <div id="beforeSignup">
        <input type="hidden" name="accessKey" value="0d04c522-1740-4f6c-aa50-ecc292a089bc">
        <input type="text" style="width: 100%; margin: 3pt;" name="name" placeholder="name" > <br>
        <input type="text" style="width: 100%; margin: 3pt;" name="email" placeholder="email (UTA preferred)"> <br>
        <input type="submit" value="Sign Up" class="highlightButton" style="font-weight: 800; border-color: darkblue; background-color: lightblue; margin: 3pt;" />
        <!-- If we receive data in this field submission will be ignored -->
        <input type="text" name="honeypot" style="display: none;">
    </div>
    <div id="afterSignup" style="max-height: 0; opacity: 0">
        <p id="welcomeMessage">I look foreward to seeing you!</p>
    </div>
</form>
<script>
$('#signup').submit(function(e){
    e.preventDefault();
    $.ajax({
        url: 'https://api.staticforms.xyz/submit',
        type: 'post',
        data:$('#signup').serialize(),
        success:function(){
            // form submitted successfully
            $("#beforeSignup").animate({
                "max-height": 0,
                opacity: 0
            }, 1000);
            $("#afterSignup").animate({
                "max-height": 10000,
                opacity: 1
            }, 1000);
        }
    });
});
</script>
