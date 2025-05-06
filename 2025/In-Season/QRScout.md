<div>
<div align="center">
<h1><span style="color:#bf5700">Scouting Success with QRScout
</span></h1>
</div>

This season, we've started seeing great results using a modified version of [Red Hawk Robotics QRScout](https://www.chiefdelphi.com/t/qrscout-no-code-no-app-no-internet-no-problem/449456?u=jimmyy), paired with this [QR scanner](https://a.co/d/6rPLtb1), for match and robot scouting.

<div>
<div align="left">
<h2><span style="color:#bf5700">Customizing for Efficiency
</span></h2>
</div>

Because we highly value our scout and want use their time efficiently, we asked ourselves these questions when determining what to scout:

1. What decisions will we make as part of match strategy (or picking alliance partners)?
2. What information would be useful in making those decisions?
3. What sources could we use to gather that information?
4. If we wanted to source that information ourselves, how would we collect it?

As we walked through this process, we considered the sources of information that would not require us to collect data ourselves, such as **Statbotics** and **The Blue Alliance**. For the data we decided would be most valuable to collect ourselves, we chose to use **QRScout**, a highly customizable tool from **Red Hawk Robotics**. Using this methodology together with QRScout streamlined our process while ensuring we gather what truly matters.

<div>
<div align="left">
<h2><span style="color:#bf5700">Customizing QRScout
</span></h2>
</div>

The most common way to use QRScout is to load it from the version hosted by Red Hawk Robotics, and then have each scouter load a custom configuration file to match a team’s desired data collection. We wanted to streamline the process for our scouters, so we forked Red Hawk Robotics’ GitHub repo, and created our own version with our desired data entry built-in, not requiring any extra steps from our scouters. Additionally, we found that by forking the repository, we could further personalize the interface for our own team, including custom fonts, our personal team logo, etc. While we lacked in-house expertise on how to modify the TypeScript code to accomplish this, we managed to muddle our way through it regardless, to which we credit Red Hawk Robotics’ excellent design.

Setting up the data entry, we split the data into three categories – Before Match, During Match, and After Match. We believe that this simplification was beneficial to our scout team. It only took a minute to set up the Before Match data, and the During Match data fit entirely on one screen, and essentially consisted of just counting the game pieces delivered. The After Match data was similarly short, but critically retained the functionality to capture notes about the team’s performance in the match.

Our modified QRScout deployment can be found [here](https://scout.lynkrobotics.org/).  We particularly like the way in which it renders on a mobile device, which again is a credit to Red Hawk Robotics.

<div>
<div align="left">
<h2><span style="color:#bf5700">Automating Data Processing
</span></h2>
</div>

With the QR scanner, all scouted data feeds into a **Google Sheet**, where we’ve set up:
✅ **Team Summaries** – A breakdown of each team's performance across matches, with calculations to highlight key capabilities using a VLOOKUP system.
✅ **Match Previews** – Uses VLOOKUP to combine scouted data with our match schedule (once posted), helping us gauge scoring needs and strategy for each match.
✅ **Scout Stats** – A quick pivot table tracking scouting contributions, which ended up being a useful derivative of our system.

<div>
<div align="left">
<h2><span style="color:#bf5700">Results So Far
</span></h2>
</div>

At our first event, we collected **over 254 individual scouting entries**, and the process ran smoothly—aside from the occasional missed cursor placement in Google Sheets! Compared to past scouting methods, **this system has saved us a significant amount of time** while improving the quality of our data-driven decisions for alliance selections and even match strategy.

<div>
<div align="left">
<h2><span style="color:#bf5700">Strat Pad
</span></h2>
</div>

To effectively apply our collected data, our strategy team has a **StratPad**, which is a [Lenovo Tab P12](https://www.lenovo.com/us/en/p/tablets/android-tablets/lenovo-tab-series/lenovo-tab-p12/) running [Nebo](https://www.nebo.app/) to [plan out strategy one match at a time, 118 style](https://youtu.be/uiYgt37zIrQ?si=qPAn-PxisPPe2RqP).

**INSERT PHOTOS OF STRAT PAD**

<hr>

<div>
<div align="left">
<h2><span style="color:#bf5700">Resources
</span></h2>
</div>

[![Static Badge](https://img.shields.io/badge/Red_Hawk_Robotics-Lynk?style=for-the-badge&label=QRScout&labelColor=bf5700&color=000000)](https://www.chiefdelphi.com/t/qrscout-no-code-no-app-no-internet-no-problem/449456?u=jimmyy) 
[![Static Badge](https://img.shields.io/badge/LYNK_Edition-Lynk?style=for-the-badge&label=QRScout&labelColor=bf5700&color=000000)](https://scout.lynkrobotics.org/) 
[![Static Badge](https://img.shields.io/badge/Code_Scanner-Lynk?style=for-the-badge&label=QR&labelColor=bf5700&color=000000)](https://a.co/d/6rPLtb1) 
[![Static Badge](https://img.shields.io/badge/Tab_P12-Lynk?style=for-the-badge&label=Lenovo&labelColor=bf5700&color=000000)](https://www.lenovo.com/us/en/p/tablets/android-tablets/lenovo-tab-series/lenovo-tab-p12/zach0177us?cid=us:sem|se|google|pmax_non_pc|||ZACH0177US|18333294919|||shopping|mix|consumer&gad_source=1&gclid=CjwKCAjwvr--BhB5EiwAd5YbXm2m6A4yBMSJHTk7YUmo6a0vY8OoGSUd5Vy9eOz-eg7BaBOYwHtxVhoCn3YQAvD_BwE) 
[![Static Badge](https://img.shields.io/badge/App-Lynk?style=for-the-badge&label=NEBO&labelColor=bf5700&color=000000)](https://www.nebo.app/) 

<hr>

<div>
<div align="center">
<h2><span style="color:#bf5700">Written By
</span></h2>
</div>

<div align="center">
@Razi.ela - Co-Lead Mentor / Business Side

@rjbell4 - Co-Lead Mentor / Programming

@Jimmyy - Programming / Electrical / Strat
</div>




