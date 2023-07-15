<table><tr><td> <em>Assignment: </em> HW HTML5 Canvas Game</td></tr>
<tr><td> <em>Student: </em> Sameer Butt (snb22)</td></tr>
<tr><td> <em>Generated: </em> 7/9/2023 4:27:56 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-451-M23/hw-html5-canvas-game/grade/snb22" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a branch for this assignment called&nbsp;<em>M6-HTML5-Canvas</em></li><li>Pick a base HTML5 game from&nbsp;<a href="https://bencentra.com/2017-07-11-basic-html5-canvas-games.html">https://bencentra.com/2017-07-11-basic-html5-canvas-games.html</a></li><li>Create a folder inside public_html called&nbsp;<em>M6</em></li><li>Create an html5.html file in your M6 folder (do not put it in Project even if you're doing arcade)</li><li>Copy one of the base games (from the above link)</li><li>Add/Commit the baseline of the game you'll mod for this assignment&nbsp;<em>(Do this before you start any mods/changes)</em></li><li>Make two significant changes<ol><li>Static changes like hard-coded colors/values will not count at all (i.e., changing shapes/colors/values that are globally defined and set only once.</li><li>Direct copies of my class example changes will not be accepted (i.e., just having an AI player for pong, rotating canvas, or multi-ball unless you make a significant tweak to it)</li><li>Significant changes are things that change with game logic or modify how the game works. Static changes like hard-coded colors/values will not count at all (i.e., changing shapes/colors/values that are globally defined and set only once). You may however change such values through game logic during runtime. (i.e., when points are scored, boundaries are hit, some action occurs, etc)</li></ol></li><li>Evidence/Screenshots<ol><li>As best as you can, gather evidence for your first significant change and fill in the deliverable items below.</li><li>As best as you can, gather evidence for your significant change and fill in the deliverable items below.</li><li>Remember to include your ucid/date as comments in any screenshots that have code</li><li>Ensure your screenshots load and are visible from the md file in step 9</li></ol></li><li>In the M6 folder create a new file called m6_submission.md</li><li>Save your below responses, generate the markdown, and paste the output to this file</li><li>Add/commit/push all related files as necessary</li><li>Merge your pull request once you're satisfied with the .md file and the canvas game mods</li><li>Create a new pull request from dev to prod and merge it</li><li>Locally checkout dev and pull the merged changes from step 12</li></ol><p>Each missed or failed to follow instruction is eligible for -0.25 from the final grade</p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Game Info </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> What game did you pick to edit/modify?</td></tr>
<tr><td> <em>Response:</em> <p>Collect the Squares&nbsp;<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the direct link to the html5.html file from Heroku Prod (i.e., https://mt85-prod.herokuapp.com/M6/html5.html)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://snb22-prod.herokuapp.com/M6/html5.html">https://snb22-prod.herokuapp.com/M6/html5.html</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the pull request link for this assignment from M6-HTML5-Canvas to dev</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/sameernbutt/IT202-451/pull/41">https://github.com/sameernbutt/IT202-451/pull/41</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Significant Change #1 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe your change/modification</td></tr>
<tr><td> <em>Response:</em> <p>I added special targets with different powerups. Every time a target is generated,<br>it has a 50% chance to be a special target (50% chance to<br>be regular). There are 5 different power-ups/effects which all have an equal chance<br>of occurring. Additionally, to distinguish them from the normal target, they are generated<br>as a different color target. Blue targets make the player move slower, yellow<br>targets make the player move faster, purple targets double the current score, orange<br>targets give 2 extra seconds and a 10 point bonus, and pink targets<br>reverse the directions of the keys (i.e. pressing the up key moves the<br>player down and so forth). Any effect on the player wears off by<br>the time they collect another target. Additionally, for the purple target the score<br>would reset to 1 if the current score is negative (will explain in<br>the next change).<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshot of the change while playing (try your best as some changes may be nearly impossible to capture)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.34.33image.png.webp?alt=media&token=cba7f72e-4fc3-49a1-a25c-d929903595a4"/></td></tr>
<tr><td> <em>Caption:</em> <p>Squares game with one of the orange targets appearing. Take note of the<br>current score<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.34.43image.png.webp?alt=media&token=b8acb13b-ba3c-4fd2-8ce2-65707635534a"/></td></tr>
<tr><td> <em>Caption:</em> <p>Orange target providing a 10 point bonus (as can be seen in the<br>top left). There is also a time bonus which is not as visible<br>because time was taken to paste the screenshot<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.37.03image.png.webp?alt=media&token=c3295c21-cc25-4f63-9ccc-759ccae6a7a7"/></td></tr>
<tr><td> <em>Caption:</em> <p>The purple target is now present. Take note of the current score<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.37.20image.png.webp?alt=media&token=7b92bd63-c4f1-4a47-985f-6bb6785308bb"/></td></tr>
<tr><td> <em>Caption:</em> <p>Player collecting the purple target, and now the score is doubled (top left)<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of the relevant lines of code that implement your change (make sure your ucid and the date are shown in comments) In the caption briefly describe/explain how the code snippet works.</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.48.56image.png.webp?alt=media&token=3e22fabc-5423-46f7-9f16-ce87ede3c269"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid (snb22) is present at the top prior to my implemented change. This<br>fragment showcases the activation of the target&#39;s power-up. Upon the player colliding with<br>the target, the program first resets any changed values, such as direction and<br>speed, to their original ones. Then, it checks by case what color the<br>target using it&#39;s hex color. The comments are to identify which color is<br>which and what the power-up is supposed to be. Upon identifying the color,<br>the given power-up is implemented as mentioned previously, and then the program continues<br>to the next part. To set the speed, the speed variable is simply<br>changed. To add more time and points, the countdown and score variables are<br>implemented respectively.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.49.10image.png.webp?alt=media&token=24847325-39cb-4a68-95dc-c595adc37d5f"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid is present at the top. Here, the target is assigned a color,<br>using a distribution done by Math.random()*10, with 6-10 being green and the others<br>given a color.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.51.47image.png.webp?alt=media&token=7451d275-560b-4a70-bc29-9f2319f9c1ea"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid is present at the top. When a key is pressed to move<br>the square, the program checks to see if the reverse variable is set<br>to true by the pink square. If so, the direction is changed. Otherwise<br>the square moves as normal<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T19.54.02image.png.webp?alt=media&token=00547b48-d42c-4ff8-a397-933127efbcb2"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid is present at the top. the reverse variable is set to false<br>by default<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Significant Change #2 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe your change/modification</td></tr>
<tr><td> <em>Response:</em> <p>The second change changes the scoring system of the game. Anytime the player<br>moves, there is a chance that a point is deducted from the total<br>score (1/7 chance by default). The chance of this may change if a<br>power-up is taken. It becomes 1/4 after hitting a blue target, 1/20 after<br>hitting a yellow one, and 1/10 after hitting a pink one. This change<br>is done by the use of the variable moveMultiplier, which works in such<br>a way that with any move, there is a 1/moveMultiplier chance that a<br>point is deducted. The variable is set to 7 by default as mentioned<br>before. As for the logic, Math.random*moveMultiplier is used, and if the resulting number<br>rounds down to 1, then a point is deducted. To determine when a<br>move is made, the program checks for a change in the direction of<br>the player by using variables to track the player&#39;s current direction and change<br>it accordingly. Additionally, as part of the scoring system, there is a 1/10<br>chance of a player earning 10 extra points instead of 1 point for<br>picking up a target.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshot of the change while playing (try your best as some changes may be nearly impossible to capture)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.02.59image.png.webp?alt=media&token=15c90dd7-f191-454a-8ef2-ecb74b6aeb24"/></td></tr>
<tr><td> <em>Caption:</em> <p>-1 points in the top left because a move was made and the<br>odds were not in our favor<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.04.37image.png.webp?alt=media&token=9d818b0c-ec20-478e-890e-5033fe106612"/></td></tr>
<tr><td> <em>Caption:</em> <p>(new game) score in the top left prior to picking up a normal<br>target<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.05.22image.png.webp?alt=media&token=9f8a58b7-c360-46e6-b482-e4a4c09d356c"/></td></tr>
<tr><td> <em>Caption:</em> <p>rare 10 point bonus in the top left after picking up the target<br>(-1 because of an unlucky move)<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of the relevant lines of code that implement your change (make sure your ucid and the date are shown in comments) In the caption briefly describe/explain how the code snippet works.</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.11.09image.png.webp?alt=media&token=c3f53cba-bc99-4131-bd41-b89aa55c6df8"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid is present at the top. This shows the initialization of the moveMutliplier<br>variable and other variables meant to track whether or not the player is<br>already moving left, right, up, or down (false by default since the player<br>is stationary to start)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.12.48image.png.webp?alt=media&token=a63d4ef4-13a7-4c9e-83e4-a8f8119778e9"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid at the top. This function is used to reset at the moving<br>statuses to false as needed<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.19.35image.png.webp?alt=media&token=928628b2-53fe-4632-99bb-48d4aa48c0e2"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid at the top. Here, there some additions made when checking if a<br>key is pressed. Anytime a key is pressed, the code checks to see<br>if the square is already moving in the corresponding direction. If so, it<br>proceeds as normal. If not, it resets the direction variables with resetMovingStatus(), sets<br>the correct direction variable to true, then runs Math.random() to see if a<br>point is deducted. Then, it proceeds as normal.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.20.57image.png.webp?alt=media&token=917a2089-c0e8-489f-a66c-ec5b248585ba"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid at the top. This uses Math.random() similarly as mentioned before to give<br>a 1/10 chance of 10 points, with just 1 point being awarded otherwise.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fsnb22%2F2023-07-09T20.22.46image.png.webp?alt=media&token=76427cf9-4233-48a2-b642-cad15003af6c"/></td></tr>
<tr><td> <em>Caption:</em> <p>ucid at the top. This shows the moveMultiplier variable being reset everytime a<br>target is touched and the corresponding colors changing it if need be<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Discuss </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Talk about what you learned during this assignment and the related HTML5 Canvas readings (at least a few sentences for full credit)</td></tr>
<tr><td> <em>Response:</em> <p>In this assignment, I learned about the capabilities of the HTML5 canvas. I<br>learned how I can implemented cool features like games and have them correspond<br>to player input. Additionally, to create interesting shapes and characters, I learned functions<br>and how to do those. With event listeners and set intervals, timers and<br>scores can be implemented to make an engaging game for the user. I<br>was able to further improve my understanding of hex colors and javascript and<br>utilize much of it to code a game&#39;s logic.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-451-M23/hw-html5-canvas-game/grade/snb22" target="_blank">Grading</a></td></tr></table>