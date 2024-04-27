// Delete this section upon all tasks completion

Note: The page was auto publishing from the README after some troubleshooting decided it was easier to move it back, so moved the main report back to it and changed all the links that referenced title.md to reference it. I added all the navigation to the assignment pages. When editing and copying from assignments to README.md, copy from after the first < br >< br > after the navigation link to before the last < br >< br > (spaces added so it shows up).

Completd Sections:
- 01 Ready fore review (Brian)

Sections Still Under Work
- 
- 05 (Done, Brian) (Intro added, Corrected all mark downs from Check Point 2 feedback)
- 06 (Done, Brian) (Intro added,)
- 09 (In progress, Seymore and Meyerhoff) Needs discussion, BOM in asignment and appendix (Done), front & back screenshots of allegro layout (Done), and physical PCB, if V2 discussion 1/2 page (In progress)
- 10 (In progress, Trevino and Seymore) Discuss how software meets user needs, discuss software decision making process, numbered list of 5 changes since software proposal (reference diagram), v2 discussion 1/2 page
- 11 (Done, Seymore)
- 12 (Done, Trevino and Meyerhoff)
- 13 (Done, Seymore)
- 14 (Done, Seymore)
- Appendix Needs pics of MCC config
- Clean Github main repository (In progress, Seymore)
- Update code in code repository, [Code-Repository](https://github.com/314-grp-301/Team301Code/tree/main/folder) and put it in the appendix, bottom of the report. (Done, Meyerhoff)
- Add all assignments and report format the main (title.md) file. (In progress, Seymore)
- For Google Drive, ensure the appropriate files are in each assignment folder. (Done, Meyerhoff)

For reference, the title (or main report) should be in this order:
- Front Matter (Touched, not finalized, Seymore)
- Introduction (Touched, not finalized, Seymore)
- Team Organization (Touched, not finalized, Seymore)
- User Needs and Benchmarking (Touched, not finalized, Seymore)
- Product Requirements (Touched, not finalized, Seymore)
- Design Ideation (Touched, not finalized, Seymore)
- (Final) Selected Design (Touched, not finalized, Seymore)
- (Final) Block Diagram (Touched, not finalized, Seymore)
- (Final) Component Selection (Touched, not finalized, Meyerhoff)
- (Final) Hardware Implementation
- (Final) Software Implementation
- System Verification
- Lessons Learned 
- Recommendations for future students (Finalized, Brian)
- Appendix

<br>// Delete this section upon all tasks completion
<br>
This is evidence of a recent commit for Checkpoint 3. Committed 0939 on 20240423.


## Meet Team 301

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5207.jpg" width="75%" /></td>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5204.jpg" width="75%" /></td>
  </tr>
  <tr>
    <td align="center">Brian Wegner [Electrical Systems & Organizational Leadership] </td>
    <td align="center">Fynn Meyerhoff [Robotics Systems]</td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5205.jpg" width="75%" /></td>
    <td><img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/01-IMG_5206.jpg" width="75%" /></td>
  </tr>
  <tr>
    <td align="center">Xzekiel Trevino [Electrical Systems] </td>
    <td align="center">Kevis Seymore [Electrical Systems]</td>
  </tr>
</table>

### Introduction

This report is a comprehensive compilation of Team 301’s efforts in developing the Portable Weather Station for the EGR-314 course during the Spring 2024 semester. It provides an integrated analysis of all relevant assignments, distilled into this unified document to facilitate easy access and reference. For in-depth exploration of specific topics, readers can navigate through the document by clicking on the hyperlinked headings corresponding to each chapter. Additionally, a curated selection of previous multimedia exhibits related to this project has been incorporated below to enhance understanding and engagement.

|Table of Contents| |Table of Figures|
|---|---|---|
|[Team Organization](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/01-Team-Organization-Charter.md)| | |
|[User Needs Benchmarking and Requirements](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/02-User-Needs-Benchmarking-and-Requirements.md)| | |
|[Design Ideation and Selected Design](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/03-Design-Ideation.md)| | |
|[Block Diagram](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/04-Block-Diagram.md)| | |
|[Component Selection](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/05-Component-Selection.md)| | |
|[Microcontroller Selection](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/06-Microcontroller-Selection.md)| | |
|[Hardware Implementation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/09-Hardware-Implementation.md)| | |
|[Software Implementation](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/10-Software-Implementation.md)| | |
|[Innovation Showcase Poster](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/11-Innovation-Showcase-Poster.md)| | |
|[System Verification](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/12-System-Verification.md)| | |
|[Lessons Learned](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/13-Lessons-Learned.md)| | |
|[Recommendations](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/14-Recommendations.md)| | |
|[Appendix](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/15-Appendix.md)| | |

### Mission Statement
“Our mission is to improve weather reporting by designing and implementing solutions that provide localized, real-time weather data in a wide range of environments and conditions. With a user focused experience in mind, our goal is to provide end users with the tools needed to make the necessary and informed decisions required in their daily activity planning.”

### Project Goals
- **Design Safety Device:** A device that gives accurate and current temperature and humidity readings.

### 7 Shared Goals
1. **Improve in Designing for Widespread Use:**
   - Focus on creating designs that are universally accessible and usable.
2. **Cater to Needs of the User:**
   - Prioritize user experience and user-centric design in our solutions.
3. **Build Network:**
   - Expand our professional and collaborative network for better outreach and resources.
4. **Practice Using a New Microcontroller:**
   - Enhance technical skills by experimenting with various microcontrollers.
5. **Continue Practice in PCB Creation:**
   - Develop expertise in printed circuit board design and manufacturing.
6. **Optimize Designs for Scalability and Adaptability:**
    - Create solutions that can be easily scaled and adapted to different environments and needs.
7. **Continuous Improvement in Design Processes:**
    - Commit to an iterative process of design improvement and refinement.

## User Needs, Benchmarking, and Requirements

### Similar Products
To gather a a basis to work from and a benchmark to evaluate our design to, we found a number of similar products described below.<br><br>

**Search #1 - Sainlogic Wireless Weather Station**<br>
Keywords: “Weather Reader”<br>
Selected Products<br>

Sainlogic Wireless Weather Station<br>
[link](https://www.amazon.com/sainlogic-Wireless-Forecast-Temperature-Pressure/dp/B08G1FZZ5M/ref=sr_1_2_sspa?crid=3N80YRJJJVXLU&keywords=weather+reader&qid=1705498363&sprefix=weather+reader%2Caps%2C141&sr=8-2-spons&ufe=app_do%3Aamzn1.fos.f5122f16-c3e8-4386-bf32-63e904010ad0&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1) - Used to read various specific weather statistics

![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Sainlogic.png)<br>
Price: $103<br>
Vendor: Amazon<br><br>
Common Positives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“Had it up and running in less than an hour. Only disappointment was that no batteries were included. Other than that, I'm absolutely satisfied. Easy to read and accurate.”|Very easy to use and accessible (Explicit)|
|“Weather station was installed in my elderly parents' study to give them weather details to help them plan their outdoor activities. It was easy to install and worked well even though their home is a metal building. Works as expected and readings are accurate.”|Easy installation and accurate (Explicit)|
|“The base unit readout screen is nice, good contrast, lots of information on it, more than we had on the last one. It hasn't rained yet, so we haven't seen how that works yet, but the rest of it has been effective, in comparison to our neighbors and some other readouts we have available nearby. Setting all the options along with date, time, and measurement/unit preferences was quick and easy.”|Offline usage (Latent)|

Common Negatives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“We have owned this weather station now for a year and half. Don't buy it. It's a piece of garbage. Wind direction is totally wrong even though I aligned it with the true north. I have twisted it this way or that to try to get it to read the direction correctly, but it has never worked accurately no matter what I do. The rain volume sensor is a joke as it has never been accurate either. There is no wind chill calculation showing on the monitor, which is a handy thing to know when you live in a cold climate as we do. We have owned much more accurate and useful weather stations in the past than this brand. I bought a different brand weather station over Black Friday and plan on mounting it this spring when the weather gets nice again.”|Wind Chill Calculation (Explicit)|
|“Downgrading to 1 star. Every time I change the batteries(3 months), I'm reminded what a POS this thing is. Now it wont reconnect. It's not mounted in an easy to troubleshoot location. (It's in a good weather recording location). Next stop... TRASH CAN!!”|Troubleshooting Convenience (Latent)|
|“This weather station worked for a couple of months, then stopped transmitting the outside temperature, wind speed and rainfall. We changed the batteries, went out and bought expensive lithium batteries and the reset button on the unit stayed red, never green like it’s supposed to be!”|Consistent Transmission (Latent)|

<br><br>

**Search #2 - Wi-Fi Professional Weather Station**<br>
[link](https://www.amazon.com/Crosse-Technology-328-69357-INT-Professional-Weather/dp/B09W8FX716/ref=sr_1_22_sspa?crid=2FALBK37647KB&keywords=weather+reader&qid=1705502867&sprefix=weather+reader%2Caps%2C232&sr=8-22-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1#customerReviews) - Weather station to detect weather stats
 
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Wifi-station.png)<br>
Price: $140<br>
Vendor: Amazon

Common Positives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“I love that you can add censors. We have one in our chicken pen, green house, garden and down by the river. Super easy to use and connect .”|Compatible with other sensors (Latent)|
|“I am beyond impressed with my Wi-Fi Professional Weather Station! This device has truly elevated my understanding of weather patterns and brought forecasting to a whole new level. The seamless integration with Wi-Fi allows me to access real-time data effortlessly through my smartphone, keeping me informed about current conditions and forecasts from anywhere.”|Wifi compatibility (Latent)|
|“The user-friendly interface and detailed graphs make it easy to interpret complex weather patterns, making this weather station suitable for both weather enthusiasts and professionals alike. I particularly appreciate the customizable alerts that notify me of any sudden changes, allowing me to take timely actions.”|Customizable Alerts (Explicit)|

Common Negatives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“Bought one same/similar to this from Costco at a much better price. Loved everything about it except the rain gauge. It kept blowing over during storms, so I would be running out during storms to stand it back up only to have it blow over again. I returned it. If you want one that tracks rain, buy a one piece unit with an integrated rain gauge.”|Stability in during Storms (Explicit)|
|“rain gauge does not collect as much rain as a small tube. Tech support says they are perfect reading almost an inch different on three inches of rain and not reading on a quarter of an inch.”|Accurate Rain Collection in Rain Gauge (Latent)|
|“Firstly, the Wi-Fi connectivity is inconsistent at best. Despite multiple attempts to set up the connection, the device frequently loses connection, making it unreliable for remote access. This significantly diminishes the convenience factor that comes with a Wi-Fi-enabled weather station.”|Importance of Reliable Wi-Fi for Convenience (Explicit)|

<br><br>

**Search #3 - Ambient Weather WS-2902 WiFi Smart Weather Station**<br>
[link](https://www.amazon.com/Ambient-Weather-WiFi-Station/dp/B01N5TEHLI/ref=sr_1_1_sspa?crid=3542KOGNXVDIW&keywords=remote%2Bweather%2Bstation&qid=1705515021&sprefix=remote%2Bweather%2Bstation%2Caps%2C133&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1) - Smart Water Monitor

![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Ambient.png)<br>
Price: $189.99<br>
Vendor: Amazon

Common Positives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“If you are looking for a great weather station at great price this is the perfect unit. This station has all the basics you would want and more. Rain gage that measures not only the amount of rain but hourly rain fall as well as 24 hour rain fall, weekly, monthly and rain event totals. The unit has a wind vain and anemometer for wind direction and speed, of course. It also has temperature with heat index and wind chill. We have a pool so I love that the unit measures UV index and Solar Radiation.”|Accurate Forecasting (Explicit), Mobile Accessibility (Explicit), Visual Representation (Explicit)|
|“Durability. This is the one area I cannot yet commend the AW on, only time will tell. It appears to be a better-built unit so I am optimistic and will update this review as necessary.”|Ruggedized/All-Weather (Explicit)|
|“ I also created an account at the Ambient website so I can see remotely on both the Ambient web site via a web browser and via the Ambient iPhone app – I use an iPhone and it works great.”|Mobile Accessibility (Explicit)|

Common Negatives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“So I take the display apart. Inside clearly labelled on the PCB is the antenna connection, and attached is a loose, 9.5 cm long red wire hanging out in the case (see photo). The antenna is just a small length of red wire. Now I'm not an RF engineer, but 9.5 cm isn't even a length that makes sense for picking up a 915MHz signal, and even worse its bent around a corner of the case so the shape of the wire is even less optimized. Don't get me wrong, you can use a wire like this to pick up a wireless signal it just works really bad and explains the problems people have with reception completely.To verify this I soldered on a proper sma connector and hacked it into the case (see my photo). Even with an antennae tuned to a completely different spectrum (2.4GHz/wifi) I was getting clear reception from the other side of my house 100% of the time.”|Effective Antenna Design (Latent)|
|My main complaints are; the only things that are accurate from day one until now are the indoor and outdoor weather and the indoor humidity. I was really looking forward to seeing the wind speed and the rainfall amount. The wind speed has never shown over around 13 mph even when I know we were gettting 40 mph gusts. It is windy enough as I write this that my flag is standing straight out and my station says 4.1-4.6 mph.|Ruggedized/All-Weather (Explicit)|
|“I bought this to replace my long-serving WS-1001 when it died. The sensors are nice and easy to install. I am not a fan of this new display even though it is color compared to my old one which was B&W. The viewing angle is pretty poor. Although it has mounting holes to enable it to hang on the wall it is very tough to read if hung at picture height. The display really needs to be below eye level. The old display did not have this limitation. And although this is a color display the colors don’t mean anything - they’re static and pretty random. I know how to grab the data from the sensors directly so I think I’ll build my own display.”|Visual Representation (Explicit)|

<br><br>

**Search #4 - Newentor Weather Station**<br>
Newentor Weather Station Wireless Indoor Outdoor with Rain Gauge and Wind Speed, Professional Tempest Digital Weather Stations with Data Logging and Alerts, Weather Forecast, Barometer, Solar Powered<br>
[link](https://www.amazon.com/Newentor-Wireless-Professional-Stations-Barometer/dp/B0CG87FVB6/ref=sr_1_14_sspa?content-id=amzn1.sym.e16c80d0-77bd-4ad0-8c6a-0b24e2e4d736%3Aamzn1.sym.e16c80d0-77bd-4ad0-8c6a-0b24e2e4d736&keywords=rain+gauge&pd_rd_r=769ac1a4-ef33-4cfe-b726-32fad9aa665b&pd_rd_w=imOZR&pd_rd_wg=eQsvR&pf_rd_p=e16c80d0-77bd-4ad0-8c6a-0b24e2e4d736&pf_rd_r=ZFGG6QPRCHANM61DPH6V&qid=1705516808&sr=8-14-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1) - Weather station to detect weather stats

![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Newentor.png)<br>
Price: $129.99<br>
Vendor: Amazon

Common Positives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“This weather station was easy to set up using the nice full book size color instructions. It has good information about current weather conditions”|Multi-Location Support (Explicit)|
|“This weather station was easy to set up using the nice full book size color instructions. It has good information about current weather conditions”|Learning & Tips Resources (Latent)|
|“The unit works perfectly! I love the colorful screen and the other features that it has. I will be purchasing another.”|Visual Representation (Explicit)|

Common Negatives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“Sensor died within 6 months, zero tech support”|Ruggedized/All-Weather (Explicit)|
|“Temperature sensor outdoor measures 12 degrees to hot when the sun shines on the sensor. Emailed the manufacture they said this is normal. If you want accurate outdoor temperature you will want a different weather station.”|Accurate Forecasting (Explicit)|
|The weather forecast is not connected to a weather service but rather overall change in barometric pressure. Which could actually be interesting information as I can get the local forecast other places.|Integration With Other Apps/Platforms (Latent)|

<br><br>

**Search #5 - Tempest Weather System**<br>
[link](https://www.amazon.com/Tempest-Weather-Accurate-Forecasts-Wireless/dp/B0868WY7NY/ref=sr_1_1_sspa?dib=eyJ2IjoiMSJ9.Qyt2_FSNDzvW5erzazZv5_68GS8f-AO3xjiNOJQxjHpcko7rXs0G-MKWwHmrDD8Mi68vGcKxQw-2V9o8UoZXh9NkBEuma7eCMk9pQmtIIMI8pSlfdDjbGPt9Z3YXlr8U5TluKCmDQvxAu-7bgMNHaS-4kOrQyjwMlWueEfSMkRbxMqroFly4XoCOhfKonAcYlDePhfyw58Ow3jFXgLS1nHzFqdFFoXbiSJia-8QjDw-ToP8spR4vkPaUzYukEL-ERc9TkvDTvlGPSbPj5Qu1S7TpCzRVY1nCLoGmFFPdJg0.d79bDSLFvdNgiOlF6Yz4S5e27GS6Kp0IG25AZtc8ges&dib_tag=se&hvadid=664223481015&hvdev=c&hvlocphy=9030084&hvnetw=g&hvqmt=e&hvrand=1841615953807592180&hvtargid=kwd-1030435799694&hydadcr=19197_13537830&keywords=tempest+weather+system&qid=1705528402&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1) - A Complete Weather Solution for Your Home

![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Tempest1.png)![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Tempest2.png)<br>
Price: $340<br>
Vendor: Amazon/Shop WeatherFlow

Common Positives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“This truly is the only ‘rain sensor’ that has ever really worked consistently with my smart irrigation controller, and I get all the other great weather station features as well.“|Consistent Rain Sensor for Smart Irrigation (Explicit)|
|“Temperatures have been spot on, wind readings are responsive and accurate. The lighting detection is unbelievable – you can track storms heading in and leaving with just this feature alone. Highly recommend the new Tempest.”|Effective Storm Tracking with Lightning Detection (Explicit)|
|“I recently switched from my old Davis Vantage Pro to the Tempest, and overall, I'm pleased with the decision. The build is solid, and the readings are accurate, but I miss the convenience of a remote console in the kitchen for a quick and easy summary of the station's data, a feature lacking in the Tempest. Despite this, I don't mind the rain adjustments based on local stations' data, which some users complain about, as it can be turned off if desired.”|Desire for Convenient Remote Console (Latent)|

Common Negatives Consist Of:
|Customer Review|Customer Need|
|-|-|
|“Everything worked seamlessly for several days until I got a message on Saturday about a data update issue. Spent four frustrating hours troubleshooting online, checking and rechecking everything. Turns out, the problem was a "Pressure Failed" sensor, and despite multiple attempts to fix it, I ended up packing the $350+ unit for return by Monday, disappointed that it failed so quickly.”|Reliable Performance (Explicit)|
|“Living in a consistently rainy area with varying precipitation amounts, I've been disappointed with the Tempest's accuracy in representing rainfall over the 18 months it's been installed, finding it to be greatly underrepresented and expressing regret over the decision to use the tool.”|Accurate Rainfall Representation (Explicit)|
|"Despite the initial hype, this weather station proves ineffective in northern climates, requiring excessive winter sunlight, providing inaccurate measurements, and lacking satisfactory customer support, leading the user to suggest investing in more established brands.”|Climate-Adaptive Functionality (Explicit)|

<br><br>

**Search #6 - OTT HydroMet Urban Flood Warning System**<br>
[Link](https://www.otthydromet.com/en/applications/flood-warning?_bk=flood%20monitoring%20system&_bm=p&_bt=648555245186&_bn=g&_bg=151874351171&gclid=EAIaIQobChMIpejp1vnkgwMVVwytBh3utgDHEAAYASAAEgJ7ZPD_BwE) - Weather station to detect weather stats

![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-OTT.png)
Price: Unlisted - Priced at Order<br>
Vendor: OTT Hydromet

The OTT HydroMet Urban Flood Warning System has been included as an extra search option despite it not having product and/or review data that aligns with this assignment. It has been included, despite the missing data, as a direct to consumer made item by the company. The device is designed for government services, not for regular private use. Because of this, there are a lack of private user reviews as the product was not designed to be sold to them.<br><br>
The system has been included since it is a close representation of the intended finished product aimed at non-commercial use. This aligns with the conceptual idea of an early warning flood detection system to detect and warn civilian populations of localized flooding conditions for emergency management.

<br><br>

## Additional User Needs

**Explicit**<br>
- Real-Time Data Access<br>
- User-Friendly Interface<br>
- Accurate Forecasting<br>
&nbsp;&nbsp;&nbsp;&nbsp;Ambient Air Temperature<br>
&nbsp;&nbsp;&nbsp;&nbsp;Water Temperature<br>
&nbsp;&nbsp;&nbsp;&nbsp;Wind Speed<br>
&nbsp;&nbsp;&nbsp;&nbsp;Water Flow Rate<br>
&nbsp;&nbsp;&nbsp;&nbsp;Water Depth/Rain Detection<br>
&nbsp;&nbsp;&nbsp;&nbsp;Humidity Detection<br>
- Customization Options<br>
&nbsp;&nbsp;&nbsp;&nbsp;Unit Conversions temperatures (e.g. Fahrenheit vs Celsius)<br>
&nbsp;&nbsp;&nbsp;&nbsp;Unit Conversions (e.g. Imperia Standard vs Metric)<br>
- Multi-Location Support<br>
- Mobile Accessibility<br>
- Visual Representation<br>
- Severe Weather Alerts<br>
- Historical Data Access<br>
- Integration With Other Apps/Platforms<br>
- Language and Units Customization<br>
- Energy Efficiency Insights<br>
- Air Quality Information<br>
- Ruggedized/All-Weather<br>
&nbsp;&nbsp;&nbsp;&nbsp;Water proof<br>
&nbsp;&nbsp;&nbsp;&nbsp;Submeragable (water submerged system component)<br>

<br><br>

**Latent**<br>
- Contextual Insights<br>
- Social Integration<br>
- Localized Community Updates<br>
- Personalized Lifestyle Recommendations<br>
- Travel Planning Assistance<br>
- Emotional Impact Consideration<br>
- Learning Resources<br>
- Offline Accessibility<br>
- Eco-Friendly Recommendations<br>
- Integration with Smart Home Devices<br>
- Mood Customization<br>
- Collaborative Forecasting<br>

<br>

## User Needs Jamboard Summation
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Jam1.png)<br>
## User Needs Organization / Ranking
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/02-Ranking.png)<br>

<br><br>

**3. Develop Requirements**<br><br>

**User Story Statement**<br><br>

User Story #1: Kevin (Home owner, private resident)<br>
Kevin is a homeowner who resides in an area prone to flash flooding. Realizing the potential damage of flooding to his property, Kevin is interested in purchasing an all-weather station	in order to mitigate flood risks to his personal property. With an early detection system, Kevin is able to safeguard his property by either relocating it or preparing counter-flood mitigation techniques (e.g. sandbags).<br><br>
	
User Story #2: Jane (County Emergency Services Management)<br>
Jane is an emergency service management specialist employed by the county and is responsible for monitoring extreme weather conditions that affect the public. To best serve the public, Jane relies on an early warning weather network of ruggedized remote weather stations that can detect real-time weather conditions and changes within the county. With this information, precise real-time weather updates can be sent to emergency management teams to aid them in warnings, emergency responses, and other critical decision-making processes.<br><br>

**Design Aspects**<br>
Listed are the original, design aspects prior to the change to a more minimalistic, portable weather system. After the the given aspect, it is noted whether it was met :white_check_mark: by the final device or if it was not :x: and why.
1. Product Design<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.1 The product’s exterior should be minimalistic to be unobtrusive visually in a water environment such as a controlled stream. :white_check_mark: <br>
&nbsp;&nbsp;&nbsp;&nbsp;1.2 The shape of the device should not have sharp and jutting portions that would cause debris in a waterway to build up on it. :white_check_mark: [Though, not intended for use in a waterway.]<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.3 The tether pole shall have a groove that keeps the device facing properly up or downstream as intended. :x: [No longer intended for use in a wateray.]<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.4 The product shall be designed to be watertight. :x: [No longer intended for use in a wateray.]<br>
&nbsp;&nbsp;&nbsp;&nbsp;1.5 The product’s exterior should have mounting capabilities so that it stays secure in a storm. :x: [Device was made to prioritize portability, but fasteners could be added to a later iteration.]<br>
2. Functionality<br>
&nbsp;&nbsp;&nbsp;&nbsp;2.1 The device must be able to determine its relative height and compare it to a baseline while noting significant changes over short periods automatically. :x: [No longer intended for use in a wateray.]<br>
&nbsp;&nbsp;&nbsp;&nbsp;2.2 The device shall be able to determine the water flow rate. :x: [No longer intended for use in a wateray.]<br>
&nbsp;&nbsp;&nbsp;&nbsp;2.3 The device shall be able to determine wind speed (where placed). :x: [Device determines temperature and humidity instead.]<br>
3. Interactivity<br>
&nbsp;&nbsp;&nbsp;&nbsp;3.1 The device shall have a simple push button to enable and disable. :white_check_mark:<br>
4. Adaptive Intelligence<br>
&nbsp;&nbsp;&nbsp;&nbsp;4.1 The device shall be able to provide itself with additional lift as needed if something has caused it to become too submerged. :x: [No longer intended for use in a wateray.]<br>
5. Customization<br>
&nbsp;&nbsp;&nbsp;&nbsp;5.1 The device can have multiple colors for the exterior to be able to make it blend in with a waterway or stand out to be easier to find and collect. :white_check_mark: [Though, not intended for use in a waterway, it would be asy to manufacture and replace the device chassis.]<br>
6. Manufacturing<br>
&nbsp;&nbsp;&nbsp;&nbsp;6.1 The total cost of the prototype shall be < $240. :white_check_mark:<br>
&nbsp;&nbsp;&nbsp;&nbsp;6.2 The device shall be designed with a minimal amount of parts. :white_check_mark:<br>
7. Regulations<br>
&nbsp;&nbsp;&nbsp;&nbsp;7.1 The device shall not chemically alter the water in which it is placed. :white_check_mark: [Not chemically harmful, though, not intended for use in a waterway.]<br>

**Open Questions**<br>
- Can the device be made easily recyclable and repairable? :white_check_mark: [The device can be easily repaired if the user/tech is knowledgable, but it is not intended for recyclables.]<br>
- Can we connect the device to a power source safely to remove the need for batteries? :white_check_mark:<br>
- Is there additional functionality that can be added with later modifications or simply with code? :white_check_mark: [Additional data tracking can be added easily prior to distribution.]<br><br>

# Design Ideation
The analysis of requirements and potential functionality lead us to concept the designs shown below each with their own advantages and disadvantages.

## 1. Brainstorm Table of Features/Ideas/Concepts

|                                   |                                  |                                   |                                   |                                   |
|-----------------------------------|----------------------------------|-----------------------------------|-----------------------------------|-----------------------------------|
| 5 in 1 Outdoor Sensor             | Weather Clock                    | Clear Color Display               | Precise Measurements              | Radio/Transmission                |
| Accuracy                          | Mobile                           | Wind Speed Gauge                  | Air Pressure                      | Moon Phase                        |
| Alarm Clock                       | 3rd Party Compatible             | Bright Display                    | Rain Gauge                        | Temperature                       |
| Solar Powered                     | UV Protectant Plastic            | Wind Propeller                    | Noise Detector                    | Offline & Online Usage            |
| Backup Battery                    | Smart Irrigation Compatibility   | Low Latency Transmission          | User Customization (DIY Friendly) | Custom Alerts, Badges             |
| Rugged Design for Storms          | Rain Collection Gauge            | High UV Detection                 | Thermo-Hygrometer                 | Bubble Level                      |
| Air Quality Sensors               | Multi-mounting Ability           | Fully Submersible                 | Nature Friendly                   | Built-in Speaker                  |
| Historical Trend Graphing         | Built-in Light (for Errors)      | Long Range Transmission           | Dew Point Sensor                  | Barometric Pressure               |
| Sea-level                         | Lightning Detection              | Rain Rate Detector                | Snow Depth Sensor                 | Geolocation                       |
| Crop Weather Reminder             | Sunrise and Sunset Detection     | Customizable Device Skins         | Earthquake Alerts                 | Wildlife Motion Tracking          |
| Security System                   | No Maintenance                   | Cylindrical Shape for Portability | Separate Display                  | Satellite Compatibility           |
| Weather Almanac Data              | GPS Capability                   | Intranet Network                  | Cold-Weather Proof                | Localized Display                 |
| Localized Configuration           | Remote Configuration             | All-Weather Ruggedization         | Hot-Weather Proof                 | Anti-theft Protection             |
| Tamper Protection                 | Fault Detection & Reporting      | Battery Backup 24h Service        | Wind Direction Gauge              | Water Temperature Gauge           |
| Water Flow Rate Tracking          | Water Rise/Depth Detection       | Warning System                    | 4G/5G Cell Network Integration    | Radio Communication Network       |
| Soil Absorption Detection System  | Soil Erosion Detection           | Auditory Warning System           | Emergency Rescue Button to EMS    |                                   |

## 2. Sort, Rank, and Group Design Concepts
Here are two tables organizing our brainstorming ideas/concepts/features into six different categories. They are ranked by interest level, indicated by the following colors:
- 🟠 Orange for highest interest
- 🟢 Green for neutral interest
- ⚪ Gray for lowest interest

 ![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-table1.png)
 ![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-table2.png)

## 3. Our three product concept sketches
Below are the original concepts. Concept 1

### Cocept 1 (Portable Weather Pod)
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-concept1a.png) 
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-concept1b.png)
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-concept1c.png)

**Description**

This portable weather pod features a simple and compact design, equipped with several advanced features. It includes an onboard OLED screen displaying data from various environmental sensors. 
The pod's customizable skin (camouflage shown) allows the user to blend it seamlessly into the appropriate environment.

**:zap: Key Features**

- **Solar Powered:** Utilizes solar energy for efficient power use.
- **Portable:** Easy to move and install in various locations.
- **OLED Display:** Clear and informative data presentation.
- **Speaker:** Audio feedback for alerts and notifications.
- **Full Weatherproof:** Designed to withstand harsh environmental conditions.
- **5-in-One Sensor:** Multi-functional sensor for comprehensive environmental data.
  - **Temperature:** Measures ambient temperature accurately.
  - **Humidity:** Monitors air moisture levels.
  - **Barometric:** Provides pressure readings.
  - **Wind:** Measures wind speed and direction.
  - **Rain:** Detects precipitation and rain intensity.

### Concept 2: Portable Adverse Weather Detection System
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-concept2a.png)

**Description**

The Portable Adverse Weather Detection System serves as an early warning and monitoring system for adverse weather conditions and flash flooding. Incorporated with other detection systems, it provides emergency management services (EMS) with the capability to detect and monitor areas at risk of flash flooding. This service offers EMS real-time data of ground conditions, aiding in delivering more accurate weather warnings to the public and responding to emergencies as required.

**:zap: Features**

- **Solar Power with Battery Backup:** Ensures continuous operation, independent of external power sources.
- **Adjustable Solar Panel (Motorized):** Solar panel adjusts automatically according to the time of day for optimal energy capture.
- **Precipitation Detection and Monitoring (Sensor 1):** Accurately detects and monitors rainfall and other forms of precipitation.
- **Ambient Air Temperature (Sensor 2):** Measures and records the ambient air temperature.
- **Remote Access (WiFi):** Allows for remote monitoring and control via WiFi connectivity.
  
### Concept 3: Waterway Weather and Flash Flood Detection Buoy
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-concept3a.png)

