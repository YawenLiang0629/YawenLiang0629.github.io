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

Ph.D. candidate in power electronics and battery systems, focusing on electric aircraft applications. Experienced in hands-on development of experimental platforms; the design and optimization of high-efficiency power converters; impedance-based harmonic analysis of grid-connected rectifiers; power-semiconductor device characterization; and battery modeling and testing (electrical, thermal, and aging) at both the cell and pack levels.



# News
- *2026.04*: &nbsp;🎉🎉 One paper is accepted by IEEE Transactions on Transportation Electrification
- *2025.06*: &nbsp;🎉🎉 One paper is accepted by IEEE Transactions on Transportation Electrification
- *2025.05*: &nbsp;🎉🎉 One paper is accepted by ECCE Europe 2025
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by IEEE Transactions on Transportation Electrification
- *2024.03*: &nbsp;🎉🎉 One paper is accepted by ITEC USA 2024
- *2023.11*: &nbsp;🎉🎉 One paper is accepted by IEEE Transactions on Transportation Electrification
- *2022.07*: &nbsp;🎉🎉 One paper is accepted by IECON 2022



# Research Experience
- *2023.12-Present*, *Power Electronics Interfaces for the Powertrain Integration of Hybrid Battery Packs*  
  Supervised by **Dr. Gautham Ram Chandra Mouli** and **Prof. Dr. Pavol Bauer**, 

  - Proposed a hybrid battery pack concept using two battery cell types to increase both energy and power densities, achieving a 15.6% weight reduction for a short-range electric vertical takeoff and landing (eVTOL) compared with a single-cell-type design.
  - Designed the eVTOL powertrain architecture using a partial power processing (PPP) structure. Compared multiple topologies and selected the dual-active-bridge (DAB) topology for the isolated DC/DC converter in the PPP structure.
  - Developed a triple-phase-shift (TPS) modulation strategy for the DAB to achieve all-switch zero-voltage switching (ZVS) and reduce current stress across full voltage and load ranges to improve efficiency.
  - Built and experimentally validated efficiency improvements on a SiC MOSFET-based 3.3 kW DAB prototype under varying voltage and load conditions of the proposed modulation, achieving up to 2.5% higher efficiency compared with minimum-current-stress TPS and a peak efficiency of 98.51%; compared experimental results with analytical loss calculations to evaluate the efficiency performance.
  - Built and experimentally validated the PPP design on an 8 kW prototype, achieving 6.95 % higher system efficiency than a full-power-rated architecture and a 60 % reduction in converter size.

   - Circuit diagram of DAB converter and experiment setup:
<p align="center">
  <img src="images/DAB Diagram.png" alt="DAB Diagram" width="35%">
  <img src="images/DAB PPP Experiment.png" alt="DAB PPP Experiment" width="35%">
</p>




- *2022.07-2024.04*, *Battery Pack Optimization Based on an Integrated Electro-Thermal-Aging Pack Model*  
  Supervised by **Dr. Gautham Ram Chandra Mouli** and **Prof. Dr. Pavol Bauer**

  - Experimentally determined the electrical circuit model (ECM) parameters of Samsung 18650-35E lithium-ion cells under different state-of-charge levels, temperatures, C-rates, and aging states using current pulse testing with an Arbin battery tester.
  - Developed an electro-thermal-aging (ETA) model at both cell and pack levels to predict battery pack behavior under operational conditions for all-electric aircraft (AEA).  
  - Validated the proposed model through experiments and ANSYS Fluent simulation, achieving thermal prediction accuracy within 0.87 ◦C  for a representative AEA mission profile at the pack level. 
  - Optimized battery pack geometry and coolant flow parameters using the ETA model, resulting in a Samsung 18650-35E liquid-cooled pack with energy densities of 227.01 Wh kg<sup>−1</sup> and 353.67 Wh L<sup>−1</sup> at the pack level. Achieved a 5.51% state-of-health improvement after 180 cycles.
  - ETA model and experiment setup for battery testing:
<p align="center">
  <img src="images/ETA Model.png" alt="Electro-Thermal-Aging Battery Model" width="35%">
  <img src="images/Battery Exp Setup.png" alt="Experimental Setup for Battery Testing" width="35%">
</p>


