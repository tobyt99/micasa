---
title: "About Us"
# watermark text
watermark: "About"
# page header background image
page_header_image: "images/background/about.jpg"
# meta description
description : "Built on the experience of a home renovation MiCasa is on a mission to help home owners understand where their energy is going and ultimately leverage technology to reduce consumption."

layout : "about"
draft : false

############################## about ###############################
about:
  enable : true
  video_bg_image : "images/about/about-3.jpg"
  video_thumbnail : "images/about/about-4.jpg"
  video_link : "https://www.youtube.com/embed/nqye02H_H6I?autoplay=1"
  subtitle : "the background"
  title : "Where is all your energy going?"
  content : "MiCasa was set up by Toby following an extensive house renovation project in Spain that involved the installation of number of different 'systems' supplied by a variety of manufacturers.<p>The local weather provides over 300 days of sunshine so the obvious starting point was a solar pv solution to benefit from the free solar energy.  Initially the solar solution was planned to heat a water tank, that was quickly extended to feed an underfloor heating system that would provide year round heating.  Using a solaredge inverter the system was intially designed to return surplus electricity to the grid with the possibilty of adding local battery storage if the solar performance/energy consumption data showed that it would be economical.</p><p>Athough the sun would provide a pretty reliable source of energy a air source heat pump was also installed to provide additional heating options.</p><p>With summer temperatures climbing, each bedroom was also equipped with a mitsubishi condenser air conditioning unit along with a ceilig fan.</p><p>While all of these systems are 'smart' it became clear that the various manufacturers approach intelligence differently.  Although table stakes is providing an mobile 'app' the way that they handle data collection and storage varies - often using a 'cloud' - rendering the controls useless without internet connectivity.  Additionally, users should be deeply suspicious of free 'cloud' solutions, since they cost the supplier to maintain and if these costs are not passed on, it is probably that they will cease to be free (or exist) in the future.</p><p>Looking for a way to bring these disparate vendor solutions together using a local (on site) solution led to Home Assistant and the realisation that while visibility and control are important first steps, it is only via some form of orchestration that automation will be achievable.</p><hr><p> For example: An automation that runs during the day, when the outside temperture hits 40 degrees, turns on all of the A/C units to reduce the inside room temperatures to 25 degrees.  Requires knowledge of the outside temperature and subsequent knowledge of invividual room temperatures AND control of the individual units.  This cannot be achieved using the local in-room AC units alone.</p><hr><p>Since these first learnings, MiCasa has been set up to blend the needs of educated consumers, with the skills of the trades needed to install the sensing and automation layer and the software capabilities needed to design the automations and orcheestration.</p><p> Currently we are working on building the first step of measuring in home energy consumption in a cost effective and useful way.<h4>Moving forward</h4>We hope that MiCasa will become a vehicle to provide information and practicle advice to home owners looking to minimise energy consumption and optimise their use of energy using technology (automation and AI)."
  button:
    enable : true
    label : "Contact Us"
    link : "contact/"

############################### counter #############################
#funfacts:
  enable : true
  funfact_item:
  # funfact item loop
  - name : "Downloads per day"
    count : "8000"
    
  # funfact item loop
  - name : "Design awards"
    count : "200"

  # funfact item loop
  - name : "Totally satisfied users"
    count : "25000"

  # funfact item loop
  - name : "People behind this app"
    count : "80"


########################### Service ################################
#service:
  enable : true
  section : "service"
  # service item comes from "content/*/service.md" file
---