**Description**

The Waterway Weather and Flash Flood Detection Buoy would serve a similar purpose as Concept 2, but be housed in a waterway. It wirelessly communicates temperature, humidity, water flow rate, and change in water level over time. Not only providing present values, it is also programmed to send out alerts for various conditions like sudden rises or falls in water flow rate and water level. This enables it to issue flash flood warnings or other preset alarms based on a target baseline. The device is waterproof and capable of detecting when it's submerged, with basic mechanisms to surface itself.

**:zap: Features**

- **Sensors:**
  - **Temperature:** Measures ambient temperature.
  - **Humidity:** Monitors air moisture levels around the waterway.
  - **Pressure (Directed Towards Expected Water Flow):** Used to determine water flow-rate.
  - **Movement:** Tracks height and changes in water level.
- **Motor-Controlled Height Adjustment:** Attached to an installed rod, allows the buoy to adjust its height relative to water level.<br><br><br>

# Selected Design
Originally we had intended to create a flash flood detection system (Concept 3), but due to potential constraints with the watertight capabilities and the water motion detection system we shifted to the weather pod (Concept 1), kept the general concept and minimized potential shortcomings which resulted in the Portable Weather Pod.

## Final Concept: Portable Weather Pod
![alt text](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/03-Concept_4.png)