- *2021.09-2022.07*, MSc. Thesis: *IoT-Based Online Harmonic Emission Estimation of DC Fast Chargers*  
  Supervised by **Dr. Lu Wang** and **Prof. Zian Qin**

  - Transformed the cascaded control loop (inner current and outer voltage, PI controller) of a grid-connected three-phase two-level PWM rectifier for DC fast-charging stations into a linearized small-signal model, and simplified it to derive the rectifier’s input impedance.
  - Modeled the current harmonic source of the PWM rectifier using Fourier series analysis, considering the modulation method and dead-time effects.
  - Developed the harmonic emission model based on the input impedance and harmonic current source, and validated it via PLECS and experiments with a CINERGIA grid emulator and Imperix modules.
  - Built an Internet-of-Things (IoT) platform supporting device-to-cloud communication with a front-end interface and a back-end for data handling and messaging.

  - IoT platform demonstration video:
  
  <div style="margin-top: 10px; text-align: center;">
    <video width="60%" controls>
      <source src="images/IoTplatform.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>



  - Experiment setup
  <p align="center">
  <img src="images/ExperimentSetup_TUD.png" alt="Experimental Setup at TU Delft" width="60%">
  </p>




- *2021.09-2022.02*, Semester Project: *Investigation of Switching Loss Measurements of SiC MOSFETs*  
  Supervised by **Anliang Hu** and **Prof. Dr. Jürgen Biela**

  - Performed a step-by-step theoretical switching transition analysis, including turn-on and turn-off dynamics and parasitic effects. Modified the traditional double-pulse test circuit to enable ZVS turn-on evaluation.
  - Developed and implemented the ZVS control scheme using an FPGA board. Analyzed the limitations of non-ideal measurement techniques in terms of bandwidth and accuracy, and conducted comparison tests to select suitable current and voltage probes.
  - Conducted experimental measurements of switching losses and analyzed deviations with the datasheet-based analytical switching loss model.



- *2021.05-2021.08*, Summer Project: *Optimization Code for the Design of IPT Resonant Converters*  
  Supervised by **Dr. Francesca Grazian** and **Prof. Dr. Thiago Batista Soeiro**

  - Modeled and analyzed a series-series (SS)-compensated inductive power transfer (IPT) resonant converter for EV wireless charging using MATLAB and LTspice.
  - Investigated soft switching behavior and developed a state-space model to assess component losses.
  - Performed system efficiency analysis under varying thermal and load conditions.
  - Validated simulation results with experimental data and identified optimal design parameters for efficiency improvement.


# Publications 


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">TTE 2025</div>
      <img src='images/LiquidModule.png' alt="battery" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
