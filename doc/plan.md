# Plans and ideas

## Concepts

* Try to address the use cases of existing users
* Outreach to new areas with low income over the digital divide

## Software

### User features

* ability to bookmark subsections of a podcast
* share deep links or media slices to subsections
* recommendation engine
* play 2 separate shows on the 2 stereo channels

### WAN

* WebTorrent
* bootstrap: supernodes

### Offline

* sync electronic program guide schedule
* prefetch as podcast: subscribe to concrete shows, general show tags, keywords in description
* after transcript is available (or generated), fetch other recent podcasts that may be of interest for later listening as well
* decompose podcast to subsections: add comments to a given point in time of a podcast that may sync to a forum or mailing list thread in batches

### Bandwidth saving

* also reduces power consumption
* when available, stream the source of tracked modules, not their rendered forms
* decompose live shows as tracked modules: prefetch static assets in high quality (musical interludes, effects, questions by host), overlay speech in realtime with lower bandwidth codec

### Business model

* resale equipment with a markup: FM transmitter for home or automotive use, speakers, headphones, cables, powerbanks, phones, modems, USB chargers, loans
* sponsorship subscription that provides a small cellular data plan (while subscribed) and hardware (from loan)

## Hardware

### Car

* phone/mifi (SBC, storage, Bluetooth, wifi, 4G modem)
* 3.5mm jack line cable
* FM transmitter
* 4G subscription
* USB car cigarette lighter charger

### Kitchen

* phone (SBC, storage, Bluetooth, wifi)
* 3.5mm jack line cable
* FM transmitter
* speaker (or built-in)
* Bluetooth keyboard (or built-in touchscreen)

### Nomadic

* phone/mifi (SBC, storage, Bluetooth, wifi, 4G modem)
* 4G subscription
* 3.5mm jack line cable
* FM transmitter
* speaker (or built-in)
* Bluetooth keyboard (or built-in touchscreen)
* powerbank (battery, LED torch, solar panel, USB charger)
* USB-OTG cable

### Digital divide

Possibly shared within family:

* phone or MP3 player (possibly with built-in speaker box)
* 3.5mm jack line cable
* 3.5mm left/right stereo to mono splitter cable: so they can listen to 2 different shows at the same time
* wired speaker, headphones
* USB SD card reader, USB cable, USB-OTG cable

Personal:

* SD card or USB thumb flash drive (perhaps USB-OTG)
* possibly shared by separate, encrypted folders

Sync:

* periodically drive into a computer with Internet access (community center, office, school)
* let the website or portable executable app sync new content automatically based on personal profile

### Development components

* https://en.wikipedia.org/wiki/Raspberry_Pi_Zero
* https://en.wikipedia.org/wiki/ESP8266
* https://en.wikipedia.org/wiki/OpenWrt

### Existing systems

Most components and full systems already exist on the market with wifi based internet radio streaming built in. Such could also be resold as a first step before creating more elaborate custom solutions.

* https://aqua.hu/radiok-tuner/nedis-rdin2000wt-internetes-radio-feher-barna-t1071926
* https://electronic-star.hu/HiFi-es-TV/Radiok/Internet-radiok/TuneUp-internet-radio-5-W-WLAN-USB-HCC-kijelzo-vonalkimenet-sotetszurke-Sotetszurke.html
* https://euronics.hu/okostelefonok/blaupunkt-sm-05-4g-mobiltelefon-fekete-yettel-csomag-p268085

## References

* https://en.wikipedia.org/wiki/Peercasting
* https://en.wikipedia.org/wiki/Crowdcasting
* https://en.wikipedia.org/wiki/Delay_tolerant_networking
