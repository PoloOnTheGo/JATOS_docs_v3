---
title: Example Studies Table
keywords: example studies, jspsych
tags:
summary: Tabulated list of example studies 
sidebar: mydoc_sidebar
permalink: Example-Studies-Table.html
folder:
toc: false
last_updated: 05 May 2019
---

### Overview
JATOS gives you complete freedom on the client side. You can do whatever you like! But these examples might help as a starting point. 

Since JATOS cares mostly for the server side it gives you the freedom to use in your study code whatever technologies work in browsers (e.g. HTML5 canvas, CSS3 or 3D graphics with WebGL). Additionally browser-side JavaScript libraries or frameworks like [jQuery](https://jquery.com/), [Bootstrap](http://getbootstrap.com/), [Highcharts](http://www.highcharts.com/), [p5](https://p5js.org/), or [jsPsych](http://www.jspsych.org/) are possible and will smooth out your path to quick and easy development. Of course the same is true for CSS modules (e.g. [Pure.css](http://purecss.io/), [Material Design](http://www.google.com/design/spec/material-design/introduction.html)).

Click on the study name to download the .zip file and [import it into JATOS](http://www.jatos.org/Get-started.html).  

<b>If you have trouble downloading a study (common in Safari browsers) check [this troubleshooting tip](Troubleshooting.html#downloading-a-study--exporting-a-study-fails-eg-in-safari-browsers).</b>

If you wrote an example study that you'd like to share, please feel free to [contact us](Contact-us.html) and we'll include it in this page!



| Study Name        | Brief Description   | Frameworks Used | JATOS Features   | Example Image  |
|-------------------|-------------------|-------------------|-------------------|-------------------|
| [Hello World](https://github.com/JATOS/JATOS_examples/raw/master/examples/hello_world.zip) | Everything starts with a Hello World! | - | - | -  |
| [Go-/No-Go](https://github.com/JATOS/JATOS_examples/raw/master/examples/go-nogo_task_(using_jspsych_6).zip) | Go/NoGo task. Includes instructions | [jsPsych](https://www.jspsych.org/) | - |  <img src="images/example-studies/Screenshot_gonogo.png" href="images/example-studies/Screenshot_gonogo.png" style="width:200%"/>|
| [Randomize Tasks Between Workers](https://github.com/JATOS/JATOS_examples/raw/master/examples/randomize_tasks_between_workers.zip) §| Template to randomly assign participants to conditions A, B, or C (with fixed numbers for each condition). | - | [Batch session](http://www.jatos.org/Session-Data-Three-Types.html)| <img src="images/example-studies/Screenshot_randomization_between_workers.png" style="width:200%"/>|
| [Lexical Decision](https://github.com/JATOS/JATOS_examples/raw/master/examples/lexical_decision_(using_jspsych).zip) | Participants classify whether a string of letters is a word or a nonword. From [factorsdb](https://github.com/jodeleeuw/factorsdb/tree/gh-pages/_experiments). | [jsPsych](https://www.jspsych.org/) | - | <img src="images/example-studies/Screenshot_lexicalDecision_word.png" style="width:200%"/>| 
| [Lexical Decision](https://github.com/JATOS/JATOS_examples/raw/master/examples/lexical-decision.osexp.zip) | An example of running OpenSesame experiments with JATOS via OSWeb. | [OpenSesame](https://osdoc.cogsci.nl/), [OSWeb](https://osdoc.cogsci.nl/manual/osweb/#the-osweb-extension) | - |  <img src="images/example-studies/Screenshot_osweb_lexical_decision.png" style="width:200%"/>|
| [Random Dot Kinematogram](https://github.com/JATOS/JATOS_examples/raw/master/examples/rdk.zip) § | A random dot kinematogram (RDK) for online visual psychophysics and the use in web browsers. By _Sivananda Rajananda, Hakwan Lau, Brian Odegaard_ ([preprint](https://www.biorxiv.org/content/early/2017/09/21/192377)). | [jsPsych](https://www.jspsych.org/) | - | <img src="images/example-studies/Screenshot_rdk.png" style="width:200%"/> |
| [Demographic and Survey Questions](https://github.com/JATOS/JATOS_examples/raw/master/examples/survey.js_ui_example.zip) | [SurveyJS](http://surveyjs.org) is an easy to use library with a great online interface to create surveys and questionaires.| [SurveyJS](https://surveyjs.io/) | -| <img src="images/example-studies/survey-js-screenshot.png" style="width:200%"/> |
| [Instructions with Google Slides](https://github.com/JATOS/JATOS_examples/raw/master/examples/intro_with_google_slides.zip) § | Use Google Slides to make an quick, easy and versatile instruction page. Might not be the prettiest, but it does the job.| [Google Slides](https://www.google.com/slides/about/) | - | <img src="images/example-studies/Screenshot_intro_slides.png" style="width:200%"/> |
| [p5.js 2D Graphics Showcase](https://github.com/JATOS/JATOS_examples/raw/master/examples/p5.js_examples.zip) § | [p5.js](https://p5js.org/) is a graphics library to easily create 2D and 3D graphics without deeper knowledge of how those graphics are rendered. Additionally one can add user interaction, video, sound, or capture from the webcam or the mic. Have a look at their [example section](https://p5js.org/examples/). | [p5.js](https://p5js.org/) | - | <img src="images/example-studies/p5-js-screenshot5.gif" style="width:200%"/>|
| [Video](https://github.com/JATOS/JATOS_examples/raw/master/examples/video_example_study.zip) | Shows how to embed a video with HTML 5 by using the browsers video player, YouTube, or the [video.js](http://www.videojs.com/) JavaScript library. | - | - |  <img src="images/example-studies/Screenshot_videoExample2.png" style="width:200%"/>|
| [Results in CSV](https://github.com/JATOS/JATOS_examples/raw/master/examples/results_as_csv_example.zip) | Simple example of how to store results in CSV format. | - | - |  <img src="images/example-studies/Screenshot_csv_example.png" style="width:200%"/>|
| [Simple Consent Form](https://github.com/JATOS/JATOS_examples/raw/master/examples/consent_form.zip) | Simple example of a consent form with text and buttons ‘I agree’ and ‘Cancel’. | - | - |  <img src="images/example-studies/Screenshot_consent_form.png" style="width:200%"/>|
| [Introduction and Consent with Preview Feature](https://github.com/JATOS/JATOS_examples/raw/master/examples/consent_form_and_introduction_with_preview_feature.zip) | This mobile-friendly example just has an introduction component that includes a consent text. | - | [Preview links](Worker-Types.html#preview-links) |  <img src="images/example-studies/Screenshot_preview_showcase.png" style="width:200%"/>|
| [2048 Game](https://github.com/JATOS/JATOS_examples/raw/master/examples/2048.zip) | This addictive game is created by [Gabriele Cirulli](https://github.com/gabrielecirulli/2048). | - | - |  <img src="images/example-studies/Screenshot_2048Game.png" style="width:200%"/>|
| [Plot Data](https://github.com/JATOS/JATOS_examples/raw/master/examples/data_visualization_-_example.zip) | A slightly different use for JATOS: as a regular server to display an HTML page that displays study results. | [Highcharts](http://www.highcharts.com/) | - |  <img src="images/example-studies/Screenshot_dataDisplay_scatter.png" style="width:200%"/>|
| [Attentional Capture](https://github.com/JATOS/JATOS_examples/raw/master/examples/reward_capture.osexp.zip) | Standard task to show how to use OSWeb with JATOS. | [OpenSesame](https://osdoc.cogsci.nl/), [OSWeb](https://osdoc.cogsci.nl/manual/osweb/#the-osweb-extension) | - |  <img src="images/example-studies/Screenshot_osweb_reward_capture.png" style="width:200%"/>|
| [Survey (Self Regulation)](https://github.com/JATOS/JATOS_examples/raw/master/examples/self_regulation_survey.zip) | A standard questionnaire. Taken from [expfactory](http://expfactory.github.io/). | [JQuery Form](https://jqueryform.com/) | - |  <img src="images/example-studies/Screenshot_selfRegulationSurvey.png" style="width:200%"/>|
| [Invaders Game](https://github.com/JATOS/JATOS_examples/raw/master/examples/invaders_with_phaser.zip) | Classical arcade game. From Phaser's [examples page](github.com/photonstorm/phaser-examples). | [phaser.io](http://phaser.io/) | - |  <img src="images/example-studies/Screenshot_spaceInvaders.png" style="width:200%"/>|
| [HexGL Game](https://github.com/JATOS/JATOS_examples/raw/master/examples/hexgl.zip) | Futuristic racing [game](https://github.com/BKcore/HexGL) by [Thibaut Despoulain](http://bkcore.com/). | HTML5, WebGL  | - |  <img src="images/example-studies/Screenshot_hexgl.png" style="width:200%"/>|
| [Visual Metacognition](https://github.com/JATOS/JATOS_examples/raw/master/examples/perceptual_metacognition_(jatosified).zip) | Taken from the [experiment factory](http://expfactory.github.io/). | [jsPsych](https://www.jspsych.org/) | - |  <img src="http://www.jatos.org/images/example-studies/Screenshot_perceptional_metacognition_stumili.png" style="width:200%"/>|
| [Clock Drawing](https://github.com/JATOS/JATOS_examples/raw/master/examples/clock_drawing.zip) | Submit images as result data to JATOS by converting them into base64-encoded text.| [jsPsych](https://www.jspsych.org/) | - |  <img src="images/example-studies/Screenshot_clock_drawing.png" style="width:200%"/>|
| [Potato Compass](https://github.com/JATOS/JATOS_examples/raw/master/examples/potato_compass.zip) | Drag & drop elements. | [interact.js](http://interactjs.io/) | - |  <img src="images/example-studies/Screenshot_potatoCompass.png" style="width:200%"/>|
| [Study, Group, and Batch Session](https://github.com/JATOS/JATOS_examples/raw/master/examples/study__group__and_batch_session.zip) §| See JATOS’ three different[ session types](http://www.jatos.org/Session-Data-Three-Types.html) in action. | - | Study, Group, and Batch session data  |  <img src="images/example-studies/ChatExample_4.png" style="width:200%"/>|
| [Group Chat](https://github.com/JATOS/JATOS_examples/raw/master/examples/group_chat.zip) §| Let members of a *group* talk to each other. | - |  [Group Session](http://www.jatos.org/Session-Data-Three-Types.html), [Group Broadcast Message](Write-Group-Studies-II-JavaScript-and-Messaging.html#broadcast-messaging) |  <img src="images/example-studies/Screenshot_chat.png" style="width:200%"/>|
| [Batch Chat](https://github.com/JATOS/JATOS_examples/raw/master/examples/batch_chat.zip) §| Let members of a *batch* talk to each other. | - |  [Batch Session](http://www.jatos.org/Session-Data-Three-Types.html) |  <img src="images/example-studies/Screenshot_chat.png" style="width:200%"/>|
| [Prisoner's Dilemma](https://github.com/JATOS/JATOS_examples/raw/master/examples/prisoner's_dilemma.zip) §| [Game](https://en.wikipedia.org/wiki/Prisoner%27s_dilemma) in which two workers interact with each other in the same study run. | - | [Group Study](Example-Group-Studies.html), [Group Direct Messaging](Write-Group-Studies-II-JavaScript-and-Messaging.html#direct-messaging) |  <img src="images/example-studies/Screenshot_prisonersDilemma.png" style="width:200%"/>|
| [Snake Game](https://github.com/JATOS/JATOS_examples/raw/master/examples/snake_game.zip) §| Multiplayer real-time [snake game](https://en.wikipedia.org/wiki/Snake_(video_game)). | - | [Group Study](http://www.jatos.org/Example-Group-Studies.html), [Group Broadcast Message](Write-Group-Studies-II-JavaScript-and-Messaging.html#broadcast-messaging) |  <img src="images/example-studies/Screenshot_snakeGame.png" style="width:200%"/>|



§ Requires JATOS version 3.1.1 or newer