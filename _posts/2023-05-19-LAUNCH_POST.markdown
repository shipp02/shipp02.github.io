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

# PTR's first flight

After six years of dedicated effort from the UCI Rocket Project team, we launched PTR, our Preliminary Test Rocket. PTR is UCI's first liquid-fuel bi-propellant rocket and huge milestone for our project. We conducted a successful hotfire of the rocket engine in January 2022. In 3 months, we integrated our systems and launched the rocket. It reached an altitude of 9,300 ft.

# My role in the avionics.

We developed the Engine Control Unit (ECU), and the Avionics Flight System (AFS). The AFS included a radio system for live telemetry. An EasyMiniv3 system from Altus Metrum was used to deploy the parachutes.

I have involved myself with PTR for the last year. I developed the software for the ECU and a data visualization system using Grafana. We had a live P&ID diagram and various gauges and line charts to help visualize the status of the rocket. The ECU is an embedded system using a Teensy 4.1 MCU. The ECU has a Ethernet interface and accepts commands over UDP. PlatformIO made it easy to version control and share the embedded software. 

I optimized the networking system to reduce the latency by 3x earlier in the year and alleviated a major concern. I analyzed the round trip times for various combinations of commands with WireShark. The solution was to reduce the number of Round Trips for system updates to allow faster control. This fix also enabled commands to be batched.

I participated in cold flow testing. It was the first time my software touched the hands of real users. This taught me lessons in stability and software evolution. Cold flow testing involved filling our tanks with liquid nitrogen (LN2). We then pressurized the system and let the gases exit from the injector. This simulates the stresses experienced by the system during hot fires.

The cold flows led to a lot of late nights due to issues caused by both avionics and propulsion. These debugging sessions were a bit tense as all other members waited for you to figure out why the system had fallen over. They also conveyed the level of testing required before deploying embedded systems on both the software and hardware side. 

The procedure documents we used are also a source of learning. I seldom had such well-documented instructions. These helped avoid mistakes in both the order of steps and in forgetting steps.

A last-minute swap of our GSE also improved reliability. We had been frustrated by LabView over the year. Critical errors during late rounds of testing drove me to develop some software for our ECU's that enabled them to function as a stop-gap GSE. We found the perils of manually setting the MAC address during a cold flow. We connected both ECU and GSE to the same network which had the same MAC address. This led to a hours of debugging frenzy solved by a single observation. This experience taught me that understanding the entire system is crucial when developing embedded systems.

During all this time, the team demonstrated a lot of humility and sympathy for each other. The cold flows never ended in arguments or people blaming each other for faster their time. This made the whole experience delightful.
# Thank you, team.

I am grateful to our leads and management for their efforts in making the project successful. Specifically, Nitish Chennoju (Chief Engineer) for helping me grow as an engineer and an effective team member. He made me aware of shortcomings in my approach to engineering. This reality check set me on a path to progress. This has benefited me in several personal projects. It has helped me overcome obstacles that might have made me quit.

![Full Team Photo](/assets/img/projects/LaunchTeamPicFinal.jpg)

[Video of the launch](https://youtu.be/xHpJZvFMLZk?si=-V8nQ_Z_soPC7IaZ)

Thank you, to the entire team of UCIRP Liquids for your awesome attitude and immense support!

#REAPER