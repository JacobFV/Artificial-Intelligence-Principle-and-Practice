---
layout: home
title: Home
permalink: /
description: Free 8-day workshop bringing you to the cutting-edge of artificial intelligence theory and technique!

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

Mon/Wed and Tue/Thur sessions held at TDB.
**Lecture** (12:30 - 1:00pm): interactive undergraduate-style lecture<br> 
**Lab** (1:10 - 1:50pm): hands-on engineering experience<br>
**Deep Dive** (2:00 - 3:20pm on Mon/Wed only): graduate-style paper and peer-focused discussion<br>

Day 1: **Oct. 4 / Oct. 5, 2021**

[Syllabus](https://jacobfv.github.io/Artificial-Intelligence-Principle-and-Practice/syllabus)

---

We will study:

 - 'Classical' AI <br>
 - Symbolic techniques <br>
 - Machine learning <br>
 - Neural networks and deep learning <br>
 - Computer vision <br>
 - Sequence modeling <br>
 - Natural language processing <br>
 - Reinforcement learning (including multi-agent RL) <br>
 - Human-level artificial intelligence <br>
 - AI safety and ethics <br>

---

We will use:

 - Python <br>
 - NumPy, Pandas, Matplotlib <br>
 - TensorFlow, Keras, Huggingface <br>
 - OpenAI Gym, PettingZoo, ThreeDWorld <br>
 - tensorboard, wandb <br>
 - docker, Google Cloud Platform <br>

---

Students should already be able to:

 - calculate the derivative of a polynomial <br>
 - apply basic probability & statistics to toy problems <br>
 - write simple Python programs <br>

---

Course expectations:

 ❌ no homework <br>
 ❌ no tests <br>
 ❌ no costs (this course is free) <br>
 ⚠️ **This course is not accredited by UTA**<br>
 ✅ individualized activities <br>
 ✅ machine learning <br>
 ✅ (most importantly) human learning <br>

---

If your neurons have accumulated sufficient presynaptic evidence and your reward estimator feels like it's ready to explode, please [join me](https://jacobfv.github.io/Artificial-Intelligence-Principle-and-Practice/#signup) on this exciting journey!

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

<br><br>

<span style="color:grey"><b>ps: (Much of this document was drafted [using artificial intelligence](https://copilot.github.com/).)</b></span>