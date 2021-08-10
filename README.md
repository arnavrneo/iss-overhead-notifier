# iss-overhead-notifier

This is a Python Code which notifies through email when the ISS SpaceStation is near you. And not only this, it only notifies you when it is dark outside so that you can see it clearly and not in the blinding sunlight! :)

## **What it uses?**

The different modules used here are:
- requests
- smtplib
- datetime
- time

## **What each of them does?**

Their functions here are:
- requests : It uses **requests** module to connect to the api endpoint : "http://api.open-notify.org/iss-now.json" .
- smtplib :  It uses the "smtplib" module for email transmission.
- datetime : As the name suggests, it is used for checking or more precisely comparing the time here in this program.
- time : This module is one of my favourite. This is a very simple module with very simple function : to stop the execution of a program for a certain amount of time. Yeah! sloooww ddooowwnn.

## **Well, what is an "api endpoint"?**

API stands for Application Interface Program. It acts as an interface between the user and the platform with which user is interacting.

## **And what is the use of this program?**

I loved space so much when I was a kid. I always loved looking at it. But never quite found the ISS.
This program can inform you when the ISS SpaceStation is near you in the sky so that you can be ready and may find that in the night sky.
