<p align="center">
  <a href="https://strapi.io">
    <img src="https://i.ibb.co/rF4cHpr/g-logo-01.png" width="318px" alt="Strapi logo" />
  </a>
</p>
<h1 align="center">Grease Pencil</h1>
<p align="center">An Intelligent Story Board Generator</p>
<p align="center"><a href="https://gpdemo.azurewebsites.net/">Try live demo</a></p>

## 📚 Live Demo Guide

### <a href="https://gpdemo.azurewebsites.net/"> Log in page:</a>
Login Credentials
- Username = demo
- Password = demo

### <a href="https://www.dailyscript.com/scripts/STRANGER-THINGS-1x01-The-Vanishing-of-Will-Byers-2ND-PINK.pdf">Drag & Drop page:</a>
Sample Script for drag & drop page
- Use **General format script in pdf** or
- Use this <a href="http://www.dailyscript.com/scripts/STRANGER-THINGS-1x01-The-Vanishing-of-Will-Byers-2ND-PINK.pdf">strangers things ep1 script (upload this script in drag & drop page)</a> for testing

### Story Time line page:</a>
- From your uploaded script each & every frames will be extracted
- Without exception, every frame will have the following
   ~ BG
   ~ Charecter
   ~
<br>

## 🤔 What is Grease Pencil

## Find the <a href="https://docs.google.com/presentation/d/1kOXX6n1mg9pxoM6lZFUyLO6THKVzh1Wdu7U8U-J7RKk/edit?usp=sharing/"> Presentation </a> and <a href="https://youtu.be/__kPN5Aes3Q/"> explainer video</a> here

Grease pencil is an Intelligent Substitute for storyboard, which uses to AI to generate storyboard images which takes textual inputs and produce image as an output.
Please go through the<a href="https://docs.google.com/presentation/d/1kOXX6n1mg9pxoM6lZFUyLO6THKVzh1Wdu7U8U-J7RKk/edit?usp=sharing/"> ppt for thorough details,</a> and find the<a href="https://youtu.be/__kPN5Aes3Q/"> explainer video here</a> 

<p align="center">
    <img src="https://i.ibb.co/vx37j3p/flow-diagram.png" alt="Omni chart" />
  </a>
</p>

<br>



## 📚 Table of Contents

###  How Azure Helping Grease Pencil

<details>
<summary>Read more...</summary>

#### **Storage Layer:**

-   Azure Blob Storage - for dataset [only images]
    
-   Azure Cosmos DB (SQL API) - for dataset [text prompts for the given images]
    
-   Azure Files - to hold user/client scripts
    
-   Azure Database for MySQL - holding User Details, User Activity, Invoicing and other relational data of the Grease Pencil
 #### **Code Pipeline:**
-   Azure Repos - Source code maintenance and version control
    
-   Azure Pipeline - To Build a docker image from the repository upon a commit in master branch
    
-   Container Registry - To Store the built docker images
    
-   App Service - To host the application from a docker image with zero downtime
 #### **MLOps:**
 -   Azure Data Factory - To process the data and stage for training upon new data or code check-ins
    
-   Azure ML Workspace - To run a training job and store the model in Model Registry
  </details>


### 📦 Backend

<details>
<summary>Used tools</summary>

#### Python

- Flask

  </details>

### 🌐 Frontend

<details>
<summary>Used tools</summary>

-React
- HTML5
- BootStrap
- CSS
- Java Script
  </details>

## 🙌🏼 Reference

<p><a href="https://www.aclweb.org/anthology/D18-1117.pdf">A Dataset for Telling the Stories of Social Media Videos</a></p>
<p><a href="https://prior.allenai.org/projects/charades-ego">Dataset</a></p>
<p><a href="https://arxiv.org/pdf/2102.12092.pdf">Dalle Paper</a></p>


