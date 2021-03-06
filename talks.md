---
layout: default
title: 'Climate Change: How Can AI Help?'
description: ICML 2019 Workshop Accepted Work
---
Works are submitted to one of three tracks: [Research](#Research-Track), [Deployed](#Deployed-Track), or [Ideas](#Ideas-Track). The number is for the poster session, and Spotlight: (time) indicates if the work will be presented as a spotlight talk at the indicated time. 

## Research Track

### (1) Policy Search with Non-uniform State Representations for Environmental Sampling  [pdf](./CameraReady/35/Submission/icml2019_workshop.pdf)

*Sandeep Manjanna (McGill University); Herke van Hoof (University of Amsterdam); Gregory Dudek (McGill University)*

<details>
<summary>
  Abstract: (click to expand)
</summary>

Surveying fragile ecosystems like coral reefs is important to monitor the effects of climate change. We present an adaptive sampling technique that  generates efficient trajectories covering hotspots in the region of interest at a high rate. A key feature of our sampling algorithm is the ability to generate action plans for any new hotspot distribution using the parameters learned on other similar looking distributions. </details>


### (2) Modelling GxE with historical weather information improves genomic prediction in new environments

*Jussi Gillberg (Aalto University); Pekka Marttinen (Aalto University); Hiroshi Mamitsuka (Kyoto University); Samuel Kaski (Aalto University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Interaction between the genotype and the environment ($G \times E$) has a strong impact on the yield of major crop plants. Recently $G \times E$ has been predicted from environmental and genomic covariates, but existing works have not considered generalization to new environments and years without access to in-season data. We study \textit{in silico} the viability of $G \times E$ prediction under realistic constraints. We show that the environmental response of a new generation of untested Barley cultivars can be predicted in new locations and years using genomic data, machine learning and historical weather observations. Our results highlight the need for models of $G \times E$: non-linear effects clearly dominate linear ones and the interaction between the soil type and daily rain is identified as the main driver for $G \times E$. Our study implies that genomic selection can be used to capture the yield potential in $G \times E$ effects for future growth seasons, providing a possible means to achieve yield improvements. $G \times E$ models are also needed to select for varieties that react favourably to the altering climate conditions. For this purpose, the historical weather observations could be replaced by climate simulations to study the yield potential under various climate scenarios.This abstract summarizes the findings of a recently published article <anonymised>. </details>


### (3) Machine Learning empowered Occupancy Sensing for Smart Buildings

*Han Zou (UC Berkeley); Hari Prasanna Das  (UC Berkeley ); Jianfei Yang (Nanyang Technological University); Yuxun Zhou (UC Berkeley); Costas Spanos  (UC Berkeley)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Over half of the global electricity consumption is attributed to buildings, which are often operated poorly from an energy perspective. Significant improvements in energy efficiency can be achieved via intelligent building control techniques. To realize such advanced control schemes, accurate and robust occupancy information is highly valuable. In this work, we present a cutting-edge WiFi sensing platform and state-of-the-art machine learning methods to address longstanding occupancy sensing challenges in smart buildings. Our systematic solution provides comprehensive fine-grained occupancy information in a non-intrusive and privacy-preserving manner, which facilitates eco-friendly and sustainable buildings. </details>


### (4) Focus and track: pixel-wise spatio-temporal hurricane tracking

*Sookyung Kim (Lawrence Livermore National Laboratory); Sunghyun  Park (Korea University); Sunghyo Chung (Korea University); Yunsung Lee (Korea University); Hyojin Kim (LLNL); Joonseok Lee (Google Research); Jaegul Choo (Korea University); Mr Prabhat (Lawrence Berkeley National Laboratory)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

We tackle extreme climate event tracking problem. It has unique challenges to other visual object tracking problems, including wider range of spatio-temporal dynamics, blur boundary of the target, and shortage of labeled dataset. In this paper, we propose a simple but robust end-to-end model based on multi-layered ConvLSTM, suitable for the climate event tracking problem. It first learns to imprint location and appearance of the target at the first frame with one-shot auto-encoding fashion, and then, the learned feature is consumed by the tracking module to track the target in subsequent time frames. To tackle the data shortage problem, we propose data augmentation based on Social GAN. Extensive experiments show that the proposed framework significantly improves tracking performance on hurricane tracking task over several state-of-the-art methods. </details>


### (5) Recovering the parameters underlying the Lorenz-96 chaotic dynamics

*Soukayna Mouatadid (University of Toronto); Pierre Gentine (Columbia University); Wei Yu (University of Toronto); Steve Easterbrook (University of Toronto)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Climate projections suffer from uncertain equilibrium climate sensitivity. The reason behind this uncertainty is the resolution of global climate models, which is too coarse to resolve key processes such as clouds and convection. These processes are approximated using heuristics in a process called parameterization. The selection of these parameters can be subjective, leading to significant uncertainties in the way clouds are represented in global climate models. Here, we explore three deep network algorithms to infer these parameters in an objective and data-driven way. We compare the performance of a fully-connected network, a one-dimensional and, a two-dimensional convolutional networks to recover the underlying parameters of the Lorenz-96 model, a non-linear dynamical system that has similar behavior to the climate system. </details>


### (6) Using Bayesian Optimization to Improve Solar Panel Performance by Developing Antireflective, Superomniphobic Glass

*Sajad Haghanifar (University of Pittsburgh); Bolong Cheng (SigOpt); Mike Mccourt (SigOpt); Paul Leu (University of Pittsburgh)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Photovoltaic solar panel efficiency is dependent on photons transmitting through the glass sheet covering and into the crystalline silicon solar cells within.  However, complications such as soiling and light reflection degrade performance. Our goal is to identify a fabrication process to produce glass which promotes photon transmission and is superomniphobic (repels fluids), for easier cleaning. In this paper, we propose adapting Bayesian optimization to efficiently search the space of possible glass fabrication strategies; in this search we balance three competing objectives (transmittance, haze and oil contact angle). We present the glass generated from this Bayesian optimization strategy and detail its properties relevant to photovoltaic solar power. </details>


### (7) A quantum mechanical approach for data assimilation in climate dynamics

*Dimitrios Giannakis (Courant Institute of Mathematical Sciences, New York University); Joanna Slawinska (University of Wisconsin-Milwaukee); Abbas Ourmazd (University of Wisconsin-Milwaukee)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

A framework for data assimilation in climate dynamics is presented, combining aspects of quantum mechanics, Koopman operator theory, and kernel methods for machine learning. This approach adapts the Dirac-von Neumann formalism of quantum dynamics and measurement to perform data assimilation (filtering) of climate dynamics, using the Koopman operator governing the evolution of observables as an analog of the Heisenberg operator in quantum mechanics, and a quantum mechanical density operator to represent  the data assimilation state. The framework is implemented in a fully empirical, data-driven manner, using kernel methods for machine learning to represent the evolution and measurement operators via matrices in a basis learned from time-ordered observations. Applications to data assimilation of the Nino 3.4 index for the El Nino Southern Oscillation (ENSO) in a comprehensive climate model show promising results. </details>


### (8) Data-driven Chance Constrained Programming based Electric Vehicle Penetration Analysis

*Di Wu (McGill); Tracy Cui (Google NYC); Doina Precup (McGill University); Benoit Boulet (McGill)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Transportation electrification has been growing rapidly in recent years. The adoption of electric vehicles (EVs) could help to release the dependency on oil and reduce greenhouse gas emission. However, the increasing EV adoption will also impose a high demand on the power grid and may jeopardize the grid network infrastructures. For certain high EV penetration areas, the EV charging demand may lead to transformer overloading at peak hours which makes the maximal EV penetration analysis an urgent problem to solve. This paper proposes a data-driven chance constrained programming based framework for maximal EV penetration analysis. Simulation results are presented for a real-world neighborhood level network. The proposed framework could serve as a guidance for utility companies to schedule infrastructure upgrades. </details>


### (9) (Spotlight: 4:30PM) Machine Learning for AC Optimal Power Flow

*Neel Guha (Carnegie Mellon University); Zhecheng Wang (Stanford University); Arun Majumdar (Stanford University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

We explore machine learning methods for AC Optimal Powerflow (ACOPF) - the task of optimizing power generation in a transmission network according while respecting physical and engineering constraints. We present two formulations of ACOPF as a machine learning problem: 1) an end-to-end prediction task where we directly predict the optimal generator settings, and 2) a constraint prediction task where we predict the set of active constraints in the optimal solution. We validate these approaches on two benchmark grids.    </details>


### (10)  (Spotlight: 2:50PM) Targeted Meta-Learning for Critical Incident Detection in Weather Data

*Mohammad Mahdi Kamani (The Pennsylvania State University); Sadegh Farhang (Pennsylvania State University); Mehrdad Mahdavi (Penn State); James Z Wang (The Pennsylvania State University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Due to imbalanced or heavy-tailed  nature of weather- and climate-related datasets, the performance of standard deep learning models significantly deviates from their expected behavior on test data. Classical methods to address these  issues are mostly data or application dependent, hence burdensome to tune. Meta-learning approaches, on the other hand, aim to learn hyperparameters in the learning process using different objective functions on training and validation data. However, these methods suffer from high computational complexity and are not scalable to large datasets. In this paper, we aim to apply a novel framework named as targeted meta-learning to rectify this issue, and show its efficacy in dealing with the aforementioned biases in datasets. This framework employs a small, well-crafted target dataset that resembles the desired nature of test data in order to guide the learning process in a coupled manner. We empirically show that this framework can overcome the bias issue, common to weather-related datasets, in a bow echo detection case study. </details>


### (11) ClimateNet: Bringing the power of Deep Learning to weather and climate sciences via open datasets and architectures

*Karthik  Kashinath (Lawrence Berkeley National Laboratory); Mayur Mudigonda (UC Berkeley); Kevin Yang (UC Berkeley); Jiayi Chen (UC Berkeley); Annette Greiner (Lawrence Berkeley National Laboratory); Mr Prabhat (Lawrence Berkeley National Laboratory)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Pattern recognition tasks such as classification, object detection and segmentation have remained challenging problems in the weather and climate sciences. While there exist many empirical heuristics for detecting weather patterns and extreme events, the disparities between the output of these different methods even for a single event are large and often difficult to reconcile. Given the success of Deep Learning in tackling similar problems in computer vision, we advocate a DL-based approach. However, DL works best in the context of supervised learning, when labeled datasets are readily available. Reliable, labeled training data is scarce in climate science. `ClimateNet' is an effort to solve this problem by creating open, community-sourced expert-labeled datasets that capture information pertaining to class or pattern labels, bounding boxes and segmentation masks. In this paper we present the motivation, design and status of the ClimateNet dataset and associated model architecture. </details>


### (12) Improving Subseasonal Forecasting in the Western U.S. with Machine Learning

*Paulo Orenstein (Stanford); Jessica Hwang (Stanford); Judah Cohen (AER); Karl Pfeiffer (AER); Lester Mackey (Microsoft Research New England)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Water managers in the western United States (U.S.) rely on longterm forecasts of temperature and precipitation to prepare for droughts and other wet weather extremes. To improve the accuracy of these long-term forecasts, the Bureau of Reclamation and the National Oceanic and Atmospheric Administration (NOAA) launched the Subseasonal Climate Forecast Rodeo, a year-long real-time forecasting challenge, in which participants aimed to skillfully predict temperature and precipitation in the western U.S. two to four weeks and four to six weeks in advance. We present and evaluate our machine learning approach to the Rodeo and release our SubseasonalRodeo dataset, collected to train and evaluate our forecasting system. Our predictive system is an ensemble of two regression models, and exceeds that of the top Rodeo competitor as well as the government baselines for each target variable and forecast horizon. </details>


### (13) Unsupervised Temporal Clustering to Monitor the Performance of Alternative Fueling Infrastructure

*Kalai Ramea (PARC)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Zero Emission Vehicles (ZEV) play an important role in the decarbonization of the transportation sector. For a wider adoption of ZEVs, providing a reliable infrastructure is critical. We present a machine learning approach that uses unsupervised temporal clustering algorithm along with survey analysis to determine infrastructure performance and reliability of alternative fuels. We illustrate this approach for the hydrogen fueling stations in California, but this can be generalized for other regions and fuels.  </details>


### (14) A Flexible Pipeline for Prediction of Tropical Cyclone Paths

*Niccolo Dalmasso (Carnegie Mellon University); Robin Dunn (Carnegie Mellon University); Benjamin LeRoy (Carnegie Mellon University); Chad Schafer (Carnegie Mellon University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Hurricanes and, more generally, tropical cyclones (TCs) are rare, complex natural phenomena of both scientific and public interest. The importance of understanding TCs in a changing climate has increased as recent TCs have had devastating impacts on human lives and communities. Moreover, good prediction and understanding about the complex nature of TCs can mitigate some of these human and property losses. Though TCs have been studied from many different angles, more work is needed from a statistical approach of providing prediction regions. The current state-of-the-art in TC prediction bands comes from the National Hurricane Center at NOAA, whose proprietary model provides "cones of uncertainty" for TCs through an analysis of historical forecast errors. The contribution of this paper is twofold. We introduce a new pipeline that encourages transparent and adaptable prediction band development by streamlining cyclone track simulation and prediction band generation. We also provide updates to existing models and novel statistical methodologies in both areas of the pipeline respectively.  </details>


### (15) Mapping land use and land cover changes faster and at scale with deep learning on the cloud

*Zhuangfang Yi (Development Seed); Drew Bollinger (Development Seed); Devis Peressutti (Sinergise)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Policymakers rely on Land Use and Land Cover (LULC) maps for evaluation and planning. They use these maps to plan climate-smart agriculture policy, improve housing resilience (to earthquakes or other natural disasters), and understand how to grow commerce in small communities. A number of institutions have created global land use maps from historic satellite imagery. However, these maps can be outdated and are often inaccurate, particularly in their representation of developing countries. We worked with the European Space Agency (ESA) to develop a LULC deep learning workflow on the cloud that can ingest Sentinel-2 optical imagery for a large scale LULC change detection. It’s an end-to-end workflow that sits on top of two comprehensive tools, SentinelHub, and eo-learn, which seamlessly link earth observation data with machine learning libraries. It can take in the labeled LULC and associated AOI in shapefiles, set up a task to fetch cloud-free, time series imagery stacks within the defined time interval by the users. It will pair the satellite imagery tile with it’s labeled LULC mask for the supervised deep learning model training on the cloud. Once a well-performing model is trained, it can be exported as a Tensorflow/Pytorch serving docker image to work with our cloud-based model inference pipeline. The inference pipeline can automatically scale with the number of images to be processed.  Changes in land use are heavily influenced by human activities (e.g. agriculture, deforestation, human settlement expansion) and have been a great source of greenhouse gas emissions. Sustainable forest and land management practices vary from region to region, which means having flexible, scalable tools will be critical. With these tools, we can empower analysts, engineers, and decision-makers to see where contributions to climate-smart agricultural, forestry and urban resilience programs can be made.  </details>


### (16) Achieving Conservation of Energy in Neural Network Emulators for Climate Modeling

*Tom G Beucler (Columbia University & UCI); Stephan Rasp (Ludwig-Maximilian University of Munich); Michael Pritchard (UCI); Pierre Gentine (Columbia University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Artificial neural-networks have the potential to emulate cloud processes with higher accuracy than the semi-empirical emulators currently used in climate models. However, neural-network models do not intrinsically conserve energy and mass, which is an obstacle to using them for long-term climate predictions. Here, we propose two methods to enforce linear conservation laws in neural-network emulators of physical models: Constraining (1) the loss function or (2) the architecture of the network itself. Applied to the emulation of explicitly-resolved cloud processes in a prototype multi-scale climate model, we show that architecture constraints can enforce conservation laws to satisfactory numerical precision, while all constraints help the neural-network better generalize to conditions outside of its training set, such as global warming.  </details>


### (17) The Impact of Feature Causality on Normal Behaviour Models for SCADA-based Wind Turbine Fault Detection

*Telmo Felgueira (IST)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

The cost of wind energy can be reduced by using SCADA data to detect faults in wind turbine components. Normal behavior models are one of the main fault detection approaches, but there is a lack of work in how different input features affect the results. In this work, a new taxonomy based on the causal relations between the input features and the target is presented. Based on this taxonomy, the impact of different input feature configurations on the modelling and fault detection performance is evaluated. To this end, a framework that formulates the detection of faults as a classification problem is also presented. </details>


### (18) Predicting CO2 Plume Migration using Deep Neural Networks

*Gege Wen (Stanford University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Carbon capture and sequestration (CCS) is an essential climate change mitigation technology for achieving the 2 degree C target. Numerical simulation of CO2 plume migration in the subsurface is a prerequisite to effective CCS projects. However, stochastic high spatial resolution simulations are currently limited by computational resources. We propose a deep neural network approach to predict the CO2 plume migration in high dimensional systems with complex geology. Upon training, the network is able to give accurate predictions that are 6 orders of magnitude faster than traditional numerical simulators. This approach can be easily adopted to history-matching and uncertainty analysis problems to support the scale-up of CCS deployment. </details>


### (19) (Spotlight: 4:20PM) Truck Traffic Monitoring with Satellite Images

*Lynn Kaack (ETH Zurich); George H Chen (Carnegie Mellon University); Granger Morgan (Carnegie Mellon University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

The road freight sector is responsible for a large and growing share of greenhouse gas emissions, but reliable data on the amount of freight that is moved on roads in many parts of the world are scarce.  Many low- and middle-income countries have limited ground-based traffic monitoring and freight surveying activities. In this proof of concept, we show that we can use an object detection network to count trucks in satellite images and predict average annual daily truck traffic from those counts. We describe a complete model, test the uncertainty of the estimation, and discuss the transfer to developing countries. </details>


### (20) (Spotlight: 2:40PM) Evaluating aleatoric and epistemic uncertainties of time series deep learning models for soil moisture predictions

*Chaopeng Shen (Pennsylvania State University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Soil moisture is an important variable that determines floods, vegetation health, agriculture productivity, and land surface feedbacks to the atmosphere, etc.. The recently available satellite-based observations give us a unique opportunity to directly build data-driven models to predict soil moisture instead of using land surface models, but previously there was no uncertainty estimate. We tested Monte Carlo dropout with an aleatoric term (MCD+A) for our long short-term memory models for this problem, and ask if the uncertainty terms behave as they were argued to. We show that MCD+A indeed gave a good estimate of our predictive error, provided we tune a hyperparameter and use a representative training dataset. The aleatoric term responded strongly to observational noise and the epistemic term clearly acted as a detector for physiographic dissimilarity from the training data. However, when the training and test data are characteristically different, the aleatoric term could be misled, undermining its reliability. We will also discuss some of the major challenges for which we anticipate the geoscientific communities will need help from computer scientists in applying AI to climate or hydrologic modeling. </details>


### (21) (Spotlight: 2:30PM) Detecting anthropogenic cloud perturbations with deep learning

*Duncan Watson-Parris (University of Oxford); Sam Sutherland (University of Oxford); Matthew Christensen (University of Oxford); Anthony Teh (University of Oxford); Dino Sejdinovic (University of Oxford); Philip Stier (University of Oxford)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

One of the most pressing questions in climate science is that of the effect of anthropogenic aerosol on the Earth's energy balance. Aerosols provide the `seeds' on which cloud droplets form, and changes in the amount of aerosol available to a cloud can change its brightness and other physical properties such as optical thickness and spatial extent. Clouds play a critical role in moderating global temperatures and small perturbations can lead to significant amounts of cooling or warming. Uncertainty in this effect is so large it is not currently known if it is negligible, or provides a large enough cooling to largely negate present-day warming by CO2. This work uses deep convolutional neural networks to look for two particular perturbations in clouds due to anthropogenic aerosol and assess their properties and prevalence, providing valuable insights into their climatic effects. </details>


### (22) Data-driven surrogate models for climate modeling: application of echo state networks, RNN-LSTM and ANN to the multi-scale Lorenz system as a test case

*Ashesh K Chattopadhyay (Rice University); Pedram  Hassanzadeh (Rice University); Devika  Subramanian (Rice University); Krishna Palem (Rice University); Charles Jiang (Rice University); Adam  Subel (Rice University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Understanding the effects of climate change relies on physics driven computationally expensive climate models which are still imperfect owing to ineffective subgrid scale parametrization. An effective way to treat these ineffective parametrization of largely uncertain subgrid scale processes are data-driven surrogate models with machine learning techniques. These surrogate models train on observational data capturing either the embed- dings of their (subgrid scale processes’) underlying dynamics on the large scale processes or to simulate the subgrid processes accurately to be fed into the large scale processes. In this paper an extended version of the Lorenz 96 system is studied, which consists of three equations for a set of slow, intermediate, and fast variables, providing a fitting prototype for multi-scale, spatio-temporal chaos, and in particular, the complex dynamics of the climate system. In this work, we have built a data-driven model based on echo state net- works (ESN) aimed, specifically at climate modeling. This model can predict the spatio-temporal chaotic evolution of the Lorenz system for several Lyapunov timescales. We show that the ESN model outperforms, in terms of the prediction horizon, a deep learning technique based on recurrent neural network (RNN) with long short-term memory (LSTM) and an artificial neural network by factors between 3 and 10. The results suggest that ESN has the potential for being a powerful method for surrogate modeling and data-driven prediction for problems of interest to the climate community. </details>


### (23) Learning Radiative Transfer Models for Climate Change Applications in Imaging Spectroscopy

*Shubhankar V Deshpande (Carnegie Mellon University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

According to a recent investigation, an estimated 33-50% of the world's coral reefs have undergone degradation, believed to be as a result of climate change. A strong driver of climate change and the subsequent environmental impact are greenhouse gases such as methane. However, the exact relation climate change has to the environmental condition cannot be easily established. Remote sensing methods are increasingly being used to quantify and draw connections between rapidly changing climatic conditions and environmental impact. A crucial part of this analysis is processing spectroscopy data using radiative transfer models (RTMs) which is a computationally expensive process and limits their use with high volume imaging spectrometers. This work presents an algorithm that can efficiently emulate RTMs using neural networks leading to a multifold speedup in processing time, and yielding multiple downstream benefits. </details>


### (24)  (Spotlight: 4:40PM) Planetary Scale Monitoring of Urban Growth in High Flood Risk Areas

*Christian F Clough (Planet); Ramesh Nair (Planet); Gopal Erinjippurath (Planet); Matt George (Planet); Jesus Martinez Manso (Planet)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Climate  change  is  increasing  the  incidence of flooding. Many areas in the developing world are experiencing strong population growth but lack adequate urban planning. This represents a significant humanitarian risk. We explore the use of high-cadence satellite imagery provided by Planet, who’s flock of over one hundred ’Dove’ satellites image the entire earth’s landmass everyday at 3-5m resolution. We use a deep learning-based computer vision approach to measure flood-related humanitarian risk in 5 cities in Africa. </details>


### (25) Efficient Multi-temporal and In-season Crop Mapping with Landsat Analysis Ready Data via Long Short-term Memory Networks

*Jinfan Xu (Zhejiang University); Renhai Zhong (Zhejiang University); Jialu Xu (Zhejiang University); Haifeng Li (Central South University); Jingfeng Huang (Zhejiang University); Tao Lin (Zhejiang University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Globe crop analysis from plentiful satellite images yields state-of-the-art results about estimating climate change impacts on agriculture with modern machine learning technology. Generating accurate and timely crop mapping across years remains a scientific challenge since existing non-temporal classifiers are hardly capable of capturing complicated temporal links from multi-temporal remote sensing data and adapting to interannual variability. We developed an LSTM-based model trained by previous years to distinguish corn and soybean for the current year. The results showed that LSTM outperformed random forest baseline in both in-season and end-of-the-season crop type classification. The improved performance is a result of the cumulative effect of remote sensing information that has been learned by LSTM model structure. The work provides a valuable opportunity for estimating the impact of climate change on crop yield and early warning of extreme weather events in the future. </details>


## Deployed Track

### (26) Autopilot of Cement Plants for Reduction of Fuel Consumption and Emissions

*Prabal Acharyya (Petuum Inc); Sean D Rosario (Petuum Inc); Roey Flor (Petuum Inc); Ritvik Joshi (Petuum Inc); Dian Li (Petuum Inc); Roberto Linares (Petuum Inc); Hongbao Zhang (Petuum Inc)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

The cement manufacturing industry is an essential component of the global economy and infrastructure. However, cement plants inevitably produce hazardous air pollutants, including greenhouse gases, and heavy metal emissions as byproducts of the process. Byproducts from cement manufacturing alone accounts for approximately 5% of global carbon dioxide (CO2) emissions. We have developed "Autopilot" - a machine learning based Software as a Service (SaaS) to learn manufacturing process dynamics and optimize the operation of cement plants - in order to reduce the overall fuel consumption and emissions of cement production.  Autopilot is able to increase the ratio of alternative fuels (including biowaste and tires) to Petroleum coke, while optimizing operation of pyro, the core process of cement production that includes the preheater, kiln and cooler. Emissions of gases such as NOx and SOx, and heavy metals such as mercury and lead which are generated through burning petroleum coke can be reduced through the use of Autopilot. Our system has been proven to work in real world deployments and an analysis of cement plant performance with Autopilot enabled shows energy consumption savings and a  decrease of up to 28,000 metric tons of CO2 produced per year. </details>


### (27) (Spotlight: 10:10AM) Towards a Sustainable Food Supply Chain Powered by Artificial Intelligence

*Volodymyr Kuleshov (Stanford University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

About 30-40% of food produced worldwide is wasted. This puts a severe strain on the environment and represents a $165B loss to the US economy. This paper explores how artificial intelligence can be used to automate decisions across the food supply chain in order to reduce waste and increase the quality and affordability of food. We focus our attention on supermarkets — combined with downstream consumer waste, these contribute to 40% of total US food losses — and we describe an intelligent decision support system for supermarket operators that optimizes purchasing decisions and minimizes losses. The core of our system is a model-based reinforcement learn- ing engine for perishable inventory management; in a real-world pilot with a US supermarket chain, our system reduced waste by up to 50%. We hope that this paper will bring the food waste problem to the attention of the broader machine learning research community. </details>


### (28)  PVNet: A LRCN Architecture for Spatio-Temporal Photovoltaic Power Forecasting from Numerical Weather Prediction

*Johan Mathe (Frog Labs)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Photovoltaic (PV) power generation has emerged as one of the leading renewable energy sources. Yet, its production is characterized by high uncertainty, being dependent on weather conditions like solar irradiance and temperature. Predicting PV production, even in the 24-hour forecast, remains a challenge and leads energy providers to left idling - often carbon-emitting - plants. In this paper, we introduce a Long-Term Recurrent Convolutional Network using Numerical Weather Predictions (NWP) to predict, in turn, PV production in the 24-hour and 48-hour forecast horizons. This network architecture fully leverages both temporal and spatial weather data, sampled over the whole geographical area of interest. We train our model on a prediction dataset from the National Oceanic and Atmospheric Administration (NOAA) to predict spatially aggregated PV production in Germany. We compare its performance to the persistence model and state-of-the-art methods. </details>


### (29) Finding Ship-tracks Using Satellite Data to Enable Studies of Climate and Trade Related Issues

*Tianle Yuan (NASA)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Ship-tracks appear as long winding linear features in satellite images and are produced by aerosols from ship exhausts changing low cloud properties. They are one of the best examples of aerosol-cloud interaction experiments, which is currently the largest source of uncertainty in our understanding of climate forcing.  Manually finding ship-tracks from satellite data on a large-scale is prohibitively costly while a large number of samples are required to better understand aerosol-cloud interactions. Here we train a deep neural network to automate finding ship-tracks. The neural network model generalizes well as it not only finds ship-tracks labeled by human experts, but also detects those that are occasionally missed by humans. It increases our sampling capability of ship-tracks by orders of magnitude and produces a first global map of ship-track distributions using satellite data. Major shipping routes that are mapped by the algorithm correspond well with available commercial data. There are also situations where commercial data are missing shipping routes that are detected by our algorithm. Our technique will enable studying aerosol effects on low clouds using ship-tracks on a large-scale, which will potentially narrow the uncertainty of the aerosol-cloud interactions. The product is also useful for applications such as coastal air pollution and trade. </details>


### (30) Using Smart Meter Data to Forecast Grid Scale Electricity Demand

*Abraham Stanway (Amperon Holdings, Inc); Ydo Wexler (Amperon)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Highly accurate electricity demand forecasts represent a major opportunity to create grid stability in light of the concurrent deployment of distributed renewables and energy storage, as well as the increasing occurrence of extreme weather events caused by climate change. We present an overview of a deployed machine learning system that accomplishes this task by using smart meter data (AMI) within the region governed by the Electric Reliability Council of Texas (ERCOT). </details>


### (31) (Spotlight: 10:30AM) Deep Learning for Wildlife Conservation and Restoration Efforts

*Clement Duhart (MIT Media Lab)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Climate change and environmental degradation are causing species extinction worldwide. Automatic wildlife sensing is an urgent requirement to track biodiversity losses on Earth. Recent improvements in machine learning can accelerate the development of large-scale monitoring systems that would help track conservation outcomes and target efforts. In this paper, we present one such system we developed. 'Tidzam' is a Deep Learning framework for wildlife detection, identification, and geolocalization, designed for the Tidmarsh Wildlife Sanctuary, the site of the largest freshwater wetland restoration in Massachusetts.  </details>



## Ideas Track

### (32)  (Spotlight: 4:50PM) Reinforcement Learning for Sustainable Agriculture

*Jonathan Binas (Mila, Montreal); Leonie Luginbuehl (Department of Plant Sciences, University of Cambridge); Yoshua Bengio (Mila)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

The growing population and the changing climate will push modern agriculture to its limits in an increasing number of regions on earth. Establishing next-generation sustainable food supply systems will mean producing more food on less arable land, while keeping the environmental impact to a minimum. Modern machine learning methods have achieved super-human performance on a variety of tasks, simply learning from the outcomes of their actions. We propose a path towards more sustainable agriculture, considering plant development an optimization problem with respect to certain parameters, such as yield and environmental impact, which can be optimized in an automated way. Specifically, we propose to use reinforcement learning to autonomously explore and learn ways of influencing the development of certain types of plants, controlling environmental parameters, such as irrigation or nutrient supply, and receiving sensory feedback, such as camera images, humidity, and moisture measurements. The trained system will thus be able to provide instructions for optimal treatment of a local population of plants, based on non-invasive measurements, such as imaging. </details>


### (33) (Spotlight: 4:55PM) Stratospheric Aerosol Injection as a Deep Reinforcement Learning Problem

*Christian A Schroeder (University of Oxford); Thomas Hornigold (University of Oxford)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

As global greenhouse gas emissions continue to rise, the use of geoengineering in order to artificially mitigate climate change effects is increasingly considered. Stratospheric aerosol injection (SAI), which reduces solar radiative forcing and thus can be used to offset excess radiative forcing due to the greenhouse effect, is both technically and economically feasible. However, naive deployment of SAI has been shown in simulation to produce highly adversarial regional climatic effects in regions such as India and West Africa. Wealthy countries would most likely be able to trigger SAI unilaterally, i.e. China, Russia or US could decide to fix their own climates and, by collateral damage, drying India out by disrupting the monsoon or inducing termination effects with rapid warming. Understanding both how SAI can be optimised and how to best react to rogue injections is therefore of crucial geostrategic interest.  In this paper, we argue that optimal SAI control can be characterised as a high-dimensional Markov Decision Process. This motivates the use of deep reinforcement learning in order to automatically discover non-trivial, and potentially time-varying, optimal injection policies or identify catastrophic ones. To overcome the inherent sample inefficiency of deep reinforcement learning, we propose to emulate a Global Circulation Model using deep learning techniques. To our knowledge, this is the first proposed application of deep reinforcement learning to the climate sciences.  </details>


### (34) (Spotlight: 5:00PM) Using Natural Language Processing to Analyze Financial Climate Disclosures

*Sasha Luccioni (Mila); Hector Palacios (Element AI)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

According to U.S. financial legislation, companies traded on the stock market are obliged to regularly disclose risks and uncertainties that are likely to affect their operations or financial position. Since 2010, these disclosures must also include climate-related risk projections. These disclosures therefore present a large quantity of textual information on which we can apply NLP techniques in order to pinpoint the companies that divulge their climate risks and those that do not, the types of vulnerabilities that are disclosed, and to follow the evolution of these risks over time. </details>


### (35) Machine Learning-based Maintenance for Renewable Energy: The Case of Power Plants in Morocco

*Kris Sankaran (Montreal Institute for Learning Algorithms); Zouheir Malki (Polytechnique Montréal); Loubna Benabou (UQAR); Hicham Bouzekri (MASEN)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

In this project, the focus will be on the reduction of the overall electricity cost by the reduction of operating expenditures, including maintenance costs. We propose a predictive maintenance (PdM) framework for multi-component systems in renewables power plants based on machine learning (ML) and optimization approaches. This project would benefit from a real database acquired from the Moroccan Agency Of Sustainable Energy (MASEN) that own and operate several wind, solar and hydro power plants spread over Moroccan territory. Morocco has launched an ambitious energy strategy since 2009 that aims to ensure the energy security of the country, diversify the source of energy and preserve the environment. Ultimately, Morocco has set the target of 52% of renewables by 2030 with a large capital investment of USD 30 billion. To this end, Morocco will install 10 GW allocated as follows: 45% for solar, 42% for wind and 13% for hydro. Through the commitment of many actors, in particular in Research and Development, Morocco intends to become a regional leader and a model to follow in its climate change efforts. MASEN is investing in several strategies to reduce the cost of renewables, including the cost of operations and maintenance. Our project will provide a ML predictive maintenance framework to support these efforts. </details>


### (36) GainForest: Scaling Climate Finance for Forest Conservation using Interpretable Machine Learning on Satellite Imagery

*David Dao (ETH); Ce Zhang (ETH); Nick Beglinger (Cleantech21); Catherine Cang (UC Berkeley); Reuven Gonzales (OasisLabs); Ming-Da Liu Zhang (ETHZ); Nick Pawlowski (Imperial College London); Clement Fung (University of British Columbia)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Designing effective REDD+ policies, assessing their GHG impact, and linking them with the corresponding payments, is a resource intensive and complex task. GainForest leverages video prediction with remote sensing to monitor and forecast forest change at high resolution. Furthermore, by viewing payment allocation as a feature selection problem, GainForest can efficiently design payment schemes based on the Shapley value. </details>


### (37) Machine Intelligence for Floods and the Built Environment Under Climate Change

*Kate Duffy (Northeastern University); Auroop Ganguly (Northeastern University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

While intensification of precipitation extremes has been attributed to anthropogenic climate change using statistical analysis and physics-based numerical models, understanding floods in a climate context remains a grand challenge. Meanwhile, an increasing volume of Earth science data from climate simulations, remote sensing, and Geographic Information System (GIS) tools offers opportunity for data-driven insight and action plans.  Defining Machine Intelligence (MI) broadly to include machine learning and network science, here we develop a vision and use preliminary results to showcase how scientific understanding of floods can be improved in a climate context and translated to impacts with a focus on Critical Lifeline Infrastructure Networks (CLIN).
</details>


### (38) Predicting Marine Heatwaves using Global Climate Models with Cluster Based Long Short-Term Memory

*Hillary S Scannell (University of Washington); Chris Fraley (Tableau Software); Nathan Mannheimer (Tableau Software); Sarah Battersby (Tableau Software); LuAnne  Thompson (University of Washington)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Marine heatwaves make human and natural systems vulnerable to disaster risk through the disruption of ecological services and biological function. These extreme warming events in sea surface temperature are expected to become more frequent and longer lasting as a result of climate change. Large ensembles of global climate models now provide petabytes of climate-relevant data and an opportunity to probe machine learning to glean new insights about the climate conditions that cause marine heatwaves. Here we propose a k-means cluster based learning objective to map the geography of marine heatwave drivers globally to build a forecast for extreme sea surface temperatures using Long Short-Term Memory. We describe our machine learning approach to predict when and where future marine heatwaves will occur while leveraging the massive output of data from global climate models where traditional forecasting approaches fall short. The impacts of this work could warn coastal communities by providing a forecast for marine heatwaves, which would mitigate the negative effects on fishery productivity, ecosystem health, and tourism. 
</details>


### (39) (Spotlight: 5:05PM) ML-driven search for zero-emissions ammonia production materials

*Kevin McCloskey (Google)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Ammonia (NH3) production is an industrial process that consumes between 1-2% of global energy  annually  and  is  responsible  for  2-3%  of greenhouse gas emissions (Van der Ham et al.,2014).  Ammonia is primarily used for agricultural fertilizers, but it also conforms to the US-DOE targets for hydrogen storage materials (Lanet al., 2012). Modern industrial facilities use the century-old Haber-Bosch process, whose energy usage  and  carbon  emissions  are  strongly  dominated by the use of methane as the combined energy source and hydrogen feedstock, not by the energy used to maintain elevated temperatures and pressures (Pfromm, 2017). Generating the hydrogen feedstock with renewable electricity through water electrolysis is an option that would allow retrofitting the billions of dollars of invested capital  in  Haber-Bosch  production  capacity.   Economic viability is however strongly dependent on the relative regional prices of methane and renewable energy; renewables have been trending lower in cost but forecasting methane prices is  difficult  (Stehly  et  al.,  2018;  IRENA,  2017; Wainberg et al., 2017). Electrochemical ammonia production, which can use aqueous or steam H2O as  its  hydrogen  source  (first  demonstrated   ̃20years ago) is a promising means of emissions-free ammonia production. Its viability is also linked to the relative price of renewable energy versus methane, but in principle it can be significantly more cost-effective than Haber-Bosch (Giddeyet al., 2013) and also downscale to developing areas lacking ammonia transport infrastructure(Shipman & Symes, 2017). However to date it has only been demonstrated at laboratory scales with yields and Faradaic efficiencies insufficient to be economically competitive.  Promising machine-learning approaches to fix this are discussed. 
</details>


### (40) (Spotlight: 5:10PM) Low-carbon urban planning with machine learning

*Nikola Milojevic-Dupont (Mercator Research Institute on Global Commons and Climate Change (MCC)); Felix Creutzig (Mercator Research Institute on Global Commons and Climate Change (MCC))*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Widespread climate action is urgently needed, but current solutions do not account enough for local differences. Here, we take the example of cities to point to the potential of machine learning (ML) for generating at scale high-resolution information on energy use and greenhouse gas (GHG) emissions, and make this information actionable for concrete solutions. We map the existing relevant ML literature and articulate ML methods that can make sense of spatial data for climate solutions in cities. Machine learning has the potential to find solutions that are tailored for each settlement, and transfer solutions across the world.
</details>


### (41) The Grid Resilience & Intelligence Platform (GRIP)

*Ashley Pilipiszyn (Stanford University)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Extreme weather events pose an enormous and increasing threat to the nation’s electric power systems and the associated socio-economic systems that depend on reliable delivery of electric power. The US Department of Energy reported in 2015, almost a quarter of unplanned grid outages were caused by extreme weather events and variability in the environment. Because climate change increases the frequency and severity of extreme weather events, communities everywhere will need to take steps to better prepare for, and if possible prevent major outages. While utilities have software tools available to help plan their daily and future operations, these tools do not include capabilities to help them plan for and recover from extreme events. Software for resilient design and recovery is not available commercially and research efforts in this area are preliminary. In this project, we are developing and deploying a suite of novel software tools to anticipate, absorb and recover from extreme events. The innovations in the project include the application of artificial intelligence and machine learning for distribution grid resilience, specifically, by using predictive analytics, image recognition and classification, and increased learning and problem-solving capabilities for the anticipation of grid events.  
</details>


### (42) Meta-Optimization of Optimal Power Flow

*Mahdi Jamei (Invenia Labs); Letif Mones (Invenia Labs); Alex Robson (Invenia Labs); Lyndon White (Invenia Labs); James Requeima (Invenia Labs); Cozmin Ududec (Invenia Labs)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

The planning and operation of electricity grids is carried out by solving various forms of con- strained optimization problems. With the increasing variability of system conditions due to the integration of renewable and other distributed energy resources, such optimization problems are growing in complexity and need to be repeated daily, often limited to a 5 minute solve-time. To address this, we propose a meta-optimizer that is used to initialize interior-point solvers. This can significantly reduce the number of iterations to converge to optimality. 
</details>


### (43) Learning representations to predict landslide occurrences and detect illegal mining across multiple domains

*Aneesh Rangnekar (Rochester Institute of Technology); Matthew J Hoffman (Rochester Institute of Technology)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Modelling landslide occurrences is challenging due to lack of valuable prior information on the trigger. Satellites can provide crucial insights for identifying landslide activity and characterizing patterns spatially and temporally. We propose to analyze remote sensing data from affected regions using deep learning methods, find correlation in the changes over time, and predict future landslide occurrences and their potential causes. The learned networks can then be applied to generate task-specific imagery, including but not limited to, illegal mining detection and disaster relief modelling. 
</details>


### (44) Harness the Power of Artificial intelligence and -Omics to Identify Soil Microbial Functions in Climate Change Projection

*Yang Song (Oak Ridge National Lab); Dali  Wang (Oak Ridge National Lab); Melanie Mayes (Oak Ridge National Lab)*
<details>
<summary>
  Abstract: (click to expand)
</summary>

Contemporary Earth system models (ESMs) omit one of the significant drivers of the terrestrial carbon cycle, soil microbial communities. Soil microbial community not only directly emit greenhouse gasses into the atmosphere through the respiration process, but also release diverse enzymes to catalyze the decomposition of soil organic matter and determine nutrient availability for aboveground vegetation. Therefore, soil microbial community control over terrestrial carbon dynamics and their feedbacks to climate. Currently, inadequate representation of soil microbial communities in ESMs has introduced significant uncertainty in current terrestrial carbon-climate feedbacks. Mitigation of this uncertainty requires to identify functions, diversity, and environmental adaptation of soil microbial communities under global climate change. The revolution of -omics technology allows high throughput quantification of diverse soil enzymes, enabling large-scale studies of microbial functions in climate change. Such studies may lead to revolutionary solutions to predicting microbial-mediated climate-carbon feedbacks at the global scale based on gene-level environmental adaptation strategies of the microbial community. A key initial step in this direction is to identify the biogeography and environmental adaptation of soil enzyme functions based on the massive amount of data generated by -omics technologies. Here we propose to make this step. Artificial intelligence is a powerful, ideal tool for this leap forward. Our project is to integrate Artificial intelligence technologies and global -omics data to represent climate controls on microbial enzyme functions and mapping biogeography of soil enzyme functional groups at global scale. This outcome of this study will allow us to improve the representation of microbial function in earth system modeling and mitigate uncertainty in current climate projection.   
</details>
