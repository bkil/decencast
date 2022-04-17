# Plans and ideas

## Concepts

* Try to address the use cases of existing users
* Outreach to new areas with low income to counter the digital divide

## Software

### User features

* ability to bookmark subsections of a podcast
* share deep links or media slices to subsections
* recommendation engine
* play 2 separate shows on the 2 stereo channels or on multiple Bluetooth devices or via FM transmitters
* adaptive autoplay and shuffle when in offline podcast mode to allow for less interaction if batch or background listening (from the neighboring room or at the workbench)
* convert to plain m3u stream within the LAN for legacy webradio devices
* LAN multicast
* temporarily switch from an unavailable live stream to previous (unheard) episodes of the same show
* notification for calendar reminders

### Sonification

* interface fully accessible to the visual impaired
* text to speech
* voice command or up to 5 fixed buttons
* adaptive autoconnection with exponential backoff and user-adaptive fallback strategies
* automatic periodic status report: battery, time (reminders), listener comments, connectivity, used bandwidth (if metered), buffer, new shows or episodes

- https://www.cs.umd.edu/~dchou/papers/818w_paper.pdf
> Voice Recognition on Simple Microcontrollers

- https://fileadmin.cs.lth.se/ai/Proceedings/etfa2005/html/articles/CF-000561.pdf
> Microcontroller Implementation of a Voice Command Recognition System for Human-Machine Interface in Embedded Systems

### WAN

* WebTorrent
* bootstrap: supernodes
* cluster peers based on latency (by country and ISP)
* https://en.wikipedia.org/wiki/Peercasting
* https://github.com/pldubouilh/live-torrent
* https://github.com/Novage/p2p-media-loader
* https://github.com/netCommonsEU/PeerStreamer-ng
* https://github.com/cdnbye/hlsjs-p2p-engine
* https://en.wikipedia.org/wiki/PeerTube
* https://datatracker.ietf.org/wg/ppsp/charter/

### Offline

* sync electronic program guide schedule
* prefetch as podcast: subscribe to concrete shows, general show tags, keywords in description
* after transcript is available (or generated), fetch other recent podcasts that may be of interest for later listening as well
* decompose podcast to subsections: add comments to a given point in time of a podcast that may sync to a forum or mailing list thread in batches
* https://en.wikipedia.org/wiki/Delay_tolerant_networking

### Bandwidth saving

* also reduces power consumption
* when available, stream the source of tracked modules, not their rendered forms
* decompose live shows as tracked modules: prefetch static assets in high quality (musical interludes, effects, questions by host), overlay speech in realtime with lower bandwidth codec
* option to only load and concatenate talk sections of composite shows and skip higher quality musical interludes
* MPEG-DASH or HLS-like slicing
* transcode streams and podcasts to various low bandwidth codecs and ensure better seeding and prefetching of lowest variants
* https://en.wikipedia.org/wiki/Codec_2

### Business model

* resale equipment with a markup: FM transmitter for home or automotive use, speakers, headphones, cables, powerbanks, phones, modems, USB chargers, loans
* sponsorship subscription that provides a small cellular data plan (while subscribed) and hardware (from loan)
* possibly offer a type of 2-for-1 subscription with which one may sponsor the hardware of one in need as well as their own
* https://en.wikipedia.org/wiki/Crowdcasting

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
* wired speaker, headphones
* 3.5mm left/right stereo to mono splitter cable: so they can listen to 2 different shows at the same time
* possibly support for multiple Bluetooth devices or FM transmitters so they could listen to different shows in neighboring rooms
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
* https://barix.com/exstreamer-100-105-110-120
* https://aqua.hu/fm-transmitter/car-mp3-hf-mp3kw853-fm-transzmitter-t1064352

### Existing systems

Most components and full systems already exist on the market with wifi based internet radio streaming built in. Such could also be resold as a first step before creating more elaborate custom solutions.

* https://aqua.hu/radiok-tuner/nedis-rdin2000wt-internetes-radio-feher-barna-t1071926
* https://electronic-star.hu/HiFi-es-TV/Radiok/Internet-radiok/TuneUp-internet-radio-5-W-WLAN-USB-HCC-kijelzo-vonalkimenet-sotetszurke-Sotetszurke.html
* https://euronics.hu/okostelefonok/blaupunkt-sm-05-4g-mobiltelefon-fekete-yettel-csomag-p268085

## References
