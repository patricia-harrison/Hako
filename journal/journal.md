# 1701QCA Final project journal: *HAKO - Desk Companion*

<!--- As for other assessments, fill out the following journal sections with information relevant to your project. --->

<!--- Markdown reference: https://guides.github.com/features/mastering-markdown/ --->

## Related projects ##
<!--- Find about 6 related projects to the project you choose. A project might be related through  function, technology, materials, fabrication, concept, or code. Don't forget to place an image of the related project in the appropriate folder and insert the filename in the appropriate places below. Copy the markdown block of code below for each project you are showing. --->

### *Arduino MP3 Player project* ###

<!--- Modify code to insert image of related project below --->


<!--- Fill out name and link to related project in the code below. --->
[Arduino MP3 Player Project](https://educ8.tv/arduino-mp3-player/])

This project is related to mine as it is centered around the DFPlayer module. The related project is a tutorial which teaches the reader to create an MP3 player using an Arduino and the DFPlayer mini-module. In a brief description of the project, it is stated that that the tutorial is *heavily* reliant on the aformentioned module, which is the same with my HAKO project. 

Both of these projects provide the user with an interactive experience through pressing a button and playing one of however many tracks the DFPlayer has been provided. However, this tutorial uses three buttons; one to play and pause, one to play the next track and another to play the previous track, while I implemented a single button that will play a random track. 
<!--- Include information about why this project is related to yours. --->


### *Dice* ###

<!--- Modify code to insert image of related project below --->
![Image](dice.png)

<!--- Fill out name and link to related project in the code below. --->
[Dice](https://microbit.org/projects/make-it-code-it/dice/)

This tutorial is related to mine through the use of the "pick random -- to --" maths code block which is provided in the makecode section on the Micro:bit website. The tutorial walks the reader through how to make their own responsive dice with the Miro:bit. When the micro:bit is shaken, it will trigger the code to randomly pick a number between 1 and 6. Once the number is picked, it wil be displayed on the inbuilt LED screen. My project follows a very similar concept. When button A is pressed, it will randomly pick an .mp3 file and play it while displaying a flashing heart. 

<!--- Include information about why this project is related to yours. --->

<!--- Repeat code above for a total of 6 related projects --->

### *Micro:bit Christmas Tree* ###

<!--- Modify code to insert image of related project below --->


<!--- Fill out name and link to related project in the code below. --->
[Miro:bit Christmas Tree](https://www.dfrobot.com/blog-1132.html)

This project is related to mine because it uses the DFPlayer mini module. The projects shows readers how to create a rotating christmas tree with LEDs and music. When button A is pressed, the LEDs light up, the DFPlayer module begins to play music and the 360 servo begins to spin clockwise. When AB is pressed, it cause the servo to spin anticlockwise and when button B is pressed, it turns everything off. 

<!--- Include information about why this project is related to yours. --->

<!--- Repeat code above for a total of 6 related projects --->

### *Arduino Application- Test DFPlayer Mini MP3 Module* ###

<!--- Modify code to insert image of related project below --->
![Image](miniradio.jpg)

<!--- Fill out name and link to related project in the code below. --->
[Test DFPlayer Mini MP3 Module](https://www.dfrobot.com/blog-277.html)

This project is similar to mine because it is centered around the use of the DFPlayer mini module. The project's purpose is to make a mini, functioning radio with a DFPlayer, an arduino and two speakers. However, the creator of this project did not wish randomise the music played from the radio and instead set a specific order in which the tracks would play. 
<!--- Include information about why this project is related to yours. --->

<!--- Repeat code above for a total of 6 related projects --->

### *Portable Toy Speaker* ###

<!--- Modify code to insert image of related project below --->
![Image](toyradio.png)

<!--- Fill out name and link to related project in the code below. --->
[Portable toy speaker](https://www.dfrobot.com/blog-482.html)


This project is related to mine because it is centered around sound. The creator of this project made a miniature toy speaker using an arduino, an analog sound sensor and a HiVi speaker. Once the power on button is pressed, a song will play. 
<!--- Include information about why this project is related to yours. --->

<!--- Repeat code above for a total of 6 related projects --->

### *Death Star word clock* ###

<!--- Modify code to insert image of related project below --->
![Image](deathstar.jpg)

<!--- Fill out name and link to related project in the code below. --->
[Deather Star Word Clock](https://www.dfrobot.com/blog-534.html)


This impressive project was created to not only function as a clock but also so the user can play a functioning game of snake. This project can be related to mine because the created used a DFPlayer for all sound effected used in their creation. 

<!--- Include information about why this project is related to yours. --->

<!--- Repeat code above for a total of 6 related projects --->

## Other research ##

Various tutorials and projects where read through in order to figure out the desired code. The help of my tutor also heavily impacted the success of this project. 
The tutorials used to create this project are:

https://github.com/DFRobot/DFPlayer-Mini-mp3/blob/master/DFPlayer_Mini_Mp3/examples/DFPlayer_receive/DFPlayer_receive.ino

https://www.codespeedy.com/play-random-mp3-from-a-folder-in-python/

https://cyaninfinite.com/playing-music-tracks-with-df-robot-mp3-player-module/#Playing_the_tracks

https://reprage.com/post/dfplayer-mini-cheat-sheet

https://techtutorialsx.com/2019/03/24/microbit-micropython-generating-random-numbers/

https://pynative.com/python-random-shuffle/

https://microbit-micropython.readthedocs.io/en/latest/tutorials/random.html


<!--- Include here any other relevant research you have done. This might include identifying readings, tutorials, videos, technical documents, or other resources that have been helpful. For each particular source, add a comment or two about why it is relevant or what you have taken from it. You should include a reference or link to each of these resources. --->

## Conceptual development ##

### Design intent ###
To create a fun and interactive desk companion which provides the user with positive affirmations and encouragement. 
<!--- Include your design intent here. It should be about a 10 word phrase/sentence. --->

### Design ideation ###
The initial idea for this project was to create some sort of interactive desk “toy” or device that would act as a type of “companion”, in a sense. This idea had been sparked from a few different things - the companion cube from the game Portal, Cozmo and Vector robots made by Anki, tamagochi and the screaming roomba which was hacked by the YouTuber Michael Reeves. These pieces of inspiration combined into the idea for a wholesome desk robot companion which would provide the user with affirmations, kind words and reminders to stay hydrated and to look after themselves. The intended purpose for this device is to act as a ‘friend’ of sorts for those who spend a lot of time working at their desk and often forget to take breaks. It could also help ease anxiety, intrusive thoughts and lowered self esteem through its kind and cute demeanor. The intended physical interaction between the robot and the user is to be kept simple, so that anyone can use it. The interaction will preferably occur through a button on the top or “face” of the robot (the side of the box with a small LED screen, in which the robot will show expressions).

A possible name for the companion robot “Hako” (はこ) which means box/case/crate in japanese. I thought this name was cute, short and fitting, considering that this robot companion will essentially be a little talking cubed companion that sits on the usered desk. The expressions have been influenced by both of the Anki robots (Vector and Cozmo) and cute japanese emoticons. The design of the box will preferably be kept simple and clean. Hence the cube shape and simple interactions the user can experience (the press of a button which triggers the scripted lines and the expressioned the user can see via the LED screen on the front side of the robot.)
<!--- Document your ideation process. This will include the design concepts presented for assessment 2. You can copy and paste that information here. --->

### Final design concept ###

The final design concept is very similar to the concept thought up in the previous assignment. Everything stayed to same, except for the LED screen. Because of the current circumstances, I was unable to purchase my desired LED screen and decided to make use of the imbedded one of the micro:bit. As expressions are difficult to communicate through this small LED screen, the emotions planned for HAKO to display were not implemented. However, the little LED heart still stayed. Everytime HAKO "speaks", the heart will flash. There were also a few design aditions to the front face of HAKO. One of these new aditions is a simple greeting phrase in japanese which translates to "Hello, I'm HAKO!".
<!--- This should be a description of your concept including its context, motivation, or other relevant information you used to decide on this concept. --->

### Interaction flowchart ###

![Image](flow.png)
<!--- Include an interaction flowchart of the interaction process in your project. Make sure you think about all the stages of interaction step-by-step. Also make sure that you consider actions a user might take that aren't what you intend in an ideal use case. Insert an image of it below. It might just be a photo of a hand-drawn sketch, not a carefully drawn digital diagram. It just needs to be legible. --->

## Process documentation ##

To get to this point in the project required a lot of searching and rummaging around the internet for similar projects, products and code. The start of this project consisted entirely of brainstorming a product that would:

- aid with mental health
- encourage users to look after themselves (e.g. stay hydrated)
- provide affirmations to the user and provide wholesome encouragement
- to be placed on desks in offices/bedrooms
Essentially, the initial idea for this product came from the desire I had for a cute, encouraging desk 'companion'. I knew that for me, something like this little robot would be very helpful for when I am struggling with anxiety, self-esteem issues and intrusive thoughts. Sometimes all I need is something small to cheer me up, e.g. getting a cute meme from a friend could instantly snap me out of that mood. Thus I believe a little robot that provide wholesome affirmations and reminders at the press of the button could not only help myself, but possible others who feel the same.

The process of finalising this project was quite frustrating as there were quite a few issues. These issues were mainly code based. There were times of switching between the code 'blocks' provided by micro:bit and other situations which called for python code. Through the switching between these two coding options many things began to go wrong. When testing the code, it would often only play one track before either being cut off by a loud buzzing or would simply replay the same track over and over. This was quite a hurdle to get over, as there were many various ways (povided from online tutorials) which were supposed to stop the intrusive buzzing and allow the code to randomly pick an .mp3 file. After many fails, I had approached my tutor, who after helping me with the code, was able to figure out the main issue with my code. After appling the suggested code, the micro:bit would successfully pick random files to play after button A had been pressed. That left the second issue - the intrusive buzzing. After trying a few solutions suggested by people whom had experienced a similar problem, only to have those solutions fail, I thought it'd be best to try and re-wire everything. Once everything had been re-wired, the buzzing was less prominent, but still there. After some thinking, I thought that it could simply be the power - that there was not enough being trasnmitted to the DFPlayer and the speaker. Once replacing the batters, the buzzing simply went away. 

( Any code that had been attempted from sources will be found above in the "other research" section. )

![Image](designcom.png)
![Image](inside1.jpg)
![Image](inside2.jpg)
<!--- In this section, include text and images (and potentially links to video) that represent the development of your project including sources you've found (URLs and written references), choices you've made, sketches you've done, iterations completed, materials you've investigated, and code samples. Use the markdown reference for help in formatting the material.-->


## Final code ##

![Image](code.png)
<!--- Include here screenshots of the final code you used in the project if it is done with block coding. If you have used javascript, micropython, C, or other code, include it as text formatted as code using a series of three backticks ` before and after the code block. See https://guides.github.com/features/mastering-markdown/ for more information about that formatting. --->

## Reflection ##

I feel the most successful part of the project was definitely the final code and the voice lines. The external look of the project definitely needed a lot of improvements, however the original idea was for HAJO to simply look like a box (hence the name, which translate to 'box' or 'crate').
Throughout the duration of this course, I have been able to learn a lot of skills which all came in handy for this project. Depite me having learnt better time management skills through this class, they did not do much to help as the code wasn't functioning up until the day before this assignment was due. Despite all of the researching and viewing of similar projects, the only source that made a true difference was David Harris (thank you), whom had essentially saved the code. 

The parts of this project I feel to be novel is the concept of having a desk 'companion' as the company Anki has successfully created an interactive and seemingly alive little robot (Vector and Cozmo). Though HAKO is no where near as interactive as Cozmo or Vector, HAKO does provide the user with affirmations which can be accessed simply by the press of a button. 

I feel that the overall execution of the project could have been much better if only the current circumstances were more desirable. Having a lack of aesthetically pleasing and lasting materials and no real one-on-one interaction (not having the same imaginatve atmosphere to work in) definitely cause the quality of this project to drop and took much longer than it should have taken to create. If I were to extend this project, I would love to implement a proper LED screen for expressions and a cleaner, more aesthetic physical appearance. 

Over all, I am still happy with this project, considering everything. 
<!--- Describe the parts of your project you felt were most successful and the parts that could have done with improvement, whether in terms of outcome, process, or understanding.


