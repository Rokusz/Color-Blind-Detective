# Colorblind-Detective

## Download and tech overview
You can download this project at: https://trinket-interactive.itch.io/color-blind-detective

<p align="justify"> This project was made using the Meta Quest 3, but it works on any modern VR headset. We used Unity 6 URP. </p>

## Overview
<p align="justify"> As a team of five, in 5 weeks we created a puzzle VR experience in which you investigate a murder in a small house as a colorblind detective. We were given a case from a real client, XR Lab (www.xr-lab.nl). We regularly met with our client, showing progress and asking for feedback, but ultimately, we had a lot of freedom. Our target audience was “Designers,” and we narrowed it down to visual designers. The goal of the project was to let designers get to know others, to allow them to be more considerate of the different needs of people when making their work. After a lot of back and forth, we settled on an experience through the eyes of a colorblind person. </p>

<p align="center">
  <video src='https://github.com/user-attachments/assets/68c75dfd-35aa-48be-a2ed-d60fd63c0e1b' width=180/>
</p>

## My roles
+ Environent art (Living room)
+ Game designer
+ VR setup
+ Color blindness implementation
+ Research

## My contributions

### Research

<p align="justify"> As a team, we spent a lot of time researching and interviewing people with colorblindness (turns out there are more around you than you would ever expect). I conducted 2 interviews with colorblind people, and there were two main takeaways. First, problematic color combinations, such as red and green, are only really an issue when there is a lack of difference in saturation and brightness. Second, the interviewees said colorblindness is not tragically life-changing, but some tasks, such as identifying road signs, become incredibly difficult. Almost all the people our team interviewed named puzzles, both in video games and in real life, as incredibly difficult. These two findings pushed us to make our game experience into a puzzle game with parts of it that are completely invisible to one of the colorblindness types we chose. </p>

<p align="justify"> Additionally, I was responsible for researching and implementing colorblindness simulations in Unity. Turns out you can’t just disable the red channel when rendering if you are red deficient. I ended up finding a mathematical formula that allows me to calculate the RGB values of the renderer to faithfully represent what colorblind people see. The final solution I made was a drag-and-drop settings preset that can be applied to the global post-process volume. These are the results: </p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/0d69c23c-d1c0-4cdb-b55a-3ee0dcba2dd7" alt="Nomral Vision">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/db020908-1e0d-4e2b-a58f-2e40efb8ab3f" alt="Nomral Vision">
</p>

<p align="center">
  <video src='https://github.com/user-attachments/assets/d20724e4-34dd-461c-b861-5edff356f863' width=180/>
</p>
    
### Design

<p align="justify"> I have a condition where I get temporary retina sunburn induced colorblindness. In bright sun, I can’t see much green and orange. Naturally, it was my suggestion to make our project revolve around color blindness. The team also liked my suggestion of turning it into a murder mystery. </p>

<p align="justify"> My original suggestion was to have 2 levels, where in one, you get to walk around in the house as the murder victim, and in the other, you get to walk around the house as the detective. You would switch between the realities with a button click at any time, appearing in the same house location. The differences would be that the victim is colorblind and the detective has normal vision, and some objects would be changed around the level. This would allow for more intricate puzzles, as the murder clues could be hidden in both realities. Furthermore, it would double the exploration value with little extra work required. Lastly, by keeping the level similar between realities, it would give a direct comparison of how colorblind people see the world. </p>

<p align="justify"> This did not happen for two reasons: we didn’t think we had nearly enough time to execute this idea, but more than that, my teammates said it was not “realistic.” Despite our client even stating that our project does not need to be grounded in reality. Ultimately, it was my vote against two others and two that were indifferent. </p>

<p align="justify"> We finally decided to settle on a one level version, where the player has to solve a murder mystery puzzle whilst being able to switch between two types of colorblindness. </p>

### My requirements for the level and puzzle designers

<p align="justify"> Since this was my first VR project, I wanted to make sure that we played into VR's strengths. So, I made a list for the other designers to keep in mind, tying it to what is unique and fun to the players. </p>

+ Exploration in VR is more engaging, so place parts of the puzzle in different rooms.
+ You have the full range of motion; feel free to hide things in places you wouldn't in a traditional FPS game, but keep in mind that the player needs to find it, so affordances guiding the player towards it are a must.
+ Physics is a core part of VR. We should have at least a couple of objects that you can grab and carry around.
+ World scaling in VR is completely different than in 3rd or 1st person games. You can’t just use the 30% scaling rule, so if some objects look too small or too big - they are.

### Environment art

<p align="justify"> Over a week and a half, I put together the living room of our level. </p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/271580d4-20df-44d1-ae10-2b59682b0f1c" alt="Nomral Vision">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fcbd7686-0e59-4faf-bcf2-8828bbe53eff" alt="Nomral Vision">
</p>
