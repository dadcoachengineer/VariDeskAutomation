# VariDeskAutomation
Automating my Varidesk via ESPHome and Home Assistant

Hey y'all!

I really love connecting all the things and most importantly automating the things across domains.

The two primary use cases for connecting my desk are:
* My Cisco DeskPro is my primary video device for my workday. Probably due to my posture differences, I am not quite framed up the same in video when sitting and standing. Now that Home Assistant knows my current desk position, it can make a xAPI call to my endpoint to change the video preset to the best zoom/pan setting.
* Using Influx and Grafana I have the ability to capture and visualize how much time I am standing vs. sitting. Also pulling in and correlating actual occupancy data based on people tracking in my DeskPro endpoint via API :)

I have the ability to control my two setpoints via a Home Assistant dashboard, buttons on my Stream Deck, or even via Alexa using a voice command.

![IMG_0382](https://github.com/dadcoachengineer/VariDeskAutomation/assets/6666082/9985dcd5-4fd6-4133-8f0c-4f18548edcd7 | width=100)
![08_47_43](https://github.com/dadcoachengineer/VariDeskAutomation/assets/6666082/6e796326-6c20-47f1-b567-593c5da986f6 | width=100)
![IMG_0380](https://github.com/dadcoachengineer/VariDeskAutomation/assets/6666082/b8c415d5-e544-4da0-b332-e2a719712933 | width=100)
