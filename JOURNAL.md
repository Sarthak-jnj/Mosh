---

Title : Mosh
Author : Sarthak Juneja
Description : A small scale custom built drone on ESP32 architecture. Ultra light in weight, affordable, ideal first build and not painful to break. It uses cheap brushed motors and easily available sensors. Battery is one thing a little hard to get the exact one, but there is enough headroom for something a few grams heavier, I aimed for a Sub-50 gram build.
Created at: 2026-11-17
---

# 11/17/2026: Made a rough Design layout and reseached parts

_Time spent: 3h_

Spent the day researching ideal parts for such a drone, took weight and performance into account to eliminate multiple options of items and find out ideal products since i had to make an BOM (not finalized yet), Kept an eye on any incompatabilities by constantly checking over google, read a couple datasheet to ensure the motors don't struggle and fought with the whole internet trying to get sources where those items are in stock and don't require a head for delivery fees. Furthermore I also drew a rough deisgn in my head and made a few fine adjustments to make it better resilient from splitting along the fibres (wooden frame design) and also not twist itself to death. Noted down these points into a notebook as a rough schematic before I start CAD testing them to make the design stronger. I COULDN'T manage to record this session since I had some problem with Wifi today, so i just did the research on my phone (Unlimited 5G lol) and drew the Drona-lisa. (I'll ensure next journals are accompanied with either lapse or hackatime :)

![Notebook img 1](https://cdn.hackclub.com/01a216c0-afbf-7233-b5f9-3b2ea6814dc3/WhatsApp%20Image%202026-11-18%20at%2000.23.20.jpg)
![Notebook img 2](https://cdn.hackclub.com/01a216c0-9cc5-7506-8377-6b01821c5306/WhatsApp%20Image%202026-11-18%20at%2000.23.12.jpg)

**Total time spent : 3 hours**

---

# 11/23/2026: Modeled the frame in fusion 360

_Time spent: 1.5h_

Spent my time modelling the desired design into fusion 360, also made adequate cuts to reduce weight. I did half of this on november 18th but forgot to journal and then didn't get time due to olympiad and staff, so including that lapse in this. Also tried using the assembly feature for the first time but ended up using the normal design part because that's more precise for me right now. Also spent some time to understand Stress simulations to perform on the frame (tho i'll watch another video tailored for drones FEA specifically). Also i worked over 12 am so I'm journalling for 23rd november on 24th.

![Fusion Screenshot](https://cdn.hackclub.com/01a216c0-80a9-7dc4-82bf-8f863c98b4ee/Screenshot%202026-11-24%20004518.png)

**Total time spent : 1.5 hours**

---

# 11/25/2026: Stress tested the frame

_Time spent: 1.5h_


Modelled the mount for FC and sensors, followed a 40 minute video to setup a Linear Stress simulation for the frame and check it's strength. Will perform it again with actual data from in-hand parts and testings. 

![Simulation Screenshot](https://cdn.hackclub.com/01a216c0-53bc-79ee-8269-5ad07a24def5/Screenshot%202026-11-26%20010403.png)

**Total time spent : 1.5 hours**

---

# 11/27/2026: Made the BOM.csv and tested some parts with a lot of research

_Time spent: 3h_

Started the Day by researching upon the structure of drone flight mechanics, followed by a few articles on PID loops and took a look at some PID projects in action to grash an idea. Had an IMU6500 lying around so thought of testing it with an arduino but since it had unsoldered pins, it took me a lot of brain frying after writing the code (hackatime), then i ended late night by making the BOM.csv file with all the applicable sources and parts I could think of now.

![MPU6500 Test](https://cdn.hackclub.com/01a21981-94e5-7d76-8dec-67852cebe025/IMG20261127003638.jpg)

**Total time spent : 3 hours**

---

# 11/28/2026: JUST BOM on this half

_Time spent: 2h_

Really intended to start the software but had to fix the BOM with a few things I confirmed today and god i live somewhere without a single proper e-commerce site. I spent like 3 hours just in finding sources of parts that are ready to deliver and aren't charging more for delivery than the actual product. I'm gonna pick the coding in second half of the day but I've deflated the time already because even I can't believe how it took me so long and I wasn't even building something.

![BOM Tabs & Research](https://cdn.hackclub.com/01a21e59-c5bf-7937-bb6e-8759349174df/IMG20261128002019.jpg)

**Total time spent : 2 hours**