**:zap: Key Features**

- **Portable:** Easy to move and install in various locations.
- **Weatherproof:** Designed to withstand harsh environmental conditions.
- **OLED Display:** Clear and informative data presentation.
- **WIFI Capable:** Uses the ESP32 chipset to transmit data to the net.
- **2 Key Sensors:** Multi-functional sensor for comprehensive environmental data.
  - **Temperature:** Measures ambient temperature accurately.
  - **Humidity:** Monitors air moisture levels.
---

# Block Diagram
Depicted is a diagram of all the key subsystems of the the weather pod device. The determining factors for the setup were the devices chosen and the communication types for said devices. We needed the temperature sensor, humidity sensor, and motor driver to communicate with the microcontroller's limited I2C and SPI pins. This proved difficult, originally, as while the MCU had the capability to support two I2C devices and an SPI device to do so required multiple devices to share a pin. This was resolved on the software side by recognizing and communicating with different addresses for the devices.<br>

![My Image](https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/Block%20Diagram%20Draft.png)

# Component Selection
## 1 - Motor Driver
- System Lead: Kevis Seymore
- Choice: **(Option 4)** IFX9201SGAUMA1
- Rationale: The IFX9201SGAUMA1 motor controller has been recommended for similar use cases and has a thorough datasheet and support around it helping eliminate much of the guesswork when attaching it to a PCB or coding for it.
### Driver Solution - 1: BD6211F-E2
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-BD6211F-E2.jpg" width="200">

