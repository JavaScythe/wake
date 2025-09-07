Total 25 hours

## 8/20/25: Project inception
I looked at my cheap alarm clock and realized what a sad piece of e waste it was. It had functions for alarm and radio that are never used, and lost about 13 minutes over the last two years. I decided this would be no more.

One part I did like about the existing one was its ceiling projection. It projected a 8 segment display on the ceiling to show time. I quickly beat the brakes off this existing one and recovered the module. I discovered what appeared to be a four wire protocol + likely 5v for light, 3.3 for logic and ground of course.

I also wanted to drive both a buzzer and a small 3 inch speaker cone for fun/utility

2 Hours

## 8/21/25: Those who scope creep
The other inhabitant of my nightstand was next: my alexa. Used solely for alarms, it was a waste of bandwidth. It left its mark on this project though: I deciced to have the edge light up, just like its predecessor.

This presented a problem: how do I (oh by the way i chose cheapest esp32 for this project with pcb antenna) mount the esp32 on the edge for EMI but also mantain a ring of leds?

I chose some of the ICs like power and mcu

2 Hours

## 8/22/25: Schematic creation
In addtion to the lighting, I also have a LED strip controlled via breadboard on my nightstand. It would be easy to mount the mofsets in this board and have it control them instead. A fourth mofset is used to control a IR led to control a projector.

<img width="1608" height="1096" alt="image" src="https://github.com/user-attachments/assets/a7edc27e-2d55-4158-a37f-35ff84fdba59" />

4 Hours

## 8/23/25: Schematic work
I settled on a semisquare layout. Not copying alexa, (bro there's no mic there's no assistant please no sue), and maxmimum perimeter for MOAR leds.

I also included a OLED for some insight as well as finding some buttons that would fit. Not sure how many I will put on.

<img width="1084" height="1020" alt="image" src="https://github.com/user-attachments/assets/1652f447-6ddc-4409-86a4-9f653640efff" />

4 Hours

## 8/24/25: Layout work
Finished the LEDS. very painful to do. I think I will do 3 buttons

<img width="1150" height="1047" alt="image" src="https://github.com/user-attachments/assets/1bb39d72-3899-492b-be90-cba715c991ca" />

2 Hours

## 8/25/25: Layout + Buzzer
I looked into implementing the buzzer. This was much harder than I though it would be. It's difficult to get a balance between cost, quality (audio) of implementation, and easy of development. For context I want variable frequency, not just a static tone.

NO picture i added like 3 symbols disconnected

2 Hours

## 8/26/25: Buzzer complete
Will be done with MCP6022. Here is the releveant scheamtic portion

<img width="1623" height="953" alt="image" src="https://github.com/user-attachments/assets/cc19b042-a313-4548-b16c-229348b5565e" />

1 Hour

## 8/27/25: Routing
Slow day in school = many hours of routing. This was a messy-ish board because of the mixed power, circular shape, and two layer. It should likely be fine... the router is very close by in the same room.

<img width="1076" height="1047" alt="image" src="https://github.com/user-attachments/assets/4cc9ff0c-aad3-46d2-be54-b8ad247ab2bb" />

Additionally I flipped the button footprint so I could have their bodies inside the PCB for less height.. to make the buttons on par with the LEDS once I make case.

4 Hours

## 9/4/25: Hiatas and minor routing.

Fixed a few ratlines left on board. Added mounting holes for case design

1 Hour

## 9/6/25: Case and writeup

Designed the case for easy mounting. The buttons I will do some trial and error on, just a matter of some tweaks. Mount should be high enough to fit speaker.

<img width="1267" height="1020" alt="image" src="https://github.com/user-attachments/assets/e78c67e0-9955-45b7-b6ee-e0028963900e" />

3 Hours

