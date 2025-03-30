---
layout: default
title: "Micro Project - Group 77"
---

<div class = "header" >
Drugs and naroctics in San Francisco
</div>
<div class="introduction" markdown="1" style="max-width: 1000px; margin: 0 auto; text-align: justify; text-justify: inter-word;">
  Like many states in the United States, San Fransisco has had its issues with handling crime related to drugs and narcotics over the years. <br>
  The following is a deep dive into how these crime reports have evolved over the years between 2003 to 2025. 
  The figures and statements are made based on information extracted from San Francisco Open Data <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data">[DataSF, 2015]</a> and <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data">[DataSF, 2024]</a> 
</div>

---

<div class = "figure-header" >
San Francisco's Battle Against Drug Crimes: A Yearly Overview
</div>

<div class="narrative-container" style="display: flex; align-items: flex-start; justify-content: space-between; width: 100%; max-width: 1200px; margin: 0 auto; overflow: hidden;">
  <div class="image-container">
    <img src="/assets/figures/drug time series.png" alt="Figure 1" style="border:none; width: 100%; max-width: 100%; display: block;">
  </div>
  
  <div class="text-container" style="flex: 0 0 35%; max-width: 35%; text-align: justify; word-break: break-word; overflow-wrap: break-word; hyphens: auto; min-width: 300px;">
    <h2>Understanding the Data</h2>
    <p>Over the years, San Francisco has faced a fluctuating battle against drug-related crimes. This bar chart vividly illustrates the annual counts of drug/narcotic crimes, showcasing the peaks and troughs in the city's past and ongoing efforts to curb illegal drug activities. Each bar represents a year, with the height indicating the number of reported incidents. Notice how it has steadily dropped since 2009, but seems to be picking back up from 2022.
    
    <br> <br>

    There could be numerous causes for the steady droprate. Crime overall has been steadily decreasing in San Francisco, but not as much as is reflected in drug/narcotics. Recreational cannabis was legalised in 2018 which would also account for a drop in marijuanna-related crimes
    <a href="https://www.bbc.com/news/world-us-canada-42532776">[BBC, 2018]</a>. The spike seen in 2022 could reflect the national fentanyl crisis that America is facing which has hit San Francisco especially hard <a href="https://www.sfchronicle.com/projects/san-francisco-drug-overdose-deaths">[San Francisco Chronolice, 2025]</a>, but fentanyl deaths have been on the rise since 2016 <a href="https://www.cfr.org/backgrounder/fentanyl-and-us-opioid-epidemic">[Council of Foreign relations, 2025]</a>, so it should not only spike after 2022. However, the Corona epidemic could arguably also help explain the lower counts in the years 2019-2023 despite the fentanyl crisis.</p>
  </div>
</div>



---
<div class = "figure-header" >
Hotspots of Drug Activity: A District-Wise Heat Map
</div>

<div class="narrative-container" style="display: flex; align-items: flex-start; justify-content: space-between; width: 100%; max-width: 1200px; margin: 0 auto; overflow: hidden;">
  <div class="text-container" style="flex: 0 0 35%; max-width: 35%; text-align: justify; word-break: break-word; overflow-wrap: break-word; hyphens: auto; min-width: 300px;">
    <h2>Explore the timeline</h2>
    <p>This heat map provides a striking visual representation of drug/narcotic crime hotspots across San Francisco, overlaid with the boundaries of police districts. The size of the red areas of the heat map colors indicates the concentration of incidents, with larger areas signifying more crime occurances. By overlaying police district borders, we can see which areas are most affected and how law enforcement resources might have been be allocated to address these critical zones. 

  <br><br>

    What is interesting, is the development over the years. Notice how the in 2003, the crimes are spread out to all of Eastern San Fransisco with Northen, Central, Tenderloin, Southern and Mission being almost one big hotspot. Then as we progress through the years, the hotspot gets much smaller almost only covering Tenderloin (while there still being several singular crimes spread out in all of San Fransisco). So, while narcotics crimes are still obviously a problem, the clear majority of them are contained in a rather concise area. Tenderloin having issues with drug-related crimes is a well-known fact that the district has been combatting for many years <a href="https://edition.cnn.com/2023/09/03/us/san-francisco-tenderloin-drug-market/index.html">[CNN, 2023]</a>. 

  <br><br>

    You can explore the data yourself using the controls at the bottom of the heatmap or zooming in on areas-of-interest using the mouse.  
    </p>
  </div>
  <div class="image-container" style="flex: 0 0 65%; max-width: 65%; display: flex; justify-content: center;">
    <iframe src="/assets/html/A2_san_francisco_heatmapwithtime.html" 
            style="border:none; width: 100%; height: 600px; max-width: 100%; display: block;"></iframe>
  </div>
</div>


---

<div class = "figure-header" >
Crime Clock: When Drug Offenses Peak in San Francisco
</div>

<div class="narrative-container" style="display: flex; align-items: flex-start; justify-content: space-between; width: 100%; max-width: 1200px; margin: 0 auto; overflow: hidden;">
  <div class="image-container">
    <iframe src="/assets/html/Narcotic 24h by district 4.html" style="border:none; width: 100%; max-width: 100%; display: block;"></iframe>
  </div>
  <div class="text-container" style="flex: 0 0 35%; max-width: 35%; text-align: justify; word-break: break-word; overflow-wrap: break-word; hyphens: auto; min-width: 300px;">
    <h2>Understanding the Data</h2>
    <p>Ever wondered when drug-related crimes are most likely to occur? This interactive plot breaks down the number of drug/narcotic crimes by each hour of the day. This allows us to delve into the daily rhythms of drug crimes. Notice how much the day of the week actually affects crime rates. It is clear that the weekend sees less overall reports compared to weekdays - except for 5am where very little crime seems to occur at all no matter the day. It is interesting to see that even drug crimes seems to somewhat take the weekends off. For buglaries/theft it would make sense to see less crime over weekends, as people are home and harder to steal from, but the use of narcotics should not have this limitation. However, it is important to note that this data reflects reports of crimes and not the actual occurances. For a crime to be reported it needs to be witnessed, and if people are doing drugs at home over the weekend that is not reflected in this data. 

  <br><br>

    You can explore this data yourself by toggling the various police districts in San Francisco. Each district is represented by a different color, with overlapping bars indicating the intensity of incidents. The hover tool provides additional context, showing the exact count of crimes for each hour and district.