**Cost:** $2.19 per unit

| Pros                                       | Cons                 |
|--------------------------------------------|----------------------|
| Extensive datasheet                        | Costly per unit      |
| Utilizes standard SPI                      | Footprint not provided |
| Additional support files provided          |                      |
| High precision sensorless motor load detection |                    |

### Driver Solution - 2: BD6210F-E2
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-bd6210f-e2.jpg" width="200">

**Cost:** $2.46 per unit

| Pros                                         | Cons                  |
|----------------------------------------------|-----------------------|
| Daughter board comes soldered                | Costly per unit       |
| Built-in thermal shutdown                    | Datasheet is minimalistic |
| CW/CCW/short-brake/stop motor control modes  | Footprint provided    |

### Driver Solution - 3: ROB-12859
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-ROB-12859.jpg" width="200">

**Cost:** $21.50 per unit

| Pros                                         | Cons                         |
|----------------------------------------------|------------------------------|
| Recommended by Digikey support for I2C stepper motor use | Costly per unit              |
| Extensive documentation                      | Would take up more space than needed on PCB |
| Built-in thermal shutdown                    |                              |
| Short to ground protected                    |                              |

### Driver Solution - 4: IFX9201SGAUMA1 :star:
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-IFX9201SGAUMA1.jpg" width="200">

