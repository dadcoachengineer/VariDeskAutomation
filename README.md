# VariDeskAutomation
Automating my Varidesk via ESPHome and Home Assistant

Hey y'all!

I really love connecting all the things and most importantly automating the things across domains.

The two primary use cases for connecting my desk are:
* My Cisco DeskPro is my primary video device for my workday. Probably due to my posture differences, I am not quite framed up the same in video when sitting and standing. Now that Home Assistant knows my current desk position, it can make a xAPI call to my endpoint to change the video preset to the best zoom/pan setting.
* Using Influx and Grafana I have the ability to capture and visualize how much time I am standing vs. sitting. Also pulling in and correlating actual occupancy data based on people tracking in my DeskPro endpoint via API :)

I have the ability to control my two setpoints via a Home Assistant dashboard, buttons on my Stream Deck, or even via Alexa using a voice command.

A huge thanks to all of the contributors in this HA Community thread:
https://community.home-assistant.io/t/desky-standing-desk-esphome-works-with-desky-uplift-jiecang-assmann-others/383790/18

You can check out my ESPHome config here: 
https://github.com/dadcoachengineer/VariDeskAutomation/blob/main/jason-desk.yaml

Here are the two pieces of hardware I used. Just a generic D1mini and a RJ45 to screw terminal adapter.
https://www.amazon.com/gp/product/B07LCJ4V5C/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1
https://www.amazon.com/gp/product/B08MLFWMF8/ref=ppx_yo_dt_b_asin_title_o05_s01?ie=UTF8&psc=1

Still to do:
* Model and print a slip on cover for the hardware
* Complete a few automations

<img src="https://github.com/dadcoachengineer/VariDeskAutomation/assets/6666082/9985dcd5-4fd6-4133-8f0c-4f18548edcd7" width="400">
<img src="https://github.com/dadcoachengineer/VariDeskAutomation/assets/6666082/6e796326-6c20-47f1-b567-593c5da986f6" width="400">
<img src="https://github.com/dadcoachengineer/VariDeskAutomation/assets/6666082/b8c415d5-e544-4da0-b332-e2a719712933" width="400">
<img src="https://github.com/dadcoachengineer/VariDeskAutomation/assets/6666082/3b30a94b-630a-4583-a098-e59e9fe9af7f" width="400">
