---
title: "Projects"
layout: single
sitemap: true
permalink: /research/
author_profile: true
toc: true
toc_label: "Projects"
toc_icon: "gear"
toc_sticky: true
---

My work centres on the intersection of chemical engineering and advanced computational techniques, enabling me to optimize systems, reduce inefficiencies, and improve overall productivity. I am continuously seeking new opportunities to integrate cutting-edge technology into chemical engineering for impactful results. Current and past research projects include; the list is unordered and does not reflect project popularity or chronological order.
- XAI For Combined Cycle Power Plant
- Case Studies on the Use of Amino Acids in the Geo-Energy Industry
- Development of Soft Sensor for Bottom Composition in Distillation Column
- Classification of Waste Products Using Transfer Learning
- Constrained Optimization of a Heat Exchanger using Python (SciPy)
- Plant Design for the Production of Ammonia from Isopentane
- Data-Driven Modeling and Parameter Optimization for Reactor Design

## XAI For Combined Cycle Power Plant
<figure>
  <img src="/assets/images/Projects/project shap summary results.jpg" width="1000px" alt="">
  <figcaption>project shap summary results
</figcaption>
</figure>

In this project, I focused on improving the interpretability of predictive models using Explainable AI techniques. I explored the application of SHAP values to understand the contributions of individual features in a dataset from a combined cycle power plant. The parameters include atmospheric pressure (AP), atmospheric temperature (AT), vacuum pressure (V), relative humidity (RH), and power output (PE).