[Optimization of a Liquid-Cooled Lithium-Ion Battery Pack for Electric Aircraft Based on an Integrated Electro-Thermal-Aging Pack Model](https://ieeexplore.ieee.org/document/11071921)

**Yawen Liang**, Weiming Luo, Gautham Ram Chandra Mouli, Pavol Bauer

**[IEEE Transactions on Transportation Electrification]**

<p><em>
To design a battery pack with improved energy density and optimized thermal and aging performance, a complete electro-thermal-aging (ETA) model at both cell and pack levels is developed to predict pack behavior under operational conditions. Optimization based on the proposed model is conducted, focusing on geometric configurations of the battery pack and coolant flow parameters. An optimized liquid-cooled battery module using Samsung 18650-35E cells is designed and achieves a maximum temperature of 41.76°C, and a maximum cell-to-cell temperature difference of 3.11°C. The lifetime performance also demonstrates a 5.51% improvement in state-of-health (SOH) after 180 cycles. Based on the module-to-pack structure analysis, the battery pack exhibits energy densities of 227.01 Wh kg<sup>−1</sup> gravimetrically and 353.67 Wh L<sup>−1</sup> volumetrically.
</em></p>


</div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">TTE 2024</div>
      <img src='images/TTE - Charging Demand2.png' alt="battery" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
[Charging Demand Prediction: Small All-Electric Aircraft and Electric Vertical Takeoff and Landing Aircraft](https://ieeexplore.ieee.org/document/10597592)

**Yawen Liang**, Dávid Bodnár, Gautham Ram Chandra Mouli, Daniele Ragni, Pavol Bauer

**[IEEE Transactions on Transportation Electrification]**

<p><em>
This article presents a study on forecasting the charging demand for future small- and short-range EA. First, battery sizes are determined for various types of small all-EA (AEA) and electric vertical takeoff and landing (eVTOL) aircraft. Utilizing the electrical circuit model (ECM) for lithium-ion batteries (LIBs), this study derives the charging power curve of EA under the constant current–constant voltage (CC–CV) charging strategy. Subsequently, the charging demand prediction is conducted using the flight schedule of a selected airport, allowing for a realistic assessment of the power requirements for charging EA. Finally, case studies exploring charging demand under different scenarios are conducted.
</em></p>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TTE 2023</div><img src='images/TTE - Review2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Charging Technology for Electric Aircraft: State of the Art, Trends, and Challenges](https://ieeexplore.ieee.org/document/10319783)

**Yawen Liang**, Gautham Ram Chandra Mouli, Pavol Bauer

**[IEEE Transactions on Transportation Electrification]**

*This article provides a comprehensive review of the latest developments and future trends in electric aviation, which covers electric aircraft, battery technology, and electric aircraft charging systems. This article also surveys the possible charging system architectures that can be employed for electric aircraft charging. Various power electronic converter topologies that are suitable for future electric aircraft DC fast chargers are presented. This article concludes by identifying future challenges in the path toward charging electric aircraft and discusses potential solutions to these challenges.*

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ITEC 2024</div><img src='images/ITEC2024 - Reconfig BP.png' alt="ITEC" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hybrid Reconfigurable Battery Pack for All-Electric Aircraft: Synergizing High-Specific-Energy and Power Battery Types](https://ieeexplore.ieee.org/document/10598954)

Mayuresh Bhide, **Yawen Liang**, Gautham Ram Chandra Mouli, Mohamad Ghaffarian Niasar, Pavol Bauer

**[ITEC 2024]**

<p><em>
Based on the optimal system voltage and power profile of the reference all-electric aircraft, this paper presents the design of a hybrid reconfigurable battery pack. The design incorporates a combination of high-specific-energy  (263 Wh kg<sup>−1</sup> at cell level) and high-specific-power  (1800 W kg<sup>−1</sup> at cell level) battery types,  and its performance is compared with that of a fixed configuration battery pack comprising a single battery type. Simulation results suggest a potential 900 kg (18% lighter than the fixed configuration) weight savings with the reconfigurable pack, translating into enhanced payload, energy savings, or range extension for a 9-passenger Eviation Alice electric aircraft,  with just 0.4% more energy capacity loss over 500 cycles.
</em></p>

</div>
</div>




<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">IECON 2022</div>
      <img src='images/IECON2022 - Control Diagram.png' alt="IECON" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
[Harmonic Emission Modelling of Electric Vehicle Chargers](https://ieeexplore.ieee.org/document/9968654)

**Yawen Liang**, Lu Wang, Zian Qin, Pavol Bauer

**[IECON 2022]**

<p><em>
In emerging fast-charging stations, DC fast chargers (DCFCs) are employed, which rely on power electronics and control to achieve the required performance. Harmonic emission induced by the complex system behavior is of great concern in the DCFC system. This paper proposes a harmonic emission model for the typical electric vehicle charger design, i.e., two-level active front end. The technique is based on the Fourier series method and the impedance model, which is able to reveal the harmonic current emission of DCFCs under different grid conditions. Time-domain simulations are presented subsequently to validate the proposed model.
</em></p>


</div>
</div>




# Educations
- *2022.07 - Present*, Ph.D., Battery and Power Electronics, Delft University of Technology, the Netherlands.
   - *Topic: Towards next-generation electric flight - Battery pack design and power electronics interface*
- *2020.09 - 2022.07*, M.Sc., Electrical Power Engineering, Delft University of Technology, the Netherlands.
   - Grade: 9.15/10.0 (cum laude)
   - *Thesis: IoT-based online harmonic emission estimation of DC fast chargers*
- *2021.09 - 2022.02*, Exchange Student, ETH Zürich, Switzerland.
   - *Project: Investigation of switching loss measurements of SiC MOSFETs*
- *2016.09 - 2020.06*, B.Sc., Electrical Engineering, Sichuan University, China.
   - Grade: 90.31/100 (outstanding graduate)
   - *Thesis: Research on the photovoltaic grid-connected control strategy*

# Honors and Awards
- *2025.06* 2nd Place, IEEE ITEC+EATS Student Design Competition
  - Design the high voltage/high-power distribution system for a regional (90 passenger) fully electric aircraft 
- *2025.02* 3rd Place, [IEEE VTS Challenge](https://vtsociety.org/membership/call-ideas-innovations-vehicle-propulsion-technologies-address-climate-change): Innovations in vehicle propulsion technologies to address climate change.

  - *Reconfigurable Hybrid Battery Pack for Future Electric Aircraft: Integrating High-Specific-Energy and Power Battery Types*

- *2019.11*  Ultra High Voltage Scholarship, China
- *2019.10*  Outstanding graduate, Sichuan University
- *2018.11*  National Scholarship, China 
- *2017.11*  National Scholarship, China 

