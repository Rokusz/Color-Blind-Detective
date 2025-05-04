# Colorblind-Detective
## Overview
<p align="justify"> As a team of five, in 5 weeks we created a puzzle VR experience in which you investigate a murder in a small house as a colorblind detective. We were given a case from a real client, XR Lab (www.xr-lab.nl). We regularly met with our client, showing progress and asking for feedback, but ultimately, we had a lot of freedom. Our target audience was “Designers,” and we narrowed it down to visual designers. The goal of the project was to let designers get to know others, to allow them to be more considerate of the different needs of people when making their work. After a lot of back and forth, we settled on an experience through the eyes of a colorblind person. </p>

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

### Design
<p align="justify"> I have a condition where I get temporary retina sunburn induced colorblindness. In bright sun, I can’t see much green and orange. Naturally, it was my suggestion to make our project revolve around color blindness. The team also liked my suggestion of turning it into a murder mystery. 

My original suggestion was to have 2 levels, where in one, you get to walk around in the house as the murder victim, and in the other, you get to walk around the house as the detective. You would switch between the realities with a button click at any time, appearing in the same house location. The differences would be that the victim is colorblind and the detective has normal vision, and some objects would be changed around the level. This would allow for more intricate puzzles, as the murder clues could be hidden in both realities. Furthermore, it would double the exploration value with little extra work required. Lastly, by keeping the level similar between realities, it would give a direct comparison of how colorblind people see the world.

This did not happen for two reasons: we didn’t think we had nearly enough time to execute this idea, but more than that, my teammates said it was not “realistic.” Despite our client even stating that our project does not need to be grounded in reality. Ultimately, it was my vote against two others and two that were indifferent. 

We finally decided to settle on a one level version, where the player has to solve a murder mystery puzzle whilst being able to switch between two types of colorblindness. </p>
