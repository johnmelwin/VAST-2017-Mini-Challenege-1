# 🌿 Unraveling Anomalous Traffic Dynamics in Boonsong Lekagul Nature Preserve 🌿
## VAST 2017: Mini-Challenge 1 🚗🔍

### Authors 🖋️
- **John Melwin Richard**  
- **Mahanand Adimulam**  
- **Niranjan Ambekar**  

---

## Abstract 📄
<span style="color:darkgreen">This study presents a comprehensive analysis of the interaction between vehicle traffic patterns and wildlife health within the Boonsong Lekagul Nature Preserve, specifically focusing on the impact on the Rose-Crested Blue Pipit bird species. The purpose is to unravel the effects of human vehicular activity on the preserve's delicate ecological balance.</span>

---

### Keywords 🔑
<span style="color:blue">Data Analysis, Visualization, Sense making</span>

---

## 1. Introduction 📖
<span style="color:darkred">The Boonsong Lekagul Nature Preserve, visited by local
residents and tourists faces an important challenge. There
are signs indicating a decrease in the number of nesting
pairs of the Rose-Crested Blue Pipit, a bird cherished for its
attractive feathers and melodious songs. There could be some
odd vehicle behaviours that seem inconsistent with typical
park visitation patterns which might affect the birds. This
study aims to analyze these vehicle behaviors over time,
shedding light on whether and how they might be disrupting
the preserve’s delicate ecosystem.</span>

---

## 2. Research Questions ❓
<span style="color:purple">
1. What are the predominant traffic flow patterns within the Boonsong Lekagul Nature Preserve?
2. What constitutes unusual vehicle behaviors within the Preserve?
3. How does vehicle data correlate with bird population changes, indicating human impact on avian habitats?
</span>

---

## 3. Dataset 🗂️
<span style="color:chocolate">To address this challenge, two key data sources are utilized:
Firstly, an extensive csv file with sensor-recorded vehicle
movements in the Boonsong Lekagul Nature Preserve, detailing timestamps, unique vehicle IDs, types of vehicles, and the
specific gates and sensors they pass. Secondly, a map of the
Preserve, visually depicting a 200x200 grid area, showcasing
roads, sensor placements, and important zones within the
Preserve. This dataset, previously employed in IEEE VAST
challenge submissions [1] and [2], yielded diverse solutions,
including spatio-temporal visualization and the utilization of
EventPad for glyph-based event representation respetively.</span>

---

## 4. Visualization Approach 📊
### 4.1 Visualizing by Vehicle Type 🚛
Initially, vehicles entering the preserve were categorized
based on axle count, facilitating an analysis of adherence
to preserve regulations. Sensor data at various checkpoints,
plotted against days over a year, generated six distinct plots for
each vehicle type. The y-axis represented checkpoints, while
the x-axis indicated days. Among these, the plot for vehicle
type-4 (4-axle trucks) exhibited a clear anomaly.
Per preserve regulations, only vehicles with a pass may
access checkpoints. However, a specific type-4 truck, lacking
a pass, repeatedly accessed checkpoints approximately biweekly, raising suspicions due to its deviation from normative
behavior. Figure 2 vehicle-type visualization distinctly marks
this type-4 truck as an anomalous case.
![Vehicle Type-4 Anomaly](Vehicle-type-4%20Anomaly.png)
_Figure 1: Vehicle Type-4 Anomaly_

### 4.2 Visualizing by Path 🛣️
Following the identification of type-4 vehicles as anomalous
in the previous analysis, tracing their path within the preserve
was the logical next step. Tracking these unauthorized type4 vehicles revealed a consistent bi-weekly pattern and also
revealed the vehicle-IDs. The typical route taken by the
anomalous truck was: entrance-3, gate-6, ranger-stop-6, gate5, general-gate-5, gate-3, and ranger-stop-3.
![Vehicle type-4 Anomaly](QGIS.png)  
_Figure 2: Vehicle Type-4 Anomaly_

### 4.3 Visualizing by Time ⏰
The final analytical step involved visualizing the anomalous
truck’s movements over time. Plotting the truck’s path on the
y-axis against various times of the day for vehicle type-4, as
shown in Figure 3, clearly indicated a pattern of unauthorized
access. Notably, all such incidents occurred after midnight and
lasted until early morning, intensifying suspicions. Figure 2
vividly illustrates these occurrences, highlighting the type-4
truck’s unauthorized gate access between 12 am and 6 am
![Visualize by Time](time.png)
_Figure 3: Visualize by Time_

---

## 5. Conclusion 🎓
<span style="color:green">After a coherent analysis, it was understood that the preserve
has regulations, and there is a pattern in vehicle behavior
that adheres to these regulations. However, an anomaly has
been noted in the form of different trucks of the same vehicle
type. These trucks access unauthorized gates without a pass,
following the same path bi-weekly, from after midnight until
early morning. The behavior of these trucks is suspicious
and may be a contributing factor in disturbing the preserve’s
ecosystem, addressing our second research question. One
hypothesis is that the rose-crested blue pipit, known for being
ground nesters, is disturbed by these trucks during the night,
potentially answering our third research question.
</span>

---

## References 📚
1. S. Zhang, D. Guo, Y. Zhu, and D. Wang, "VAST Challenge 2017: Mini-challenge 1,"...
2. M. A. Whiting et al., "VAST Challenge 2017: Mystery at the Wildlife Preserve,"...