**Cost:** $4.00 per unit

| Pros                                       | Cons                 |
|--------------------------------------------|----------------------|
| Low standby current                        | Complex chip      |
| Overtemp shutdown                     | Limited to DC motors |
| 3.3V logic compatible          |                      |
---

## Component 2 - Motor
- System Lead: Kevis Seymore
- Choice: Option 1: LS-00028
- Rationale: The LS-00028 motor offers the perfect balance of compact size and high efficiency, making it an excellent choice for our small scale project.

### Motor Solution - 1: ROB-10846
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-ROB-10846.jpg" width="200">

**Cost:** $19.50 per unit

| Pros                                     | Cons                             |
|------------------------------------------|----------------------------------|
| Recommended for use with ROB-12859       | Minimalistic datasheet           |
| High resolution steps (400 per revolution) | Round shaft requires press fit or clamp |
| Low voltage required                     |                                  |

### Motor Solution - 2: ROB-09238
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-ROB-09238.jpg" width="200">

**Cost:** $18.79 per unit

| Pros                                  | Cons                                  |
|---------------------------------------|---------------------------------------|
| Slightly lower price compared to ROB-10846 | Minimalistic datasheet              |
| 18.76 gcm<sup>2</sup> rotor inertia             | Lower resolution (200)               |
|                                       | High voltage required (12V)           |
|                                       | Round shaft requires press fit or clamp |

