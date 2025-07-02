---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>



I received the B.Sc. degree in electrical engineering and automation, in 2020, from Sichuan University, Chengdu, China, and the M.Sc. (cum laude) degree in electrical power engineering, in 2022, from the Delft University of Technology, Delft, The Netherlands, where she is currently working toward the Ph.D. degree in electrical engineering with DC Systems, Energy Conversion and Storage (DCE&S) group. Her research interests include battery systems and the power electronics interface for electric aircraft.

# 🔥 News
- *2025.06*: &nbsp;🎉🎉 One paper is accepted by IEEE Transactions on Transportation Electrofication

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Charging technology for electric aircraft</div><img src='images/Charger_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Charging Technology for Electric Aircraft: State of the Art, Trends, and Challenges](https://ieeexplore-ieee-org.tudelft.idm.oclc.org/document/10319783)

**Yawen Liang**, Gautham Ram Chandra Mouli, Pavol Bauer

**[IEEE Transactions on Transportation Electrification]**

*Electric aircraft technology has gained considerable attention and is rapidly developing to mitigate the environmental impact of air transportation and move toward more sustainable modes. Nevertheless, the unique characteristics of electric aircraft pose significant challenges for the charging infrastructure, which must be effectively addressed to facilitate the growth of electric aircraft. This article provides a comprehensive review of the latest developments and future trends in electric aviation, which covers electric aircraft, battery technology, and electric aircraft charging systems. This article also surveys the possible charging system architectures that can be employed for electric aircraft charging. Various power electronic converter topologies that are suitable for future electric aircraft DC fast chargers are presented. This article concludes by identifying future challenges in the path toward charging electric aircraft and discusses potential solutions to these challenges.*

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">BTMS optimization for electric aircraft</div>
      <img src='images/BTMS_Optimization.png' alt="battery" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
[Optimization of a Liquid-Cooled Lithium-Ion Battery Pack for Electric Aircraft Based on an Integrated Electro-Thermal-Aging Pack Model](https://ieeexplore.ieee.org/document/xxxxxxx)

**Yawen Liang**, Weiming Luo, Gautham Ram Chandra Mouli, Pavol Bauer

**[IEEE Transactions on Transportation Electrification]**

<p><em>
To design a battery pack with improved energy density and optimized thermal and aging performance, a complete electro-thermal-aging (ETA) model at both cell and pack levels is developed to predict pack behavior under operational conditions. Optimization based on the proposed model is conducted, focusing on geometric configurations of the battery pack and coolant flow parameters. An optimized liquid-cooled battery module using Samsung 18650-35E cells is designed and achieves a maximum temperature of 41.76 °C, and a maximum cell-to-cell temperature difference of 3.11 °C, improving thermal uniformity. The lifetime performance also demonstrates a 5.51% improvement in state-of-health (SOH) after 180 cycles. Based on the module-to-pack structure analysis, the battery pack exhibits energy densities of 227.01 W h kg<sup>−1</sup> gravimetrically and 353.67 W h L<sup>−1</sup> volumetrically. This study facilitates the guideline for compact and lightweight liquid-cooled battery pack design with improved thermal and aging performance for AEA applications.
</em></p>


</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Charging demand prediction for electric aircraft</div>
      <img src='images/Charging_Demand_Prediction.png' alt="battery" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
[Charging Demand Prediction: Small All-Electric Aircraft and Electric Vertical Takeoff and Landing Aircraft](https://ieeexplore-ieee-org.tudelft.idm.oclc.org/document/10597592)

**Yawen Liang**, Dávid Bodnár, Gautham Ram Chandra Mouli, Daniele Ragni, Pavol Bauer

**[IEEE Transactions on Transportation Electrification]**

<p><em>
Electric aircraft (EA) is a promising alternative to conventional fuel-based aircraft, offering reduced greenhouse gas emissions and enhanced operational efficiency. To ensure seamless operations and optimize energy management, accurate EA charging demand prediction becomes imperative. This article presents a study on forecasting the charging demand for future small- and short-range EA. First, battery sizes are determined for various types of small all-EA (AEA) and electric vertical takeoff and landing (eVTOL) aircraft. Utilizing the electrical circuit model (ECM) for lithium-ion batteries (LIBs), this study derives the charging power curve of EA under the constant current–constant voltage (CC–CV) charging strategy. Subsequently, the charging demand prediction is conducted using the flight schedule of a selected airport, allowing for a realistic assessment of the power requirements for charging EA. Finally, case studies exploring charging demand under different scenarios are conducted. The results highlight the substantial power demand associated with the charging process, emphasizing the essential infrastructure needs and potential approaches for managing charging power in electric flight.
</em></p>

</div>
</div>


# 💬 Research Experience
- *2021.09-2022.06*, MSc. Thesis: *IoT-Based Online Harmonic Emission Estimation of DC Fast Chargers*  
  Supervised by **Dr. Lu Wang** and **Prof. Zian Qin**

  - Developed a harmonic emission model for two-level active front-end EV chargers used in DC fast-charging stations.
  - Validated the proposed model through simulation and experiment.
  - Built an IoT platform for harmonic calculation supporting device-to-cloud communication, including a front-end interface and a back-end for data handling and messaging.
  
  - IoT platform demonstration video:
  
    <div style="margin-top: 10px;">
      <video width="60%" controls>
        <source src="images/IoTplatform.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    
  - Experiment setup
  <p align="center">
  <img src="images/ExperimentSetup_TUD.png" alt="Experimental Setup at TU Delft" width="60%">
  </p>
  
  - Control block diagram
  <p align="center">
  <img src="images/ControlDiagram_TUD.png" alt="AFE of EV charger with the control block diagram" width="30%">
  </p>



- *2021.09-2022.02*, Semester Project: *Investigation of Switching Loss Measurements of SiC MOSFETs*  
  Supervised by **Anliang Hu** and **Prof. Dr. Jürgen Biela**

  -  Modified the traditional double-pulse test circuit to enable zero voltage switching (ZVS) turn-on evaluation
  - Developed and implemented a ZVS control scheme using FPGA
  - Conducted experimental measurements and analysis of switching losses
  
  - Experiment setup
<p align="center">
  <img src="images/ExperimentSetup_ETHz.png" alt="Experimental Setup at ETH Zürich" width="60%">
</p>

# 🎖 Honors and Awards
- *2025.06* 2nd Place, IEEE ITEC+EATS Student Design Competition: Design the high voltage/high-power distribution system for a regional (90 passenger) fully electric aircraft 
- *2025.02* 3rd Place, [IEEE VTS Challenge](https://vtsociety.org/membership/call-ideas-innovations-vehicle-propulsion-technologies-address-climate-change): Innovations in vehicle propulsion technologies to address climate change.

  - *Reconfigurable Hybrid Battery Pack for Future Electric Aircraft: Integrating High-Specific-Energy and Power Battery Types*


# 📖 Educations
- *2022.07 - 2026.01*, Ph.D., Battery and Power Electronics, Delft University of Technology, The Netherlands.
- *2020.09 - 2022.07*, M.Sc., Electrical Power Engineering, Delft University of Technology, The Netherlands.
- *2021.09 - 2022.02*, Exchange Student, ETH Zürich, Switzerland.
- *2016.09 - 2020.06*, B.Sc., Electrical Engineering, Sichuan University, China.


