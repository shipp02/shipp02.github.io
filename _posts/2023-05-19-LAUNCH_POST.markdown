---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_Examples
title: We launched a rocket

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
author: Aashay Shah
# multiple category is not supported
category: ucirp
# multiple tag entries are possible
tags: [ucirp, celebrate, announcement]
# thumbnail image for post
img: "/assets/img/projects/Engine2.jpg"
# disable comments on this page
#comments_disable: true

# publish date
# date: 2023-04-30
# published: false

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-02-10 08:11:06 +0900
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
# published: false
---

After 6 years of hardwork from the UCI Rocket Project team and a year of my own
involvement in the project, we launched PTR our Prelimiary Test Rocket. This was quite the milestone 
since it is UCI's first liquid fuel bi-propellant rocket. We got to a maximum altitude of
9300ft. After our successful hotfire of the rocket engine in flight configuration in January
2023, we pulled the system together in just 3 months.

The Avionics Systems on this rocket were the Engine Controller, the Avionics Flight System
and a transmitter module for live telemetry. These were developed by us in-house.
The parachutes deployment system was a commercial EasyMiniv3 system from Altus Metrum.

My primary role was the developmet of the software for the control of the engine. This included the
grafana data analysis system that I deployed. We also has a P&ID control diagram to help
visualize the status of the rocket. I also developed the software for the Engine Control Unit (ECU)
which involved embedded programming on a teensy4.1 board. The ECU accepted commands over a IP based 
network which made it very convinient during development. I also helped make the builds of the 
software more robust through the use of platformio which helped people collborate with each other.
s
With that technical stuff out of the way, let me express my gratitude to our leads and management for their efforts to the project. I would like to acknowledge our chief engineer in particular for driving me to grow as an engineer and a diplomatic team member. I am aware of several shortcomings in the way I approach my work. He gave me a reality check and set me on the path to progress because I had put off working on issues. This has benefited me in a few personal projects and allowed me to push through obstacles that might have otherwise caused me to quit.

![Full Team Photo](/assets/img/projects/LaunchTeamPicFinal.jpg)

Thank you, to the entire team of UCIRP Liquids for your hardwork and support!

#REAPER