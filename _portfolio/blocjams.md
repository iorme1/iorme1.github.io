---
layout: post
title: BlocJams
feature-img: "img/sample_feature_img.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030966/blocjams_1x.png"
short-description: BlocJams music player

---

 <p>  My first project in the Bloc program was creating a functional music playing web application.  The project assignment illustrated a step by step process to accomplish this from start to finish.  Most of the code for building this web application was provided to me by the Bloc program, though I frequently had to fill in sections with my own code implementation in order to get certain parts of the site functioning properly.  This project was a great introduction into how a web application is created using JavaScript/HTML/CSS. <p>

	<p>  My goals in this project were to understand the code and the logic behind it, to become familiar with the development process, and to become accustomed to using best practices when creating a web application.  In order to gauge my understanding of the code used throughout this web application, I was tasked with assignments that involved writing my own code implementations to get certain parts of the site functioning properly.  The web application was first created using vanilla JavaScript, followed by a jQuery refactoring and ending with an Angular refactoring.<p>

  <p> During the vanilla JavaScript phase of the project, one of the more interesting and practical lessons I had learned involved understanding the process of implementing play/pause/switch song functionality.
  I gained practice with learning how to map out the logic in a step by step manner before implementing complex code. I had to visualize and understand what needed to be shown to the user given certain events.  In order to do this I had to think about what the user should see when they: hover their mouse over a song, click a song to play it, click a song to pause it, click a different song than the currently playing song, etc.  This taught me an excellent lesson in the development process.  I learned the importance of writing a solution out in pseudo-code or plain english before writing the code out itself.  I also gained practice with translating pseudo-code or English into JavaScript.</p>

  <p> The following images/explanations show a break down of the logic I needed to follow in order to implement play/pause functionality on our site.</p>


{:.center}
![]({{ site.baseurl }}/assets/images/song_num_to_pause.gif)
<p>-When a user clicks a song to play it, the song number must change to a pause button.</p>
{:.center}
![]({{ site.baseurl }}/assets/images/pause_remain.gif)
<p>-When the users mouse leaves the table row of the currently playing song, the pause button should remain.</p>
{:.center}
![]({{ site.baseurl }}/assets/images/pause_to_num.gif)
<p>-When the user switches songs, the previously playing song's table cell should revert the content back to the song number.</p>
{:.center}
![]({{ site.baseurl }}/assets/images/play_on_hover.gif)
<p>-When the user hovers over each of the songs that are not playing, the play button should still appear; we don't, however, want to show the play button when we hover over the playing song.</p>


  <p> After the BlocJams web app was created using JavaScript/HTML/CSS, I was introduced to jQuery.  The goal of this portion of the project was to familiarize myself with a JavaScript library to see how it can be used to simplify the development process.  I noticed that using jQuery substantially reduced the amount of code we needed to write in order to build the same web application.  Refactoring the web app with jQuery also gave me yet another chance to be involved and further internalize the development process from start to finish.<p>

  <p> Finally, we refactored the BlocJams web app once more using Angular.  With Angular, we had to re structure the entire application to fit into a SPA style. We used an external module called “UI-ROUTER" that helped determine the states of the application. What I learned most from using Angular was the idea behind encapsulation and how it is extremely important to avoid the use of global functions/variables to keep your code from interfering with or overlapping and shadowing other code.  Every separate javascript file was written in an IFFE to accomplish this.  Once again, I was able to be involved and contribute to the development process of a web application and gain more experience using my own computer/text-editor/files to accomplish this from start to finish. </p>

	<p>  My experience with creating a web application using Javascript, jQuery and Angular was invaluable and helped me gain a better understanding and a big picture view of the development process.  Through my trial and error of implementing my own code in this project, I gained experience pouring over lines of code to find errors or typos.  My debugging skills improved rapidly throughout this project and I found myself becoming more and more skillful in understanding how to find bugs using logic and tracing through the web of interconnected functions and variables to find them.</p>
