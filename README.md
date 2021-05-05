This is an Arduino code for a Wemos D1 board (ESP8266 chip), coupled to 3 LM1881 video sync separators, and a MAX4545 video switch.
Compared to the popular RSSI-based systems, the advantages a video-based diversity are:
- No need to open the receivers to get the RSSI [Receiver Signal Strength indication] signals. You just have to plug in your different receivers, and they can be of different types.
- There is no need to calibrate the RSSi signals of the different receivers (this is often the tricky part).
- It is also frequent to get a strongly distorted image, while the RSSI is high.
- When the reception level is low (flying far for instance), some receivers have RSSI close to zero, although the image is still viewable. In that case an RSSI-based system is not really efficient.
