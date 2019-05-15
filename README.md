# Home-AssistantConfig
Apple Homekit With Konnected Alarm Panel and Home Assistant (Hass.io)

## Introduction
This is for users of Apple's Homekit, where homekit is primary and Home Assistantant provides additional support for unimplemented features in Homekit. 

## Features Better Supported By Home Assistant

 - Home Alarm Control For Konnected.io Alarm Panel
 - Automation of Alarm Via Presence Detection
 - Alarm triggering for home and away modes
 - Automatically switch arm_night to arm_home
 - Homekit doesn't show August's doorbell motion detection
 - Homekit doesn't automate based on Ecobee temperature
 - Homekit doesn't support appliances on too long in automation and can notify when things are in the undesired state for too long
 - Home Assistant can turn off the Ecobee if the Windows are open too long
 - Home Assistant can disarm the alarm based on who unlocked the August smartlock
 - Homekit can send a note when zones are entered or exited to to devices other than traveller's.
 
 ## Additional Feautures of Home Assistant

 - Connects to Google Assistant and Alexa (Not Used Here)
 - Connects to Asus Gateway
 - Sends stats to InfluxDB for better looking graphs

 ## Where does Homekit Fit In?
 Homekit already controls all accessories and is the primary system.  Home Assistant (Hass.io) covers the rest.
