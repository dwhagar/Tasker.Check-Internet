Tasker.Check-Internet
======================

## Requirements
* Tasker (Android App)

## What does it DO?
I got really tired of having my cable Internet go down while I was asleep and waking up to find that I had no Internet access and people had been trying to get ahold of me via Instant Messenger or some such.  My phone, of course, has cellular data access but if Wifi is connected the phone will usually just sit there like anything that doesn't have the word "Smart" in the name with no Internet access.

In my case, my ISP was working fine but my router kept getting overloaded or overheated or just over-it and would stop tossing packets to/from a client on the WiFi connection.  So my designed this so it detects a problem, resets the WiFi of my device (and provides a nice notification with the time it happened) and tries again.  It does this 3 times.  If after 3 resets it still can't find a network connection then it turns WiFi off.

Once WiFi is turned off, it turns on a profile that will turn WiFi back on every so often to check if the problem has been solved.

Now, as a note, some modifications will have to be made for a specific setup.  This works in conjunction with my Auto Tethering setup so it is configured to shut off the auto-tether if it has to turn the WiFi off.  This will prevent the device from thinking it should activate the tether rather than try to use the questionable WiFi for access. 