# Raspberry Pi 3B/3B+ 2FA

This MVP software provides a cheap, alternate second factor authentication (2FA) phone number on a Raspberry Pi 3B/3B+.  It solves the problem of companies requiring you to add a mobile phone number to your account and then using that phone number for targeting ads, leaking the phone number, etc. Companies keep doing this.  And I don’t see them stopping.

Hacker news discussion that inspired me:
https://news.ycombinator.com/item?id=32399949

## Demo
Below are a couple of screenshots.
1.  The software is running and the Pi is waiting for an SMS.  <br />
![Screenshot](waiting.png)  

2.  An SMS (or two) comes in it is displayed

![Screenshot](with-messages.png)

The Pi3B is headless and I'm accessing it over VNC.

I built this for myself and I've been really happy with it.  I want to know if enough people are interested for me to commercialize it.
To cover my costs, I will eventually charge a small monthly subscription fee or upcharge the twilio usage.  I am not looking to get rich here, just to provide a needed service.

The code is Python3 and Gtk
