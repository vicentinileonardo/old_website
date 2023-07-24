---
layout: projects_page
title: Projects
permalink: /projects/
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">



# Query recommendation system

### Dates

+ **Start date**: 2021-03-01
+ **End date**: 2021-06-01

### Project description

**Hybrid recommendation system** leveraging a linear combination of Expanded-Item-Item Collaborative Filtering and Compact Item-Item Collaborative Filtering based on query result cardinality.

### Repository and Report

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/query-recommendation-system','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
    <button onclick="window.open('/project_reports/query_recommendation_system.pdf','_blank');" type="button" class="btn"><i class="fa fa-file-pdf-o" style="font-size:42px"></i></button>
</center>

### Team and role

Team size: 2 people

+ I was responsible for the implementation of the precursor of the generic Item-Item Collaborative Filtering algorithm and the **Compact Item-Item Collaborative Filtering** algorithm. <br>
+ I proposed and integrated the **evaluation metrics** used throughout the project. <br>
+ I implemented several other components, following other approaches, such as a **Content-based** algorithm, which did not satisfied our baseline requirements. <br>
+ I proposed and implemented the **linear combination** based on query result cardinality of the two best algorithms. <br>
+ Given my previous experience with **data visualization**, I created the visualizations of the results for the report, along with the contribution to the redaction of the report itself.

### Tech stack

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) 


<br>
<hr style="border:2px solid gray"> 
<br>


# Digital watermarking tool 

### Project description

A digital watermarking tool developed for the **"Catch the Mark" competition** of the Multimedia Data Security graduate course at the University of Trento. <br>
The implementation is based on various research papers and leverages **Discrete Wavelet Transform** and **Singular Value Decomposition**. <br>
The repository contains code for embedding, detecting, and attacking watermarked images. <br>
Overall, the embedding strategy was evaluated as interesting and effective. <br>
**Azure IaaS** (VM with configured Python venv), Google Colab (Jupyter notebooks) and local machines were exploited for the parallelization of the attack phase.

### Repository

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/DWT-SVD-digital-watermarking','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
</center>

### Team and role

Team size: 4 people

+ I was responsible for the implementation of the **embedding** and **detection** algorithm along with another team member. <br>
+ I **proposed** and **set up** simple but effective cloud services for the attack phase. <br>
+ Given my previous experience with Python and its main libraries, I took the lead for the **supervision** of the project and the **coordination** of the team.
+ Since our backgrounds were pretty different, we tried to **leverage** the most of each other's skills and knowledge, from telecommunications to software engineering and cybersecurity. <br>

### Tech stack
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) 

<br>
<hr style="border:2px solid gray"> 
<br>

# Parallel convex hull solver

### Project description

Parallel implementation of the Divide and Conquer algorithm for the convex hull problem. The implementation is based on the **C** programming language and leverages **MPI** and **OpenMP** libraries. The solution was tested on a **High-Performance Computing cluster** with specific PBS configuration files.

### Repository and Report

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/parallel-convex-hull','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
    <button onclick="window.open('/project_reports/parallel_convex_hull_solver.pdf','_blank');" type="button" class="btn"><i class="fa fa-file-pdf-o" style="font-size:42px"></i></button>
</center>

### Team and role

Team size: 2 people

+ The team designed the general implementation strategy together. <br>
+ I contributed in part of the core implementation and debugging of the algorithm. <br>
+ I was responsible for the implementation fo the *OpenMP* section of the project. <br>
+ I investigated various PBS configurations for the HPC cluster and proposed the final one. <br>

### Tech stack
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 

<br>
<hr style="border:2px solid gray"> 
<br>

# Daytrip - service-oriented cloud-native web application

### Project description

The project aims to create a web application that suggests daytrip destinations in Italy based on weather conditions, travel time, and other indicators. A service-oriented architecture was used to build decoupled services that can be expanded and modified independently.

### Repository and Report

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/daytrip','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
    <button onclick="window.open('/project_reports/daytrip.pdf','_blank');" type="button" class="btn"><i class="fa fa-file-pdf-o" style="font-size:42px"></i></button>
</center>

### Team and role

Team size: 2 people

### Tech stack
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)

