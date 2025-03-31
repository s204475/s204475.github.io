---
layout: default
title: "Micro Project - Group 77"
---

<div class = "header" >
  <h1>Drugs and Narcotics in San Francisco</h1>
</div>

<div class="project-members" style="text-align: center; margin-top: 10px; font-size: 1.1em;">
  <p>Paula Barho (s242926) &nbsp;|&nbsp; Aleksandar Lukic (s194066) &nbsp;|&nbsp; Victor Gustav Harbo Rasmussen (s204475)</p>
</div>

<div class="introduction" markdown="1" style="max-width: 1200px; margin: 0 auto; text-align: justify; text-justify: inter-word;">
  Like many states in the United States, San Francisco has had its issues with handling crime related to drugs and narcotics over the years. <br>
  The following is a deep dive into how these crime reports have evolved over the years between 2003 to 2024. 
  The figures and statements are made based on information extracted from San Francisco Open Data <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data">[DataSF, 2015]</a> and <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data">[DataSF, 2024]</a> 
</div>

---

<div class = "figure-header" style="text-align: center; margin-bottom: 20px;">
  <h2>San Francisco's Battle Against Drug Crimes: A Yearly Overview</h2>
</div>

<div class="narrative-container" style="display: flex; align-items: flex-start; justify-content: space-between; width: 100%; max-width: 1200px; margin: 0 auto; overflow: hidden;">
  <figure class="image-container" style="flex: 1 1 65%; min-width: 65%; max-width: 65%; display: flex; justify-content: center; flex-direction: column; align-items: center;">
    <img src="/assets/figures/drug_crimes_by_year.png" alt="Figure 1" style="border:none; width: 100%; max-width: 100%; display: block;">
    <figcaption style="font-style: italic; font-size: 0.9em; margin-top: 5px;">Figure 1: Annual counts of drug/narcotic crimes in San Francisco in 2003-2024.</figcaption>
  </figure>
  
  <div class="text-container" style="flex: 1 1 35%; min-width: 35%; max-width: 35%; text-align: justify; word-break: break-word; overflow-wrap: break-word; hyphens: auto; min-width: 300px;">
    <h2>Understanding the Data</h2>
    <p>Over the years, San Francisco has faced an up-and-down battle against drug-related crime. This bar chart vividly illustrates the annual incidents of drug/narcotics crimes, showing the highs and lows of the city's past and ongoing efforts to curb illegal drug activity. Each bar represents a year, with the height indicating the number of reported incidents. Note how the number of incidents has been steadily decreasing since 2009, but seems to increase again from 2022 onwards.
    
    <br> <br>

    There could be numerous causes for the steady droprate. Crime overall has been steadily decreasing in San Francisco, but not as much as is reflected in drug/narcotics. Recreational cannabis was legalised in 2018 which would also account for a drop in marijuanna-related crimes <a href="https://www.bbc.com/news/world-us-canada-42532776">[BBC, 2018]</a>. The spike seen in 2022 could reflect the national fentanyl crisis facing America, which has hit San Francisco particularly hard <a href="https://www.sfchronicle.com/projects/san-francisco-drug-overdose-deaths">[San Francisco Chronicle, 2025]</a>, but fentanyl deaths have been on the rise since 2016 <a href="https://www.cfr.org/backgrounder/fentanyl-and-us-opioid-epidemic">[Council of Foreign Relations, 2025]</a>, so it should not only spike after 2022. However, the Corona epidemic could arguably also help explain the lower counts in the years 2020-2023 despite the fentanyl crisis.</p>
  </div>
</div>



---
<div class = "figure-header" style="text-align: center; margin-bottom: 20px;">
  <h2>Hotspots of Drug Activity: A District-Wise Heat Map</h2>
</div>

