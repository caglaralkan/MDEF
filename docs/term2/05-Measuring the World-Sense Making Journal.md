---
hide:
    - toc
---

# Measuring the World-Sense Making Journal


**Measuring the World**


Data vs Information

We started our project with a bunch of questions:
- Do I spend enough time in nature?
- Is my work fulfilling?
- Is my identity / life shaped mostly by my work?
- Are our salaries high enough?
- Do we get health care?
- Do we have recovery time at the end of a work day?
- Do we have time to connect with people in a meaningful way?
- Do we have time and energy to do what we love?
- Do we feel we are free to choose what we do?
- Do we have enough time for our mental health?

Then we decided to work on the subject of “Work-Life balance”. We were aware that it was a broad subject. So, we decided to build a circuit with LDR sensor and gather data on how much time we are spending inside and how much time left us from work to see some daylight?

After building the LDR sensor circuit we made some configurations as changing the resistor to 1K to get appropriate numbers in order to get the different values for inside and outside brigthness. The next step was to restoring the data from the LDR sensor. We tried to use bluetooth through our mobile phones(with the idea of carrying the sensor with us everywhere), but it was quite complicated process and we couldn’t succeed at the end. We ended up the decision of using wifi.

Josep helped us to figure out how to store the data by downloading Arduspreadsheets and logging the LDR data in a .csv file. We used If This Then That (IFTTT) to connect to Webhooks to publish the data over Wifi. After this we were able to connect the ESP32 to a phone hotspot and the device was mobile. The LDR sensor sent the value of the light that it detected every six seconds.

On the other hand, as our time was limited, we tried to gather more info through web, results of some surveys and research through an application called Orange3. We found a big research called “World Happiness Report” and we analyzed that with the help of Orange3. But, we figured out that it was more related with socio-economic information. Then, we also tried to acquire info from a survey that made by OECD.Stat which shows the percentage of adults who reported that over the last 12 months it has been difficult for them to fulfill their family responsibilities because of the amount of time they spent at work. In order to gather informations and graphics that we wanted, we had to install some add-on for Orange3 and for Mac version it took so much time.

The third step to get information through web was using twitter data and analysis of some tweets through specific keywords. The process could be done by text-mining add-on. We went through several analysing and data visualising tools as SENTIMENT ANALYSIS, BOX PLOT-emotion analyze, Corpus Viewer, Word Cloud, Preprocess Text…

The work we did mostly about the methodology. We did not have the chance to gather correct and appropriate data within two days to propose a solution to our hypothesis. But, the discovery of this methodology was really useful for future-works. According to me, it is essential to design a balanced scenario to capture the data through sensors by first hands and support that by using the data that already captured by several applications through web and networks.

Link for the Repository;

https://hackmd.io/wLNUaeyyR32BA8rWh7lFUg?view
