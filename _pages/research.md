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
- Case Studies on the Use of Amino Acids in the Geo-Energy Industry
- Development of Soft Sensor for Bottom Composition in Distillation Column
- Classification of Waste Products Using Transfer Learning
- Constrained Optimization of a Heat Exchanger using Python (SciPy)
- Plant Design for the Production of Ammonia from Isopentane
- Data-Driven Modeling and Parameter Optimization for Reactor Design

## Case Studies on the Use of Amino Acids in the Geo-Energy Industry

<figure>
  <img src="/assets/images/antitracer.png" width="1000px" alt="">
  <figcaption>Tracer release experiment in a global Oceananigans.jl configuration, simulating the enhancement of ocean alkalinity between Thailand and Indonesia.
</figcaption>
</figure>

This is a chapter in the book **Amino Acids Applications in the Geoenergy Industry** that discusses the role of amino acids as alternative green additives in the geoenergy and related carbon sequestration industry under the guidance of Dr. Cornelius Borecho Bavoh and Dr. Ato Fanyin-Martin at the Department of Chemical and Petrochemical Engineering at UMaT. Furthermore, the main challenges involved in the use of amino acids in the geoenergy industries are discussed.
* Discusses mechanisms of relevant amino acids and their possible commercialization in the oil and gas industry
* Addresses properties of amino acids that promises their use in green oil and gas chemistry
* Provides knowledge of the use of amino acids in several aspects of the geoenergy industry
* Clarifies the benefits and drawbacks of using amino acids in the oil and gas industry
* Provides real-world case studies on the use of amino acids in the oil and gas industry

Below is the abstract of my chapter:
**ABSTRACT**
This paper explores the application of amino acids in three critical industrial processes: hydration suppression in drilling, hydraulic fracturing, and corrosion inhibition. Amino acids offer promising solutions for improving wellbore stability, enhancing fluid performance, and reducing environmental impact across diverse industrial applications. In drilling operations, amino acids act as effective hydration suppressants, limiting clay swelling and improving mud formulation flexibility. In hydraulic fracturing, amino acid-based friction reducers enhance fracture propagation and increase hydrocarbon recovery rates, particularly in low-permeability gas reservoirs with high clay content. Additionally, amino acids serve as environmentally friendly corrosion inhibitors, replacing traditional hazardous compounds and ensuring regulatory compliance. Through collaborative efforts between academia, industry, and regulatory bodies, the widespread adoption of amino acids can advance sustainability and efficiency in industrial processes.

Related publications: Akuoko, S., Fanyin-Martin, A., (2025), Case Studies on the Use of Amino Acids in the Geo-Energy Industry, In C.B. Bavoh & K.A. Quainoo (Eds.), Amino Acids Applications in the Geoenergy Industry (pp.172-180). CRC Press. https://doi.org/10.1201/9781003502388

## Development of Soft Sensor for Bottom Composition in Distillation Column

<figure>
  <img src="/assets/images/hybrid_climate_modeling.png" width="1000px" alt="">
  <figcaption>A hybrid climate model combines a traditional dynamical core with machine-learned parameterizations.
</figcaption>
</figure>

Integrating machine learning (ML) with ocean modeling offers a promising path to improving the accuracy and efficiency of ocean simulations, and plays a central role in emerging hybrid climate modeling approaches that combine physics-based and data-driven components. My work focuses on developing ML-based parameterizations for ocean physical processes, using both offline and online approaches:

* **Offline learning:** ML models are trained on outputs from high-resolution simulations or observational datasets before being incorporated into the ocean model.
* **Online learning:** ML models are trained dynamically during the simulation itself, requiring the ocean model to be differentiable.

During my work with the [M2LInES Team](https://m2lines.github.io/), I focused on offline approaches to hybrid modeling. I began by diagnosing eddy fluxes from high-resolution MOM6 simulations using filtering and coarse-graining techniques. I then trained ML models on these offline datasets using PyTorch. To evaluate the model’s performance in an online setting, I integrated it into the MOM6 code base. 
However, offline-learned parameterizations often encounter numerical instability when coupled with the full model, highlighting the potential advantages of online approaches.

As part of the [DJ4Earth project](https://dj4earth.github.io/), I supervise students applying online learning techniques to improve ocean eddy parameterizations. In this approach, the machine-learned parameterization is trained alongside the simulation, requiring a differentiable ocean model with an adjoint. We implement this method using the ocean model Oceananigans, and train the ML models in Julia.

Related publications: [Balwada, ..., Loose et al.](https://doi.org/10.21105/jose.00241), JOSE (2024);
[Yu, ..., Loose et al.](https://proceedings.neurips.cc/paper_files/paper/2023/hash/45fbcc01349292f5e059a0b8b02c8c3f-Abstract-Datasets_and_Benchmarks.html), NeurIPS (2023)

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

My main contributions to the project were the design of a process flow diagram (PDF) using Visio, the development of the simulation of the processes using Aspen PLUS, while utilising its optimisation tools to optimize the process for a better yield and integrating it with Excel for economic analysis of the plant. I then designed a Methanator, a reactor that serves to convert the carbon dioxide produced into methane and water for recycling and finally using AutoCAD to help with the mechanical design of the reactor. This project culminated into my final year research project (undergraduate thesis) under the guidance of Dr. Emmanuel Godwin Ankudey. This project not only built my computational confidence but also enhanced my presentation, communication, collaboration, and review of articles skills. 

The project report and PowerPoint presentations can be accessed [here](https://github.com/sakuoko/Plant-Design-for-the-Production-of-Ammonia-from-Isopentane).

## Data-Driven Modeling and Parameter Optimization for Reactor Design

I am engaged with developing open-source software tools in Python and Julia to enable our Earth Science community to perform data analysis and modeling in an efficient and reproducible way. 
I have led the development of two open-source Python packages: [GCM-Filters](https://gcm-filters.readthedocs.io/en/latest/) and [ROMS-Tools](https://roms-tools.readthedocs.io/en/latest/).

<figure>
  <img src="/assets/images/roms_grid.png" alt="">
  <figcaption> 
A ROMS grid created with the open-source Python package ROMS-Tools.
</figcaption>
</figure>
`ROMS-Tools` is a Python package for creating the input files that are necessary to run a ROMS simulation. This includes creating a grid, tidal, boundary, and atmospheric forcings, initial conditions, and more! 

<figure>
  <img src="/assets/images/filter_intro.png" alt="">
  <figcaption> 
Filtering surface relative vorticity from a global 0.1 degree MOM6 simulation with the open-source Python package GCM-Filters.
</figcaption>
</figure>
`GCM-Filters` is a Python package that allows scientists to perform spatial filtering analysis in an easy, flexible, efficient, and reproducible way. `GCM-Filters` is designed to work with gridded data that is produced by General Circulation Models (GCMs) of ocean, weather, and climate. 
Check out [this presentation](https://noraloose.github.io/ams2022-talk) on GCM-Filters!

Related publications: [Loose et al.](https://doi.org/10.21105/joss.03947), JOSS (2022); 
[Grooms, Loose et al.](https://doi.org/10.1029/2021MS002552), JAMES (2021).