Full description and process are availale in the code found [here](https://github.com/sakuoko/XAI-For-Combined-Cycle-Power-Plant).

## Case Studies on the Use of Amino Acids in the Geo-Energy Industry

<figure>
  <img src="/assets/images/Projects/Amino Acids Applications in the Geoenergy Industry.jpeg" width="350px" height="500px" alt="">
  <figcaption>Book cover of Amino Acids Applications in the Geoenergy Industry
</figcaption>
</figure>

This research project forms part of the chapters in the book "**Amino Acids Applications in the Geoenergy Industry**" that discusses the role of amino acids as alternative green additives in the geoenergy and related carbon sequestration industry under the guidance of Dr. Cornelius Borecho Bavoh and Dr. Ato Fanyin-Martin at the Department of Chemical and Petrochemical Engineering at UMaT. Furthermore, the main challenges involved in the use of amino acids in the geoenergy industries are discussed.
* Discusses mechanisms of relevant amino acids and their possible commercialization in the oil and gas industry
* Addresses properties of amino acids that promises their use in green oil and gas chemistry
* Provides knowledge of the use of amino acids in several aspects of the geoenergy industry
* Clarifies the benefits and drawbacks of using amino acids in the oil and gas industry
* Provides real-world case studies on the use of amino acids in the oil and gas industry

Below is the abstract of my chapter:

**ABSTRACT**

This paper explores the application of amino acids in three critical industrial processes: hydration suppression in drilling, hydraulic fracturing, and corrosion inhibition. Amino acids offer promising solutions for improving wellbore stability, enhancing fluid performance, and reducing environmental impact across diverse industrial applications. In drilling operations, amino acids act as effective hydration suppressants, limiting clay swelling and improving mud formulation flexibility. In hydraulic fracturing, amino acid-based friction reducers enhance fracture propagation and increase hydrocarbon recovery rates, particularly in low-permeability gas reservoirs with high clay content. Additionally, amino acids serve as environmentally friendly corrosion inhibitors, replacing traditional hazardous compounds and ensuring regulatory compliance. Through collaborative efforts between academia, industry, and regulatory bodies, the widespread adoption of amino acids can advance sustainability and efficiency in industrial processes.

Related publications: Akuoko, S., Fanyin-Martin, A., (2025), Case Studies on the Use of Amino Acids in the Geo-Energy Industry, In C.B. Bavoh & K.A. Quainoo (Eds.), Amino Acids Applications in the Geoenergy Industry (pp.172-180). CRC Press. [https://doi.org/10.1201/9781003502388](https://doi.org/10.1201/9781003502388)

## Development of Soft Sensor for Bottom Composition in Distillation Column

<figure>
  <img src="/assets/images/Projects/Soft Sensor summary.jpg" width="1000px" alt="">
  <figcaption>An image showig the performance plots of the model used
</figcaption>
</figure>

It is often necessary to find the top purity and the bottom product purity of a distillation column. But the problem in the industry is that it is not always possible to put a composition analyzer at the bottom product or at the distillate. Why? This is because analyzers are too costly and not always economically feasible to put a bottom analyzer. This was an industrial challenge I encountered at the Tema Oil Refinery, Ghana, as an intern in 2022. I proposed the use of a function to establish a relationship between the bottom product purity along with the help of column parameters, and then we can deploy the equation into a distributed control system, DCS where a plant operator or engineer can continuously see the analysis. I developed a **Soft Sensor**, which is nothing but an equation relating the bottom product purity with temperatures or other process parameters of the distillation column. With the help of machine learning using MATLAB, I successfully developed a model with a 98% validation accuracy as compared to what is normally done by laboratory analysis with gas chromatography and mass spectrometer. This completely eliminated the over 8 hours spent collecting samples in a day and over 2 hours spent analysing the samples in the laboratory.

The project codes can be located [here](https://github.com/sakuoko/Soft-sensor-development)

## Classification of Waste Products Using Transfer Learning

<figure>
  <img src="/assets/images/Projects/Evaluation plots of the model developed.jpg" width="1000px" alt="">
  <figcaption> Evaluation performance plots
</figcaption>
</figure>

In this study project, I applied Transfer Learning using a pre-trained model(VGG16) and fine-tuning to classify different types of waste products into organic and recyclable through the use of deep learning (DL) and convolutional neural networks (CNNs). This project aimed to automate waste sorting for improved recycling efficiency and environmental impacts. At the end of the project, I was able to develop a trained model that classifies wastes images into the different categories with a model validation accuracy of over 92%. Comparing the plots a&b to plots c&d, it can be deduced that the model performance increased after the fine tuning.

A detailed workflow of the whole process can be accessed via [here](https://github.com/sakuoko/Classification-of-Waste-Products-Using-Transfer-Learning/blob/main/Final%20Proj-Classify%20Waste%20Products%20Using%20TL%20FT.ipynb). This project was crucial to me as I earned an IBM Deep Learning with Pytorch, Keras, and Tensorflow with GenAI Professional Certificate [link](https://coursera.org/verify/professional-cert/WY9XFIXH3K23).

## Constrained Optimization of a Heat Exchanger using Python (SciPy)

<figure>
  <img src="/assets/images/Projects/Optimization of a Heat Exchanger result.jpg" alt="">
  <figcaption> 
Optimization of a Heat Exchanger result from the code 
</figcaption>
</figure>

In this study, I focused on optimization in engineering on improving the design of a heat exchanger. Heat exchangers are used in various industries to transfer heat between two or more fluids efficiently, but how can we design these heat exchangers better? I explored how to balance high performance, low cost, and minimal energy loss. This balance is essential because it can lead to significant savings, reduce energy use, and have a beneficial impact on the environment. I identified some of the various factors that influence the design, such as the size and shape of the heat exchanger, the material used, and the volume of the fluid that flows through it.

Using the optimization package available in SciPy, I was able to achieve optimal values for the outer diameter, wall thickness, flow rate, number of tubes, and an objective function value of -234824.76448735717. This outer diameter dimension influences the overall size and the space it occupies while the wall thickness and the tube thickness ensure the structural integrity of the tubes while influencing the thermal resistance of the tube material. Hence, a balance is needed to ensure the tubes are not too thin or too thick. An optimal value of the flow rate is necessary to ensure that enough fluid passes through the heat exchanger for efficient heat transfer without causing excessive pressure drop or requiring too powerful pump, which would increase operational costs. More tubes can also increase the heat transfer area but might also necessitate a larger shell size, leading to an increase in the complexity of the tube bundle assembly. The objective function value represents the quantitative assessment of the heat exchanger design by the optimization model. The value is the weighted sum of the negative heat transfer rate, the positive pressure drop, and material costs. The negative indicates a stronger performance in maximizing the heat transfer relative to penalties incurred from pressure drop and material costs. A more negative value is preferable as it indicates a higher heat transfer rate and lower undesired costs. This value quantifies the trade-offs made between these factors, where a more negative result suggests a design loser to the ideal balance as defined by the weights in the objective function.

The project code can be located [here](https://github.com/sakuoko/Optimization-of-a-Heat-Exchanger).

## Plant Design for the Production of Ammonia from Isopentane

<figure>
  <img src="/assets/images/Projects/Project summary.jpg" alt="">
  <figcaption> 
Process summary and my contriutions to the design project
</figcaption>
</figure>

Ammonia, which finds several uses in the fields of agriculture, health, textiles, hydrogen storage, energy, and many more, is one of the most successful chemicals to be discovered. From Ghana National Gas Company Limited (GNGC), an effluent gas, an Isopentane known for its potential use as an energy source, is being flared into the environment regardless of its negative impacts it may have on the community years to come. To tackle this, a 7 member group, including myself, was tasked to investigate the possibility of transforming the flared gas into a useful chemical, ammonia. Several known ammonia synthesis processes were looked at. We made selections of a combination of technologies that can contribute to a higher yield of ammonia while minimising carbon emissions.

My main contributions to the project were the design of a process flow diagram (PFD) using Visio, the development of the simulation of the processes using Aspen PLUS, while utilising its optimisation tools to optimize the process for a better yield and integrating it with Excel for economic analysis of the plant. I then designed a Methanator, a reactor that serves to convert the carbon dioxide produced into methane and water for recycling and finally using AutoCAD to help with the mechanical design of the reactor. This project culminated into my final year research project (undergraduate thesis) under the guidance of Dr. Emmanuel Godwin Ankudey. This project not only built my computational confidence but also enhanced my presentation, communication, collaboration, and review of articles skills. 

The project report and PowerPoint presentations can be accessed [here](https://github.com/sakuoko/Plant-Design-for-the-Production-of-Ammonia-from-Isopentane).

## Data-Driven Modeling and Parameter Optimization for Reactor Design

<figure>
  <img src="/assets/images/Projects/rxn for data modeling.jpg" alt="">
  <figcaption> 
Plot summary of the project
</figcaption>
</figure>

In this project, I demonstrated how to determine the rate at which a secret chemical, A reacts to form another chemical, B, after several experiments in a batch reactor. I did this by collecting concentration data for A at different time intervals. Using Python as the main tool, I successfully settled on two methods, namely: Least Squared Method(LSM) and optimize tool in Scipy. It took me several iterations to get the model of the best fit using  LSM. However, a simple run to get the best model to determine the rate constant, k using Scipy. Through this project, I learned that:

* Getting the best model that represents your data involves the use of your engineering intuition to identify the most suitable model based on the underlying physics and characteristics of the system.
* Analyse the data visually to estimate parameters accurately. Selecting appropriate initial parameters can significantly influence the fitting process and improve convergence.

Check out the code and details [here](https://github.com/sakuoko/Data-Driven-Modeling-and-Parameter-Optimization-for-Reactor-Design)