<div class="narrative-container" style="display: flex; align-items: flex-start; justify-content: space-between; width: 100%; max-width: 1200px; margin: 0 auto; overflow: hidden;">
  <div class="text-container" style="flex: 1 1 35%; min-width: 35%; max-width: 35%; text-align: justify; word-break: break-word; overflow-wrap: break-word; hyphens: auto; min-width: 300px;">
    <h2>Explore the timeline</h2>
    <p>This heat map provides a striking visual representation of drug/narcotics crime hotspots across San Francisco, overlaid with police district boundaries. The size of the red areas in the heat map colours indicates the concentration of incidents, with larger areas indicating more crime. By overlaying police district boundaries, we can see which areas are most affected and how law enforcement resources may have been allocated to address these critical areas.

  <br><br>

    What is interesting is the development over the years. Notice how in 2003, the crimes were spread out to all of Eastern San Francisco with Northern, Central, Tenderloin, Southern and Mission being almost one big hotspot. Then as we progress through the years, the hotspot gets much smaller, almost only covering Tenderloin (while there still being several singular crimes spread out in all of San Francisco). So, while narcotics crimes are still obviously a problem, the clear majority of them are contained in a rather concise area. Tenderloin having issues with drug-related crimes is a well-known fact that the district has been combating for many years <a href="https://edition.cnn.com/2023/09/03/us/san-francisco-tenderloin-drug-market/index.html">[CNN, 2023]</a>. 

  <br><br>

    You can explore the data yourself using the controls at the bottom of the heatmap or by hovering and clicking on the areas-of-interest using the mouse.  
    </p>
  </div>
  <figure class="image-container" style="flex: 1 1 65%; min-width: 65%; max-width: 65%; display: flex; flex-direction: column; align-items: center; justify-content: center;">
    <iframe src="/assets/html/A2_san_francisco_heatmapwithtime.html" 
            style="border:none; width: 100%; height: 600px; max-width: 100%; display: block;"></iframe>
    <figcaption style="font-style: italic; font-size: 0.9em; margin-top: 5px; text-align: center;">
      Figure 2: Heatmap movie diplaying the development of drug/narcotic-related crime incidents in San Fransisco over the years, where each frame corresponds to a month in a year. The districts are highlighted and display their respective counts. 
    </figcaption>
  </figure>

</div>


---

<div class = "figure-header" style="text-align: center; margin-bottom: 20px;">
  <h2>Crime Clock: When Drug Offenses Peak in San Francisco</h2>
</div>

<div class="narrative-container" style="display: flex; align-items: flex-start; justify-content: space-between; width: 100%; max-width: 1200px; margin: 0 auto; overflow: hidden;">
  <figure class="image-container" style="flex: 1 1 65%; min-width: 65%; max-width: 65%; display: flex; justify-content: center; flex-direction: column; align-items: center;">
    <iframe src="/assets/html/drug_crime_plot.html" style="border: 1px solid transparent; width: 100%; max-width: 1000px; height: 600px; display: block; flex-grow: 1;"></iframe> 
    <figcaption style="font-style: italic; font-size: 0.9em; margin-top: 5px; text-align: center;">
      Figure 3: Interactive bar plot of hourly incidents of drug/narcotic crimes per district in San Francisco. The multi-choice tool allows for the selection of specific years.
    </figcaption>
  </figure>
  <div class="text-container" style="flex: 1 1 35%; min-width: 35%; max-width: 35%; text-align: justify; word-break: break-word; overflow-wrap: break-word; hyphens: auto; min-width: 300px;">
    <h2>Understanding the Data</h2>
    <p>Ever wondered when drug-related crimes are most likely to occur? This interactive plot breaks down the number of drug/narcotic crimes by each hour of the day. This allows us to delve into the daily rhythms of drug crimes. Notice how much the day of the week actually affects crime rates. It is clear that the weekend sees less overall reports compared to weekdays - except for 5am where very little crime seems to occur at all no matter the day. It is interesting to see that even drug crimes seem to somewhat take the weekends off. For buglaries/theft it would make sense to see less crime over weekends, as people are home and harder to steal from, but the use of narcotics should not have this limitation. However, it is important to note that this data reflects reports of crimes and not the actual occurrences. For a crime to be reported it needs to be witnessed, and if people are doing drugs at home over the weekend that is not reflected in this data. 

  <br><br>

    You can explore this data yourself by toggling the various police districts in San Francisco. Each district is represented by a different color, with overlapping bars indicating the intensity of incidents. The hover tool provides additional context, showing the exact count of crimes for each hour and district. Additionally, you can select different years in the multi-select tool on the left top of the figure. 

  </p>
</div>
