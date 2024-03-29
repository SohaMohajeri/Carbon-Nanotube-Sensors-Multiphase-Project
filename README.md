<div align="center"> 
  
# Carbon Nanotube Sensors Multiphase Project

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/69224996/97274426-e024d700-17f1-11eb-8dab-f56d0c2ade72.png" >
</div>
<br />

<div align="justify">
This is a senior project carried out at the University of Washington to create data models that successfully predict the sensitivity and detection capability of modified carbon nanotube sensors.

In this multiphase project, we used five datasets including Metal-CNT Sensor Dataset, Research Centers-Countries Dataset, Pt-CNT Sensor Dataset, Sulfur Cathode Properties Dataset and CNT Synthesis Dataset. These datasets were obtained from the chemical experiments and research carried out at the University of Washington.

Carbon nanotubes (CNTs) are extremely promising candidates as high-performance sensors for the electrochemical detection of dissolved ions in aqueous media. In the first phase of this project, CNTs were modified with noble metals such as Gold, Platinum, Palladium, Silver, Ruthenium and Iridium to further improve the sensitivity of nanotubes. Furthermore, the sensitivity of CNTs was measured as a nonlinear function of operating parameters including CNTs diameter, CNTs length, CNTs density, deposition potential, deposition time, thickness of the deposited metal, catalyst concentration, and the operating temperature. The first purpose of this phase of project was to find out which factors were more important to obtain a higher sensitivity. The second purpose was to implement several machine learning algorithms to predict the sensitivity and compare the results to discover which algorithm works better for the dataset. 

In the second phase, the research carried out at different research centers in various countries was gathered and visualized to determine the reported sensitivities of sensors which could detect sulfide ions similar to our developed CNT-based sensors.

In the third phase, the best preforming Pt-CNT sensor that was fabricated in the first phase with the highest sensitivity for the electrochemical detection of dissolved sulfide ions in aqueous media was used. The capability of this particular Pt-CNT sensor for the detection of nitrate and chloride ions was evaluated. This capability was measured as a function of the type of functional groups, type of surfactant, detection_technique, concentration of ions, NaCl and distilled water. The first purpose of this phase of the project was to determine the factors that were more crucial for enhancing the nitrate and chloride detection capability of Pt-CNT sensor. The second purpose was to implement several machine learning algorithms to predict the detection capability and determine the best performing algorithm for the dataset.

In the fourth phase, we obtained the properties of the applied sulfur cathodes from the manufacturers as a data frame with 19 columns. These columns demonstrated the physical and chemical properties of sulfide cathode materials including their thermal conductivity, formation energy, band gap, density, ionic conductivity and so forth. In the First step, we used Principal Component Analysis (PCA) as a dimensionality-reduction technique. In order to do this, we standardized the data, found the optimal number of components which captured the greatest amount of variance, and performed PCA with the chosen number of components. In the second step, we segmented this data into separate clusters by KMeans Clustering. For this purpose, we tried to find the number of optimal clusters by elbow method, performed clustering with the chosen number of clusters, visualized clusters by components, and added PCA and K-means results to the dataframe. Finally, we grouped the sulfur cathode materials to separate classes with respect to their crystalline structure.

In the fifth phase, we synthesized carbon nanotubes by Chemical Vapor Deposition which is the most widely used method for the production of carbon nanotubes, and fabricated three types of single-wall carbon nanotubes including armchair, zig-zag and chiral as well as two types of multi-wall carbon nanotubes including Russian and Parchment. In this process, we recorded the growth temperature, gas flow rate, wall thickness and deposited mass. Finally, as the dimension of the recorded data was not high, we used K-Nearest Neighbors (KNN) algorithm for the classification and prediction of different types of carbon nanotubes.

</div>
