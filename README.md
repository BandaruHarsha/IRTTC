# IRTTC
Intelligent Real Time Temperature Control
Finally came the part of the day when we had to start working, we were probably the team with

least equipment: 1 Beagle Bone board,2 Raspberry Pi and 1 DHT11 temperature and humidity

sensor. With the limited components we decided to build a weather monitoring machine which

would post weather updates on a website. For this we connected the DHT11 to Pi and then I realised

that my Laptop had a non-functional RJ45 port and the other 2 didn’t even have one. We were left

with no option but connect Pi to the Wi-Fi network and work wirelessly on the LAN, little did we

know that the Wi-Fi router had blocked direct device to device connections which didn’t let us

connect to our Pi. By the time we realised this we had already wasted 2 precious hours sorting the

problems, Then Siddarth decided that he go home once as he has a monitor there. He then setup

weaved on the Pi so that we could work remotely on the Internet and not just on LAN, so at about

6PM we finally could start working on the project. We connected the components and started off

with a plan. The plan was to Install Apache and MySQL on the Pi. Then a simple python code will be

used to Pull the data from the sensors and add the data to a local database table. We then created a

website hosted on Pi which would pull data from the database, print it and also draw a graph. A cron

job was used to automate this process to repeat every few minutes. We were almost done with this

by mid night and still had a decent amount of time to work. After thinking a while we realised that

what we made is barely associated with IoT. I kept thinking about what we could do but then, the

components we had was the main limiting factor. I then came up with an Idea to Create and

Automated Air Conditioner (Now called “INTELLIGENT, REAL-TIME TEMPERATURE CONTROL”) It was

a very convincing project but we lacked the knowledge, resources and time to do it. I explained my

Idea to Harsha and he was very convinced with it and asked if it’s really possible. I spent rest of the

night and most of next morning searching for tools and libraries which could help me in my project

and came across OpenCV and Open Remote 2.0 which immensely boosted my confidence. We

decided to demo what we already made (Weather monitoring stations) and also give a presentation

on our future plans for the notion. We collected data across different websites and made a PPT


We were given many tips about how the project can be improved and we were suggested to work

on the security, so that we could prevent others from gaining access to the AirCon. He found it to be

the most practical project of the day and decided to hand over the first place to us. We were

extremely delighted and couldn’t believe it for a while. The situation was surreal and none of us

knew how and what to react. After the event while many were congratulating us, somewhere deep

inside I was not totally satisfied for 2 reason.

1) It was not so secure after all

2) We were unable to implement our idea

To solve the first one, I spent some time of the next 2 days thinking about a solution and came

across an article on Google about VO2 which has a very specific property of blocking our IR

radiations at high temperatures, the same phenomenon could be simulated by increasing the

voltage. For reference, by increasing the voltage form 1V to 3V, the effect caused would be similar to

that by increasing the temperature from 30* C to 77* C. This was a fairly simple thing to be

implemented using an Arduino which would act as a pre-processor for our signals.


Please refer to our Power Point presentation included along with this for more details on the project

and the use case scenarios. We’re looking forward to develop this product whenever possible and

would greatly appreciate help in any form.

https://docs.google.com/presentation/d/1eaygMxgkH53V87p9b3aI9Dwa4z3_eEB6Yzpj507jOpk/edit?usp=sharing
