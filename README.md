# Express AM8

Express AM8 is a Russian geostationary communications satellite.

<img src="/img/Express-AM8.jpg" alt="" width="304" height="178">

Its content broadcasting includes a number of controversial <a href="https://rumble.com/v241fl2-play-with-sat-stuff.html">Russian</a>, Syrian and Iranian (news) channels.<br>
Which are banned from broadcasting by EU distributors/providers due sanctions against Russia (everything) and Iran (Press TV).<br>
          
## Appendix

- [ 1.0 TV and Radio Channels ](https://github.com/happysat/Express-AM8/blob/main/README.md#tv-and-radio-channels)
- [ 1.1 Satellite Description ](https://github.com/happysat/Express-AM8/blob/main/README.md#satellite-description)
- [ 1.2 Dish and LNB ](https://github.com/happysat/Express-AM8/blob/main/README.md#dish-and-lnb)
- [ 1.3 Footprint ](https://github.com/happysat/Express-AM8/blob/main/README.md#footprint)
- [ 1.4 Dish Align to Express AM8 ](https://github.com/happysat/Express-AM8/blob/main/README.md#dish-align-to-express-am8)
- [ 1.5 Transponders and Frequencies ](https://github.com/happysat/Express-AM8/blob/main/README.md#telemetry-transponders-and-beacon-frequencies)
- [ 1.6 T2-MI Technology ](https://github.com/happysat/Express-AM8/blob/main/README.md#t2-mi-technology)
- [ 1.7 Satellite Receivers ](https://github.com/happysat/Express-AM8/blob/main/README.md#satellite-receivers)
- [ 1.8 DVB-S Card Software ](https://github.com/happysat/Express-AM8/blob/main/README.md#dvb-s-card-software)
- [ 1.9 Codecs, Players, Streaming Software ](https://github.com/happysat/Express-AM8/blob/main/README.md#codecs-players-streaming-software)
- [ 2.0 Electronic Program Guide XMLTV](https://github.com/happysat/Express-AM8/blob/main/README.md#electronic-program-guide-xmltv)
- [ 2.1 News and Updates ](https://github.com/happysat/Express-AM8/blob/main/README.md#news-and-updates)
- [ 2.2 Disclaimer ](https://github.com/happysat/Express-AM8/blob/main/README.md#disclaimer)

## TV and Radio Channels
The following TV and Radio channels are broadcasted in DVB-S(2) HD thru Express-AM8:

<img src="/img/RTDE2.jpg">

RT Int., RT Deutsch, RT France, RT Espanol, RT Arabic.<br>

<img src="/img/Rossia-24.jpg">

Russian: Rossiya 24, RTR Planeta, NTV Mir, Perivy Kanal, Dom Kino, Karusel, Radio Sputnik.<br>

<img src="/img/Belarus.jpg">

Belarus: Belarus 24 HD, Radio Belarus Int.<br>

<img src="/img/ALALAM.jpg">

Iran: Irib TV 1, Sahar TV Bosnian/Azari, Press TV HD, Hispan TV, iFilm, Al Alam TV.<br>

<img src="/img/Sport24.jpg">

Syria: Syria Sat Ch., Syria Sport 24, Syria 1, Syria News, Syria Drama, Sakaker Kids.<br>

<img src="/img/AlManar.jpg">

Lebanon: Etihad TV, Al Manar TV, Al Nour Radio.<br>

## Satellite Description

Operated and owned by RSCC (Russian Satellite Communications Company) from an orbital slot at 14?? Degrees West.<br>
<a href="https://www.n2yo.com/satellite/?s=40895#results">Express-AM8</a> will provide high quality fixed and mobile communication services.<br>

As well as broadcast services for digital television and radio, data transmission,
high-speed Internet access and secure government communications.<br>

<img src="/img/????8.jpg" alt="" width="304" height="178">

<a href="https://orbit.ing-now.com/satellite/40895/2015-048a/express-am8/">Express-AM8</a> (Norad:40895 2015-048A) was launched by a Proton M launcher into orbit on September 14, 2015.<br>
Thales Alenia Space, constructed Express-AM8 payload, and ISS Reshetnev constructed the satellite bus which was based on the Ekspress-1000NTB platform.<br>
The satellite has a mass of 2,100 kg (4,600 lb), provides 5.9 kilowatts to its payload, and a planned operational lifespan of 15 years.<br>

It should be taken into account that Express AM8 is not an ordinary DTH high power satellite like Astra and Hotbird!<br>

Express AM8 is subject to frequent frequency and signal strength changes.<br>
Transponder with low symbolrates are used, and many test's are performed varying from DVB-S(2) to T2-MI.<br>

Transponders/Channels details and info can change on a daily base.<br>
Which makes this a interesting exotic "DX" satellite with trans-atlantic coverage and custom cross-strap footprint configurations.<br>

The satellite transponders are also regularly hacked or disrupted by jamming signals.<br>
This is no unique case and it did happen at Eutelsat Hotbird Position (and a number of other satellites) also.<br>

## Dish and LNB

For reception of Express-AM8 you need a dish in size >75 - 85 cm.<br>
A size between 80 - 1.20 cm is recommended.<br>

Dishes In use on my setup are:<br>
          <br>
          <img src="img/Triax.jpg" alt="" width="267" height="187">
          &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; <img
            src="img/90cm.jpg" alt="" width="173" height="196"><br>

89CM Triax And 90CM Noname Dish.
          
Any Ku-band Satellite TV (DRO/PLL-based) LNB can be used for Express AM8.<br>
I have various results with DRO and PLL based ones but shows clearly a huge increase of frequency stability YMMV.<br>

Regular Ku-band Satellite TV LNB (DRO) suffer from drift in frequency making it more difficult to keep a stable reception for the low symbolrate signals.<br>
Because of outside conditions (temperature changes, sun, clouds, wind ect).<br>

In use on my setup are:<br>

<img src="img/ultra.jpg" alt="" width="161" height="94"><br>

Invertro Ultra Black LNB (DRO Old model with longer neck).<br>

<img src="img/twin.jpg" alt="" width="185" height="185"><br>

Inverto Twin (PLL) LNB.<br>

## Footprint

Express AM8 carries 12 Ku-band transponders Linear 12x36 MHz; 4x54 MHz (150W) with three footprints:

<img src="img/express-am8-ku-band-fix1.jpg" alt="" width="567" height="405">

Europe/Middle-East Fixed 1

<img src="img/express-am8-ku-band-fix2.jpg" alt="" width="564" height="533">

Africa/Middle-East Fixed 2.<br>
And Latin America/East coast of North America Fixed 3.<br>

24 C-band transponders Circular 24x40 MHz (100W) with coverage of two footprints:

Europe, Africa and the Middle-East and Latin America and the East coast of North America.<br>
And the payload has two L-band transponders.<br>

## Dish align to Express-AM8

There are several ways to find Express-AM8 in the sky:

<a href="https://www.dishpointer.com" target="_blank">Dishpointer has a good website and Android app.</a>

Enter City location and Select Express AM8 to see all details.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=MNqsqvnrJbI
" target="_blank"><img src="http://img.youtube.com/vi/MNqsqvnrJbI/0.jpg" 
alt="LNB Skew" width="240" height="180" border="10" /></a>

Take into account the skew settings of the LNB!<br>
Dish Pointer website list the skew values for Express AM8 below the image of your selected location.<br>

And try to tune for the strongest transponder <a href="https://en.kingofsat.net/tp.php?tp=12861" target="_blank">11623 V DVB-S2 8PSK 7347 3/4.</a><br>

If not working try Telstar on 15 West, strong Transponder with 1 FTA channel on <a href="https://en.kingofsat.net/tp.php?tp=1086" target="_blank">11377 V DVB-S2 QPSK 8750 3/5.</a><br>

<img src="img/MTN_Info.jpg" alt="" width="542" height="299"><br>

When it works and fine tuned for enough signal move the dish to 14 west, it should be a small adjustment.<br>


Or the program <a href="http://www.al-soft.com/saa/satinfo.shtml" target="_blank">Satellite Antenna Alignment 4.0</a><br>
For Dish alignment and many more options.<br>

Examples of Video's  Express AM8 Reception:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=wlJQ2GOm05I
" target="_blank"><img src="http://img.youtube.com/vi/wlJQ2GOm05I/0.jpg" 
alt="Reception with a dishindoor." width="240" height="180" border="10" /></a>
&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; 
<a href="http://www.youtube.com/watch?feature=player_embedded&v=wH6MfeTWfuo
" target="_blank"><img src="http://img.youtube.com/vi/wH6MfeTWfuo/0.jpg" 
alt="RT" width="240" height="180" border="10" /></a>


## Telemetry, Transponders and Beacon Frequencies.

<a href="http://www.romantis.com/wp-content/uploads/2017/01/Romantis_AM8.pdf" target="_blank"><img src="img/freq-plan.jpg" alt="" width="741" height="645" border="0"></a>

Telemetry and Beacon Frequencies:<br>

<img src="img/telemetry.jpg" alt="" width="525" height="292"><br>

11199.50 GHz R (Global).<br>
<br>
<br>
[Up2date Express AM8 Transponder.ini file](https://github.com/happysat/Express-AM8/blob/main/3460.ini)<br>
<br>
<br>
[![Express AM8 Transponder Index](https://www.lyngsat.com/images/lyngsat_210x48.gif)](https://www.lyngsat.com/Express-AM8.html)
<br>
Lyngsat Transponder Index<br>
<br>
[![Express AM8 Transponder Index](https://en.kingofsat.net/kingofsat.gif)](https://en.kingofsat.net/pos-14W.php)
<br>
KingOfSat Transponder Index<br>

## T2-MI Technology

T2-MI (T2 Modulator Interface) is a method of encapsulating a satellite signal into an MPEG TS transport stream.<br>
In simple terms, using the T2Mi interface, channel packages in the DVB-T2 standard are transmitted from the satellite to base
earth stations for further distribution to T2 towers, <br>
which then transmit terrestrial digital television for TVs or DVB-T2 receivers.<br>&nbsp;<br>
That is, the channel packages in T2MI were not originally intended to be received by domestic satellite receivers. <br>
But with the development of processors for satellite receivers capable of processing them, it became possible to receive these TV channels at home on a regular home satellite receiver.<br>

Express AM8 did have a few T2-MI transponders.<br>

<img src="img/T2-MI.jpg" alt="" width="508" height="306"><br>

Broadcasting channels to DVB-T2 Multiplexes in Ukraine.

Update T2-MI Multistreams with the Russian package appear to have completely migrated to the Express AM6 53?? East!<br>

## Satellite Receivers

Well, there is plenty of choice in this area, it depends a bit on what you want to see.<br>

<img src="img/1-0-1-1-14-1-D842-D76-0-0-0.jpg" alt="" width="640" height="360"><br>

A lot is already possible to see with a normal HD receiver and it does not have to be new state of the art.<br>
Ci, softcam's or smart cards are not necessary because everything is broadcasting Free To Air.<br>

Off course for the T2-MI Multiplexes to show or even more, one need a new generation receiver or even better a <a href="https://www.tbsdtv.com/">TBS DVB-S Card</a> is recommended.<br>

<a href="https://www.tbsdtv.com/products" target="_blank"><img src="img/tbs5530_1.jpg" alt="" width="350" height="300" border="0"></a>

Capable of receiving digital TV channels of multiple standards: DVB-S2X/S2/S/DVB-T2/C2/T/C(J.83 A/B/C)/ISDB-T/C/ATSC1.0<br> 
Also supporting CCM, VCM and Multi Input Streams.<br>

Advantages are analyzing streams, faster blindscanning, wide software choice (viewers/headends), multipule platform support Linux/Windwows/ARM, media features Kodi, adding second tuners in engima2 based recievers.<br>

Receivers in use on my setup are:<br>

Dreambox 800se <a href="https://github.com/jack2015/openpli-dreambox-oe-core" target="_blank">OpenPLI 12.2</a><br>
VuSolo2 <a href="http://images.mynonpublic.com/openatv/7.1/index.php?open=vusolo" target="_blank">Open-ATV</a><br>
<a href="https://www.tbsiptv.com/tbs5530-multi-standard-universal-tv-tuner-usb-card" target="_blank">TBS5530</a>.<br>

## DVB-S Card Software

There is a lot of (free) software choice for the DVB-S cards.<br>
Varying from TV application viewers till stream analyzers.<br>

<a href="https://www.altx.ro/projects/altdvb/" target="_blank">AltDVB</a>
is a free software for watching digital TV on your windows PC using a dedicated DVB hardware device.<br>
It does support DVB-S/S2 and T2-MI standards,<br>
Picture-in-Picture (PIP), LAN Streaming, and many other options and features.<br>

<img src="img/AltDVB.jpg" alt="" width="638" height="405"><br>

<a href="http://www.smartdvb.net/tempsite/index.html" target="_blank">SmartDVB</a> 
is a free digital-tv watch application for satellite TV cards. <br>
It supports DVB-S/S2 and T2-MI standards.<br>
XMLTV import option for EPG, streaming, PIP, and other options and features.<br>

<img src="img/smartdvb.jpg" alt="" width="635" height="438"><br>

<a href="https://sourceforge.net/projects/crazyscan/" target="_blank">Crazyscan</a>, <a href="http://ebspro.net/overview/" target="_blank">EBSPro</a> and <a
href="https://www.satellitescommunity.de/forum/index.php?thread/2005-iqmonitor-only-files/&amp;postID=45835#post45835" target="_blank">IQ Monitor</a> - Free analyzer tools for satellite DVB-tuners to show details and info about stream info, <br>
blind scanning, signalInfo, constellations and many more options.<br>

<img src="img/Bild.jpg" alt="" width="493" height="579"><br>

## Codecs, Players, Streaming Software

Software DVB-S Demodulator

<img src="img/Etihad.jpg" alt="" width="525" height="292"><br>

The demodulator works with RTL-SDR, Airspy, HackRF, SDRplay and PlutoSDR.<br>
It can demodulate DVB-S and S2 signals with very low symbolrate, but not above 2000 ks.<br>

[More about Software DVB-S Demodulator Overhere.](https://github.com/happysat/Es-Hail-2-Oscar-100#software-dvb-s-demodulator)<br>

[And setup SDR on LNB Ouput.](https://github.com/happysat/Es-Hail-2-Oscar-100#bias-tee)<br>

<img src="img/demoneditor.jpg" alt="" width="611" height="348"><br>
<a href="https://github.com/DYefremov/DemonEditor" target="_blank">DemonEditor</a><br>

Enigma2 channel and satellite list editor for Windows and Linux.<br>

Main features of the program:<br>

Editing bouquets, channels, satellites, Import/Backup function, Support of picons.<br>
Export of bouquets with IPTV services in m3u.<br>
Assignment of EPG from DVB or XML for IPTV services, Playback of IPTV or other streams.<br>

<img src="img/mpv.jpg" alt="" width="641" height="384"><br>
<a href="https://mpv.io/">Mpv</a>
Free, open source, and cross-platform media player.<br>

<a href="https://github.com/Nevcairiel/LAVFilters/releases">LAV Filters</a> are a set of DirectShow filters based on the libavformat and libavcodec libraries from the ffmpeg project.<br>

<img src="img/LAV.jpg" alt="" width="645" height="575"><br>

Which will allow you to play virtually any format in a DirectShow player.<br>

<a href="http://madvr.com/">madVR</a> is a DirectShow video renderer used by hundreds of thousands of home theater enthusiasts around the world.<br>
Designed as a no-compromise approach, madVR delivers the ultimate video playback quality that no enthusiast should be without.<br>

## Electronic Program Guide XMLTV

TV Channels on Express AM8 are not broadcasting Electronic Program Guide Data.<br>
However it is possible to import EPG data yourself in XMLTV format.<br>

The enigma2 based receivers are having the rytec plugin in their image feed for importing epg data.<br>

DVB-S card software including Smartdvb can import XMLTV so that an epg guide can be seen for the TV channels of Express AM8.<br>

<img src="img/epg3.jpg" alt="" width="694" height="498"><br>

Also in the seperate Guides

<img src="img/epg.jpg" alt="" width="694" height="498"><br>

<img src="img/epg2.jpg" alt="" width="694" height="498"><br>


Download (right click save as) XMLTV EPG for:<br>

[RT Germany](https://happysat.nl/xmltv/rt_de.xml)<br>

[RT Int, Rossia-24, NTV MIR, 1TVRUS Europe, Dom Kino, RTR-Planeta Europa and Belarus24 HD.](https://happysat.nl/xmltv/rt.xml)<br>

Updated every 7 Days.<br>

Goto Tool/Settings menu for EPG import.<br>

<img src="img/xmltv.jpg" alt="" width="694" height="498"><br>

## News and Updates

14 March<br>

RT Transponder back on 11638 V 1/2 16574 RT Esp, RT Int, RT De and RT France<br>

<img src="img/RTDe14.03.2023.jpg" alt="" width="525" height="292"><br>

13 March<br>

RT/1TVRus Transponder no signal.<br>

NTV Mir, RT Eng, RT Fr, RT Esp, RT Arab, RT De, 1TVRUS Europe, RTR-Planeta Europe, Rossia 24, Belarus-24 HD and Radio Belarus,
appeared on Express AM 6 53 East TP: 11481 H 27500 1/2 DVB-S2.<br>

Dom Kino, Karusel Int appeared on Express AM 6 12532 H 27500 1/2 DVB-S2.<br>

12 March<br>

RT Transponder turned off, Jamming continues on other channels.<br> 

11 March<br>

Pretty much all Transponders are affected by jamming except the Syrian mux and Al Manar.<br> 

<img src="img/1TVRus_11.03.jpg" alt="" width="525" height="292"><br>

1TVRus is suffering from interuption hacks.<br> 

10 March<br>

Signal Jamming every 30 seconds started again following TPs are affected: 11.653V (1TVRUS), 11.110H (NTVmir) und 11.025H (Rossiya24, RTR Planeta), 11638H (Belarus24).<br>

<img src="img/IMG-20230310-091851.jpg" alt="" width="525" height="292"><br>

1TVRus was hacked in the early morning 2x5 minute broadcasting reporting the "actual count" victims since the war started.<br> 

6 March<br>

Transponder: 11671 H 16600 DVB-S2/8PSK 3/5 IRIB SID Changed.<br>

15 Febuary<br>

The European Union may ban RT Arabic on its territory as part of new anti-Russian sanctions.<br>

On Hotbird the channel is allready showing black screen, transmissions will continu offcourse on Express AM8.<br>
RT Arabic is named as Synterra on the eu beam (fixed 1) and also available on the fixed 2 beam in the middle east.<br>

9 Febuary<br>

11671 H Radio 01 / 07 World Service added.

6 Febuary<br>

<a href="https://orbit.ing-now.com/satellite/40895/2015-048a/express-am8/">Altitude statistics</a> from Express AM8 showing a significant difference in elevation.<br>

<img src="/img/stats.jpg" alt="" width="1100" height="400">

Which coincides with the February 6th earthquake event, some experts telling planets in the solar system were in constellations which maybe did affected geostationary satellites..?<br>

3 Febuary<br>

News channel Russia Today Deutschland (RT-DE), already subject to sanctions within the European Union since last year has ceased all journalistic activities of RT Germany in the country.<br>

Last month, RT did the same in France.<br>

It does not mean that there is no more RT programming aimed at France or Germany.<br>
RT now broadcasts outside the EU and continues to transmit at 14 degrees west.<br>

1 Febuary<br>

<img src="img/Dom_Kino.jpg" alt="" width="525" height="292"><br>

11623 1TVRus replaced by Dom Kino.<br>

<img src="img/1TV_Rus.jpg" alt="" width="525" height="292"><br>

11653 Pobeda replaced by 1TVRus.<br>

30 January<br>

T2-MI Multistreams with the Russian package appear to have completely migrated to the Express AM6 53?? East.<br>
The channels in T2-MI were originally intended for DVB-T2 terrestrial broadcasting in Novorossia.<br>

27 January<br>

A number of Transponders do indeed have more transmission power.<br>

<img src="img/RT-Arab.jpg" alt="" width="525" height="292"><br>

11541 H RT Arabic, Fix Ku2, 21 % / 3,40 dB.<br>

<img src="img/Rossiya24.jpg" alt="" width="525" height="292"><br>

The jamming continues, clearly visible on transponder B3 11025 H Rossiya 24 and RTR Planeta.<br>

26 January<br>

<img src="img/RT_Int.jpg" alt="" width="542" height="299"><br>

Jamming signal on RT and almost all other Russian transponders.<br>
Some Transponders are showing increased signals levels then usual.<br>

T2-MI Transponder on 11647 Off.

25 January<br>

TV broadcasts in Russia???s southwest were briefly disrupted by an address from the Ukrainian president, disruption affected satellite broadcasts, according to the press service of the regional government. <br>
Operators had to re-direct the signal from a backup satellite.<br>

<a href="https://thepressunited.com/updates/zelensky-appears-on-russian-tv/" target="_blank">Zelensky appears on Russian TV</a>.<br>

24 January<br>

Pobeda back as "POBEDA int" on 11653 V 4880 2/3.<br>

<img src="img/POBEDA.jpg" alt="" width="518" height="274"><br>

23 January<br>

IRIB - JAMEJAM1 HD, SAHAR BALKAN/AZARI, PRESS TV HD, HISPAN TV, iFILM ENGLISH, ALALAM HD - 11670 H 16596.

21 January<br>

PRESS TV HD - 11498 H Gone.

20 January<br>

Syria, Syria Sport 24, Syria CH1, Syria News, Drama 24, Sakaker - 11690 H 12110.

<img src="img/Syrian.jpg" alt="" width="515" height="356"><br>

PRESS TV HD - 11498 H 6938.<br>

<img src="img/PRESSTV.jpg" alt="" width="511" height="288"><br>

18 January<br>

1TVRUS are now broadcasting in 2/3. <br>
Pobeda is switched off.<br>
Many interruptions on RT Transponder. <br>

<img src="img/rtde.jpg" alt="" width="525" height="292"><br>

<img src="img/jam.jpg" alt="" width="500" height="31"><br>

17 January<br>

Syrian Transponder clear 11600 V.<br>

5 January 2023<br>

Express AM8 transponder 11647V was hacked today at 6:30 PM by Ukrainian Ministry of Strategic Communication.<br>
A New Year's address by Ukrainian President V. Selensky was shortly broadcast in Ukrainian on all program positions of the T2-MI transponder.<br>

<img src="img/1_0_1_B_5_0_D84AD7F_0_0_0_202301.jpg" alt="" width="516" height="289"><br>

21 July 2022<br>
<a href="https://eng.rscc.ru/press/satellite-being-born-siberia-rscc-signs-contract-r/">Express AM4 launch is planned in 2026.</a><br>

It will occupy the slot at 11??W on geostationary orbit and will also reserve 14??W.<br>
The satellite will be delivered in orbit by Khrunichev Space Center using the Proton launch vehicle.<br>

Equipped with a 63 active transponders at a payload power of 14 kW for its planned 15-year service life in orbit.<br> 
Its ten antennas will provide high performance coverage over the Russian Federation and the CIS countries and its steerable antennas can be used to provide communication to any point within the satellite's visibility.<br>

## Disclaimer

This website is for educational purpose only.<br>
The European Union labels alternative news sources on this satellite as propaganda.<br>

Residents of the European Union are allowed to view this content, but may not live distribute it.<br>
This satellite and it contents broadcasting channels are controlled by RSCC (Russian Satellite Communications Company).

## Author

- [Express AM8 by Happysat](https://github.com/happysat/Express-AM8/)