### Motor Solution - 3: FIT0278
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-FIT0278.jpg" width="200">

**Cost:** $13.95 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Low voltage required                      | Schematic not provided in datasheet      |
| Termination with connector and leads provided allowing for removal and/or easier installation and maintenance | Round shaft requires press fit or clamp |

### Motor Solution - 4: 4641
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-4641.jpg" width="200">

**Cost:** $12.50 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Compact: Ideal for space-limited applications. | Limited Torque: May struggle with high power or heavy loads. |
| Precision Control: Offers fine adjustments in speed and torque. | Wear and Tear: Gearbox can wear out, especially under heavy use. |
| Energy Efficient: Suitable for battery-powered projects. | Noise: Gear meshing can produce undesirable noise. |

### Motor Solution - 5: LS-00028 :star:
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-LS-00028.jpg" width="200">

**Cost:** $5.98 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Cost Effective | Small Torque|
|Efficient| Limited Speed Control |
---

## Component 3 - Temperature Sensor
- System Lead: Xzekiel Trevino
- Choice: **Option 4:** TC74A4
- Rationale: The TC74A4 temperature sensor is the ideal for our project based on price point, supporting documentation and fits within the expected voltage operating range of the project. While the sensor degrades in accuracy after 100° F, the drop off is negligible within ranges it will be operating within.

### Temp Sensor Solution - 1: TPIS 1S 1385 / 5029
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-TPIS-1S-1385.jpg" width="200">

**Cost:** $13.63 per unit

| Pros                                  | Cons                                         |
|---------------------------------------|----------------------------------------------|
| Power Range: 2.6V ~ 3.6V              | Expensive                                    |
| Digital, IR                           | Many features outside the scope of the project and not required |
| Ambient and/or object heat detection  |                                              |

### Temp Sensor Solution - 2: AT30TSE004A-MAA5M-T
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-AT30TSE004A-MAA5M-T.jpg" width="200">

**Cost:** $1.32 per unit

| Pros                                     | Cons                                         |
|------------------------------------------|----------------------------------------------|
| ±1C° accuracy (40-90°F)                    | Accuracy degrades after 95°F                  |
| Temp Conditional Emergency Alarm/Shutoff | ±3.0°C accuracy (maximum) over the -20°C to +125°C range |

### Temp Sensor Solution - 3: LM75BDP,118
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-LM75BDP.jpg" width="200">

**Cost:** $0.91 per unit

| Pros                                  | Cons                              |
|---------------------------------------|-----------------------------------|
| Cheap price point                     | Accuracy degrades after 100°F      |
| Extensive Data sheet and support documents |  ±2°C accuracy                                |
| 2.8-5V operating range                |                           |

### Temp Sensor Solution - 4: TPIS 1S 1385 / 5029 :star:
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-TC74A4-3.3VCTTR.jpg" width="200">

**Cost:** $1.15 per unit

