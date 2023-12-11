# Unraveling Anomalous Traffic Dynamics in Boonsong Lekagul Nature Preserve
## VAST 2017: Mini-Challenge 1

### Authors
- **John Melwin Richard**  
- **Mahanand Adimulam**  
- **Niranjan Ambekar**  

---

## Abstract
This study presents a comprehensive analysis of the interaction between vehicle traffic patterns and wildlife health within the Boonsong Lekagul Nature Preserve, specifically focusing on the impact on the Rose-Crested Blue Pipit bird species. The purpose is to unravel the effects of human vehicular activity on the preserve's delicate ecological balance. This was achieved by addressing three key research questions: identifying predominant traffic flow patterns within the preserve, defining unusual vehicle behaviors, and exploring the correlation between these factors and changes in the local bird population. The study's outcomes are expected to inform and influence future policies and actions aimed at protecting the Boonsong Lekagul Nature Preserve's diverse ecosystem, ensuring a sustainable coexistence of human and natural elements.

---

### Keywords
Data Analysis, Visualization, Sense making

---

## 1. Introduction
The Boonsong Lekagul Nature Preserve, visited by local residents and tourists, faces an important challenge. There are signs indicating a decrease in the number of nesting pairs of the Rose-Crested Blue Pipit, a bird cherished for its attractive feathers and melodious songs. There could be some odd vehicle behaviors that seem inconsistent with typical park visitation patterns which might affect the birds. This study aims to analyze these vehicle behaviors over time, shedding light on whether and how they might be disrupting the preserve's delicate ecosystem.

---

## 2. Research Questions
To strategically analyze this situation, we have formulated three research questions to arrive at a reasonable solution. The answers to these questions will serve as a solution to the challenge. The research questions are as follows:
1. What are the predominant traffic flow patterns within the Boonsong Lekagul Nature Preserve?
2. What constitutes unusual vehicle behaviors within the Preserve?
3. How does vehicle data correlate with bird population changes, indicating human impact on avian habitats?

---

## 3. Dataset
To address this challenge, two key data sources are utilized: Firstly, an extensive csv file with sensor-recorded vehicle movements in the Boonsong Lekagul Nature Preserve, detailing timestamps, unique vehicle IDs, types of vehicles, and the specific gates and sensors they pass. Secondly, a map of the Preserve, visually depicting a 200x200 grid area, showcasing roads, sensor placements, and important zones within the Preserve. The dataset is cleaned, pre-processed, and formatted for the analysis.

![Vehicle Type-4 Anomaly](Vehicle-type-4%20Anomaly.png)
_Figure 2: Vehicle Type-4 Anomaly_
_Figure 1: Heat Map of Unusual Vehicle Behaviour_

![Vehicle type-4 Anomaly](path/to/your/image/Vehicle-type-4_Anomaly.png)  
_Figure 2: Vehicle Type-4 Anomaly_

![Visualize by Time](Visualize%by%time.png)
_Figure 3: Visualize by Time_

---

## 4. Visualization Approach
### 4.1 Visualizing by Vehicle Type
Initially, vehicles entering the preserve were categorized based on axle count, facilitating an analysis of adherence to preserve regulations. Sensor data at various checkpoints, plotted against days over a year, generated six distinct plots for each vehicle type. The y-axis represented checkpoints, while the x-axis indicated days. Among these, the plot for vehicle type-4 (4-axle trucks) exhibited a clear anomaly.

Per preserve regulations, only vehicles with a pass may access checkpoints. However, a specific type-4 truck, lacking a pass, repeatedly accessed checkpoints approximately bi-weekly, raising suspicions due to its deviation from normative behavior. Figure-1's vehicle-type visualization distinctly marks this type-4 truck as an anomalous case.

### 4.2 Visualizing by Path
Following the identification of type-4 vehicles as anomalous in the previous analysis, tracing their path within the preserve was the logical next step. Tracking these unauthorized type-4 vehicles revealed a consistent bi-weekly pattern. The typical route taken by the anomalous truck was: entrance-3, gate-6, ranger-stop-6, gate-5, general-gate-5, gate-3, and ranger-stop-3.

### 4.3 Visualizing by Time
The final analytical step involved visualizing the anomalous truck's movements over time. Plotting the truck's path on the y-axis against various times of the day for vehicle type-4, as shown in figure-3, clearly indicated a pattern of unauthorized access. Notably, all such incidents occurred after midnight and lasted until early morning, intensifying suspicions. Figure-2's heat map vividly illustrates these occurrences, highlighting the type-4 truck's unauthorized gate access between 12 am and 6 am.

---

## 5. Conclusion
After analysis, it was understood that the preserve has regulations, and there is a pattern in vehicle behavior that adheres to these regulations. However, an anomaly has been noted in the form of different trucks of the same vehicle type. These trucks access unauthorized gates without a pass, following the same path bi-weekly, from after midnight until early morning. The behavior of these trucks is suspicious and may be a contributing factor in disturbing the preserve's ecosystem, addressing our second research question. One hypothesis is that the rose-crested blue pipit, known for being ground nesters, is disturbed by these trucks during the night, potentially answering our third research question.

---

## References
1. S. Zhang, D. Guo, Y. Zhu, and D. Wang, "VAST Challenge 2017: Mini-challenge 1," 2017 IEEE Conference on Visual Analytics Science and Technology (VAST), Phoenix, AZ, USA, 2017, pp. 249-250.
2. M. A. Whiting et al., "VAST Challenge 2017: Mystery at the Wildlife Preserve," 2017 IEEE Conference on Visual Analytics Science and Technology (VAST), Phoenix, AZ, USA, 2017, pp. 173-178.
