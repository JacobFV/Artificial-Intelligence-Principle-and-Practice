---
layout: home
title: Home
permalink: /
description: Free 8-day workshop bringing you to the cutting-edge of artificial intelligence theory and technique!

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

This completely free workshop is intended to give undergraduate and graduate students from all science and engineering majors a fast introduction to the modern artificial intelligence theory and technique with special emphasis on machine learning. 

It will be held in 80-minute online sessions twice a week over 8 days of October. To accomodate varied schedules, sessions will be held on:

- Mondays and Wednesdays (12:30 - 1:50pm)
- Tuesdays and Thursdays (12:30 - 1:50pm)
- Saturdays (2:00 - 3:20pm and 3:30 - 4:50pm)

All times listed in Central time (UTC−05:00). First session: **Sat. Oct. 2 / Mon. Oct. 4 / Tue. Oct. 5 2021**

Github repo: [https://github.com/JacobFV/Artificial-Intelligence-Principle-and-Practice](https://github.com/JacobFV/Artificial-Intelligence-Principle-and-Practice)

Zoom link: [https://us04web.zoom.us/j/2940991499?pwd=QndzY0llY3NqRlEwYXYrWDVDTGRDdz09](https://us04web.zoom.us/j/2940991499?pwd=QndzY0llY3NqRlEwYXYrWDVDTGRDdz09)

---

We will study:

 - 'Classical' AI shortcomings and modern symbolic progressing techniques
 - Machine learning fundamentals, neural networks, and deep learning
 - Computer vision, generative modeling, sequence modeling, natural language processing, deep graph processing 
 - Reinforcement learning, multi-agent RL, self-supervised learning, transfer learning, and domain generalization
 - MLops, AI safety, and ethics

---

We will use:

 - Python
 - `NumPy`, `Pandas`, `Matplotlib`
 - `TensorFlow`, `Keras`,  `transformers`
 - OpenAI `gym`, `PettingZoo`, `ThreeDWorld`
 - `tensorboard`, `wandb`, docker, and the Google Cloud Platform

---

Before signing up, you should already be able to calculate basic derivatives, apply probability & statistics to toy problems, and write simple Python programs. 

If your neurons have accumulated sufficient presynaptic evidence and your reward estimator feels like it's ready to explode, please [join](https://jacobfv.github.io/Artificial-Intelligence-Principle-and-Practice/#signup) this exciting workshop!

---

<form id="signup">
    <div id="beforeSignup">
        <input type="hidden" name="accessKey" value="0d04c522-1740-4f6c-aa50-ecc292a089bc">
        <input type="text" style="width: 100%; margin: 3pt;" name="name" placeholder="name" > <br>
        <input type="text" style="width: 100%; margin: 3pt;" name="email" placeholder="email"> <br>
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

<span style="color:grey"><b>ps: (Much of this document was drafted [using an autoregressive language model](https://copilot.github.com/).)</b></span>