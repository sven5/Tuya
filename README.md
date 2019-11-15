# Tuya
This is some information about my discoveries with Tuya smart home IoT cloud.
I bought a [smart home WIFI Thermostat "revolt"](https://www.pearl.de/a-NX4608-3103.shtml) from German reseller Pearl.
They're using their own App called [ELESION](https://www.elesion.com/). However, this is a branded Tuya App. 

You can use any Tuya App to connect this device so you're not tied to the Elesion App:
- [Tuya Smart](https://play.google.com/store/apps/details?id=com.tuya.smart)
- [Smart Life](https://play.google.com/store/apps/details?id=com.tuya.smartlife)

I decided to test some of these apps to reverse engineer their API.

With the help of the great tool [Packet Capture](https://play.google.com/store/apps/details?id=app.greyshirts.sslcapture) I was able to see the packets 
from the Tuya Smart app. I was able to connect to this API through postman.

Tuya also has a well documented [Open API](https://docs.tuya.com/en/iot/open-api/tuya-open-platform-access-guide/simple-grant) with samples. However, I wasn't able to get this working. I always got sign errors in the login process.
I think this is (only) useful for customers which operate their own cloud/App.

# Tuya Smart Life App
With the help of [cloudtuya project](https://github.com/unparagoned/cloudtuya) I was able to get the connection to the Smart Life API from postman working. 
You can find the postman environment file in my repo.
You need to install Smart Life App on your smartphone and register an account and then your device.


Good luck.