![NGINX](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) 
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) 
![ExpressJS](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

<br>
<hr style="border:2px solid gray"> 
<br>

# Multi-level distributed cache

### Project description

TODO

### Repository and Report

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/distributed-cache','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
    <button onclick="window.open('','_blank');" type="button" class="btn"><i class="fa fa-file-pdf-o" style="font-size:42px"></i></button>
</center>

### Team and role

Team size: 2


### Tech stack
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)

<br>
<hr style="border:2px solid gray"> 
<br>


# ProjectsChain

### Project description

ProjectsChain is a plugin developed in order to be integrated with already existing e-shops of industrial designs and is able to grant, using the public **blockchain** and through **smart contracts**, the intellectual property of the projects and a fair royalty distribution between coauthors of a final project. The straightforward and transparent mechanism developed also will prevent non-payment and miscommunication risks, representing common scenarios among freelancers.

### Repository and Report

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/projectschain','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
    <button onclick="window.open('/project_reports/projects_chain.pdf','_blank');" type="button" class="btn"><i class="fa fa-file-pdf-o" style="font-size:42px"></i></button>
    <button onclick="window.open('https://drive.google.com/file/d/1NBfR3Tln6dz7mGiXHSfOW1VU1A21XQo1/view?usp=sharing','_blank');" type="button" class="btn"><i class="fa fa-video-camera" aria-hidden="true" style="font-size:42px"></i></button>
</center>

### Team and role

Team size: 3

+ I was responsible for the design and implementation of a web server and related **RESTful APIs** that performs CRUD operations against a properly configured NoSQL database (**Redis**),
which are critical for the pre-mint operation, IPFS upload and catalog fetching.
+ I proposed and implemented a **digital signature** mechanism into the server code and into
Master smart contract.
+ I was responsible for the **Chainlink node** setup and Chainlink jobs configurations together with the CustomChainlinkClient smart contract development and integration with ProjectNFT.
+ I contributed to the initial high-level smart contracts design together with final smart contract **optimization** and **testing**


### Tech stack


![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Vue](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Web3JS](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3.js&logoColor=white)

![Solidity](https://img.shields.io/badge/Solidity-e6e6e6?style=for-the-badge&logo=solidity&logoColor=black)
![Chainlink](https://img.shields.io/badge/chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white)

![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) 
![ExpressJS](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Redis](https://img.shields.io/badge/redis-CC0000.svg?&style=for-the-badge&logo=redis&logoColor=white)

<br>
<hr style="border:2px solid gray"> 
<br>

# Galaxies image classification

### Project description

The goal of this project is to classify galaxies images into **10 different classes**. In order to achieve this goal, several models have been trained and tested, as explained in the report. The final model is leveraging a pre-trained **VGG19** network as a feature extractor and **Support Vector Machines** as a classifier. The model has been trained on a dataset of 9928 images, validated on 2487 images and tested on 5321 images. The model has achieved a sample-wise accuracy of 85.6% and a class-wise accuracy of 83.8% on the test set.

### Repository and Report

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/galaxies-image-classification','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
    <button onclick="window.open('/project_reports/galaxies_image_classification.pdf','_blank');" type="button" class="btn"><i class="fa fa-file-pdf-o" style="font-size:42px"></i></button>
</center>


### Team and role

Team size: 1 person

+ I was responsible for the whole project, from model exploration to final implementation. <br>

### Tech stack

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) 
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)

<br>
<hr style="border:2px solid gray"> 
<br>

# Dating app

### Project description

A web app that allows users to register, login, and find other users based on their **preferences**. A simple **chat system** was implemented as well.
The goal of the project was to learn to design and develop RESTful APIs using Node.js and Express.js. The project was developed in a team of 5 people and Scrum was adopted as an agile workflow methodology.
Pair programming was also adopted as a development technique since it was the first time working with Node.js and REST for some of the team members.

### Repository and Report

<center>
    <button onclick="window.open('https://github.com/vicentinileonardo/dating-app','_blank');" type="button" class="btn" ><i class="fa fa-github" style="font-size:42px"></i></button>
</center>


### Team and role

Team size: 5

+ Given my previous experience with web development, I was co-led the initial design of the project. <br>
+ I was responsible for the implementation of some of the core RESTful endpoints <br>

### Tech stack

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) 
![ExpressJS](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

<br>
<hr style="border:2px solid gray"> 
<br>