| Pros                                  | Cons                                         |
|---------------------------------------|----------------------------------------------|
| High Precision              | Limited Temperature Range                                    |
| Low Power Consumption                           | No Analog Output |
| Easy Integration  | Single Address                                             |
---
## Component 4 - Humidity Sensor
- System Lead: Brian Wegner
- Choice: **Option 3:** HIH6030
- Rationale: The HIH6030 Humidity Sensor was determined to be the best choice of the three components based on meeting all project requirements. This particular component further set itself apart from the crowd by having an extensive data sheet with example code, different schematic configurations, and having online support.

### Humidity Sensor Solution - 1: SHT40-AD1B-R2
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-SHT40-AD1B-R2.jpg" width="200">

**Cost:** $2.58 per unit

| Pros                                       | Cons                                       |
|--------------------------------------------|--------------------------------------------|
| Accurate ±1.8%                             | Will require power converters if system operates higher than 3.6V |
| Low Power 1.08v - 3.6V                     | Small Component                            |
| Surface Mount                              |                                            |
| Digital Sensor                             |                                            |
| Operates in AZ extreme heat conditions     |                                            |
| I2C Serial                                 |                                            |
| GitHub Support                             |                                            |

### Humidity Sensor Solution - 2: BPS240-D2P0-S10E
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-BPS240-D2P0-S10E.jpg" width="200">

**Cost:** $5.78 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Surface Mount                             | Higher Power Requirement 1.62v - 5.5v    |
| Digital Sensor                            | 30 second response time                  |
| Operates in AZ extreme heat conditions    |                                          |
| I2C Serial                                |                                          |
| GitHub Support                            |                                          |

### Humidity Sensor Solution - 3: HIH6030 :star:
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-HIH6030-021-001.jpg" width="200">

**Cost:** $13.43 per unit

| Pros                                      | Cons                                     |
|-------------------------------------------|------------------------------------------|
| Surface Mount                             | Expensive                                |
| Most Accurate                             | Higher Power Requirement 2.7v - 5.5v     |
| Example code and setup in Data Sheet      |                                          |
---
## Component 5 - LCD Screen
- System Lead: Brian Wegner/Xzekiel Trevino
- Choice: **Option 3:** NHD-0216SZ-NSW-BBW-33V3
- Rationale: Due to the simplistic nature and close acquaintance with this component, we believe this can display all our information without the headache of learning other complex display layouts in the short timeframe. It also has a relatively small form factor and low cost. 

### LCD Solution - 1: 64128K COG FA BW
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-64128K%20COG%20FA%20BW.jpg" width="200">

**Cost:** $12.28 per unit

| Pros                            | Cons                                    |
|---------------------------------|-----------------------------------------|
| 128 x 64 display                | Tight pin layout, difficult soldering   |
| Small (56 x 39 x 8.5mm)         | May require additional drivers          |
| Light Weight: 1 oz              | Expensive solution                      |
| Power: 3V                       |                                         |

### LCD Solution - 2: NHD-C12864LZ-FSW
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-NHD-C12864LZ-FSW-FBW-3V3.jpg" width="200">

**Cost:** $17.64 per unit

| Pros                                     | Cons                                 |
|------------------------------------------|--------------------------------------|
| 128 x 64 display                         | Bad Resolution                       |
| Fastest Response Time/least lag from input to screen update | Most Expensive Solution             |
| Largest Viewing Area: 70 x 40 mm         | High backlighting may require more power |

### LCD Solution - 3: NHD-0216SZ-NSW-BBW-33V3 :star:
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-MFG_NHD-0216SZ-NSW-BBW-33V3.jpg" width="200">

**Cost:** $24.34 per unit

| Pros                       | Cons                                   |
|----------------------------|----------------------------------------|
| Easy to program            | Limited to 2x16 characters             |
| Sample Code Available      | No images                              |
| Can make custom fonts      | Unable to order small batch (2-3 units)|
---
## Component 6 - Power Switch Regulator (Microcontroller)
- System Lead: Fynn Meyerhoff
- Choice: **Option 1:** LM2575-3.3WU-TR
- Rationale: The LM2575-3.3WU-TR is a good option because it offers a reliable 3.3V suitable for most microcontrollers. This was also the same regualtor used in an in-class activity. 

### Power Regulator Solution - 1: LM2575-3.3WU-TR :star:
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-LM2575-3.3WU-TR.jpg" width="200">

**Cost:** $1.75 per unit

| Pros                                              | Cons                                        |
|---------------------------------------------------|---------------------------------------------|
| Versatile with a wide input voltage range.        | Lower current capacity compared to some newer designs. |
| Capable of driving a 1.0A load.                   | Requires several external components.       |
| Available in various fixed and adjustable output versions. | Might be less efficient than newer alternatives. |

### Power Regulator Solution - 2: LM2596S-5.0
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-LM2596S-5.0.jpg" width="200">

**Cost:** $6.81 per unit

| Pros                                          | Cons                                          |
|-----------------------------------------------|-----------------------------------------------|
| Reliable performance with good thermal management. | Larger size compared to newer regulators.     |
| Wide input voltage range.                     | Lower switching frequency might not be ideal for all applications. |
| Built-in thermal shutdown and current limit features. | Fixed 5.0V output limits flexibility unless using an adjustable version. |

### Power Regulator Solution - 3: MP1584EN-LF-Z
<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-MP1584EN-LF-Z.jpg" width="200">

**Cost:** $2.81 per unit

| Pros                                      | Cons                                             |
|-------------------------------------------|--------------------------------------------------|
| High efficiency in conversion.            | Potentially noisier output due to high switching frequency. |
| Compact size, suitable for space-constrained applications. | Might require additional filtering for sensitive applications. |
| High current capability (up to 3A).       | Limited by a maximum input voltage of 28V.        |

## Power Budget

<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/05-Power_Budget.PNG" width="1000">

# Microcontroller Selection
## Introduction

Microcontrollers play an important role in electrical system projects. They serve as the ‘brain’ that controls and orchestrates the functions of various components within the system or a subsystem. These components allow designs to implement code such as Python, C+, and other advanced programing languages to control hardware and software within the device. Microcontrollers are found in nearly all modern electronic devices.

For our project, we determined that the PIC16F15354 produced by Microchip was the optimal solution for our project based on a variety of factors ranging from the number of GPIO pins to I2C/SPI computability. A further breakdown of our selection processes as well as a side-by-side comparison of alternative chip considerations can be found below.


## Microcontroller Selection

| Feature      | **Option 1** :star: | Option 2     | Option 3     |
|--------------|----------------|--------------|--------------|
| **Part #**   | **PIC16F15354**| PIC16F1517   | PIC18F47K42  |
| **GPIO**     | **22 (21 req)**| 33           | 33           |
| **ADC**      | **24 (1 req)** | 28           | 35           |
| **PWM**      | **4 (1 req)**  | 0            | 4            |
| **I2C/SPI**  | **2/0**        | 1/0          | 2/0          |
| **UART**     | **1 (0 req)**  | 1            | 2            |

