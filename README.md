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
<img src="https://github.com/user-attachments/assets/0d69c23c-d1c0-4cdb-b55a-3ee0dcba2dd7" alt="Nomral Vision">
<img src="https://github.com/user-attachments/assets/db020908-1e0d-4e2b-a58f-2e40efb8ab3f" alt="Nomral Vision">