**Choice: Option 1**

<img src="https://raw.githubusercontent.com/314-grp-301/314-grp-301.github.io/main/docs/assets/images/06-PIC16F15354.png" width="300">

**Reasons:**

- It has 2 different I2C ports, perfect for the temperature and humidity sensor
- SPI functionality for the motor driver
- Low power consumption, ideal for a small 9V 600mAh battery
- MCC snap compatible, a familiar interface in MPLabX 
- Plenty of GPIO for LED's and other accessories
---
## Design Considerations 

| Feature                                      | Project Requirements | PIC16F15354 | PIC16F1517 | PIC18F47K42 |
|----------------------------------------------|----------------------|-------------|------------|-------------|
| **How many GPIO Pins?**                      | 21                   | 22          | 33         | 33          |
| **Built-in Analog to Digital Converter?**    | 1                    | 24          | 28         | 35          |
| **Built-in Hardware PWM?**                   | 0-1                  | 4           | 0          | 4           |
| **Built-in I2C? SPI?**                       | 2 I2C’s, no SPI’s    | 2           | 1          | 2           |
| **Built-in UART?**                           | 0                    | 1           | 1          | 2           |
| **Other Required Built-In Features?**        | TBD                  |             |            |             |
| **Additional considerations (Low Power Mode?)** | ?                  |             |            |             |

## Microcontroller Considerations

| Information                             | PIC Option 1                                                                 | PIC Option 2                                                               | PIC Option 3                                                               |
|-----------------------------------------|------------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------|
| **Part Number**                         | PIC16F15354                                                                  | PIC16F1517                                                                 | PIC18F47K42                                                                |
| **Link to product page**                | [Product Page Link](https://www.microchip.com/en-us/product/PIC16F15354)     | [Product Page Link](https://www.microchip.com/en-us/product/pic16f1517)   | [Product Page Link](https://www.microchip.com/en-us/product/pic18f47k42)  |
| **Link to Data Sheets**                 | [Data Sheets](https://www.mouser.com/datasheet/2/268/PIC16F_LF_15354_55_Data_Sheet_40001853D-2885845.pdf) | [Data Sheets](https://ww1.microchip.com/downloads/aemDocuments/documents/OTH/ProductDocuments/DataSheets/40001452F.pdf) | [Data Sheets](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18%28L%29F26-27-45-46-47-55-56-57K42-Data-Sheet-40001919G.pdf) |
| **Link to Application Notes**           | [Notes](https://www.microchip.com/en-us/application-notes)                 | [Notes](https://www.microchip.com/en-us/application-notes)               | [Notes](https://www.microchip.com/en-us/application-notes)               |
| **Link to Code Examples**               | [Code Examples](https://www.microchip.com/en-us/code-examples)             | [Code Examples](https://www.microchip.com/en-us/code-examples)           | [Code Examples](https://www.microchip.com/en-us/code-examples)           |
| **Link to External Resources**          | [External Resources](https://www.instructables.com/Programming-PIC-Microcontrollers/) | [External Resources](https://www.instructables.com/Programming-PIC-Microcontrollers/) | [External Resources](https://www.instructables.com/Programming-PIC-Microcontrollers/) |
| **Production Unit Cost**                | $1.39                                                                       | $2.29                                                                     | $3.48                                                                     |
| **Supply Voltage Range**                | Vdd(min) = +2.3V, Vdd(max) = +5.5V                                          | Vdd(min) = +2.3V, vdd(max) = +5.5V                                        | Vdd(min) = +2.3V, vdd(max) = +5.5V                                        |
| **Absolute Maximum Current for entire IC** | Vss = 350 mA, Vdd = 250 mA                                                  | Vss = 350 mA, Vdd = 350 mA                                                | Vss = 350 mA, Vdd = 350 mA                                                |
| **Maximum GPIO Pin Current (Source/Sink)** | ± 40 mA                                                                    | ± 50mA                                                                    | ± 50mA                                                                    |
| **8-bit or 16-bit Architecture**         | 8 bit                                                                       | 8 bit                                                                     | 8 bit                                                                     |
| **Available IC Packages / Footprints**   | S(PDIP), SOIC, SSOP, QFN, UQFN                                              | PDIP, UQFN                                                                | PDIP, UQFN, TQFP, QFN                                                     |
| **Supports External Interrupts?**        | Yes                                                                         | Yes                                                                       | Yes                                                                       |
| **In-System Programming Capability**     | Yes, ICSP                                                                   | Yes, ICSP                                                                 | Yes, ICSP                                                                 |
| **Works with MPLAB® X IDE?**             | Yes                                                                         | Yes                                                                       | Yes                                                                       |
| **Works with Microchip Code Configurator?** | MCC Classic works                                                            | MCC Classic works                                                         | MCC Classic works                                                         |
---
## Microcontroller Detailed Requirements

**GPIO Pins Required: 17** (Excluding debug LED’s!)
- [2] Temperature Sensor (LM75BDP,118) - Digital
  - Serial Data Line (SDA)
  - Serial Data Clock (SCL)
- [2] **Humidity Sensor (HIH6030-021-001)** - Digital
  - Serial Data Line (SDA)
  - Serial Data Clock (SCL)
- [4] **Motor Driver (IFX9201SGAUMA1CT-ND)** - Digital
  - SCK
  - CSN
  - SI
  - SO
- [7] **LCD Screen (3086-MD21605G12W3-BNMLW-VE-ND)** Assuming 8-bit mode:
  - DB0-DB7 (4 pins Data Bus Line)
  - RS (1 pin for Register Select)
  - R/W (1 pin for Read and Write)
  - E (1 pin for Enable)
- [2] **ESP32 Wireless Receiver**
  - RX
  - TX

**Built-in Analog to Digital Converter: 1**
- All sensors and drivers are digital, but including 1 ADC is advisable for potential future needs.

**Built-in Hardware PWM: 1**
- Required for the Motor Driver to control motor speed.

**Built-in I2C & SPI: 2 I2C’s & 0 SPI’s**
- I2C interfaces: 2 (Temp & Humid sensor can be addressed differently through the same bus)
- SPI interfaces: Not required for this project.

**Built-in UART: 0**
- Humid/Temp Sensor: Communicate via I2C or SPI, not UART.
- Motor Driver: Uses digital signals for control, not UART.
- LCD Screen: Uses a parallel or I2C/SPI interface, not UART.
<br><br>
[Previous](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/05-Component-Selection.md) - [Main Page](../README.md) - [Next](https://github.com/314-grp-301/314-grp-301.github.io/blob/main/Assignments/09-Hardware-Implementation.md)
