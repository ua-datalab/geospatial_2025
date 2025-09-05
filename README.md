# GeospatialAI 
#### Special series

### Artificial Intelligence is Reshaping our Interaction with Geographic Data
<img src="https://github.com/ua-datalab/Geospatial_Workshops/blob/main/images/UA_datalab.png" width=100> &nbsp;&nbsp;&nbsp; <img src="https://github.com/ua-datalab/Geospatial_Workshops/blob/main/images/PoweredbyCyverse_LogoSquare0.png" width=67>
<image src="https://github.com/ua-datalab/Geospatial_Workshops/blob/main/images/jetstream2_logo.png" width=200>


<img src="./images/geospatial_robot.png" width=700>

|    | Workshop Information       |
|  --- | ----  |
| Dates | Sept. 4, 11, & 18 - 2025 |
| When | Thursdays 10 am Arizona Time | 
| Where | Hybrid at [Weaver Science-Engineering Library](https://map.arizona.edu/54) Room 212 & Zoom (https://arizona.zoom.us/j/86009100882) |

[Worshop Registration](https://uarizona.co1.qualtrics.com/jfe/form/SV_3eq2ax2JjH52Wiy)   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  [Feeback Form]  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Youtube Playlist](https://www.youtube.com/playlist?list=PLohiBOvMMwCsICfZRYmnAIW3xNb1Gvpis)

<br/>
<br/>

## About the Workshop Series

Since the 'chatgpt moment' in late 2022, multimodal AI models have surged forward with ever more astonishing capabilities. The impact of these AI systems in the fields of GIS, remote sensing, and spatial data analysis (collectively called Geospatial) is starting to take shape. 

* AI models are increasingly capable of writing custom analysis code and are morphing from a source of advice to an agent capable of executing GIS commands directly on your computer.

* In the domain of imagery analysis, the open ecosystem of machine learning is producing ever more capable models for a variety of tasks like object detection and image classification. The ML workflow is on the cusp of being automated. 

* Remote sensing foundation models hold the promise of accelerating ML accuracy and text-vision models are making it possible to perform complex image analyis with text prompts. 

<br/>
<br/>

This 3-Part series will begin with a broad overview of developments in GeoAI. It aims to be more accessible to a general audience and demystify the jargon for researchers working with GIS/Remote Sensing data. 

The following two sessions will be more technical and guide attendees through hands-on examples of GeoAI technology in practice. Together, we will 'vibe code' our way through Google Earth Engine, QGIS, and run through a ML Vision workflow using a state-of-art cloud computer Jetstream2. Following along during the technical sessions will require some pre-workshop setup.   

<br/>
<br/>

The series is **FREE** and open to all University of Arizona personnel and is tailored for graduate students, postdocs, and early career faculty looking to expand their geospatial skills. Basic knowledge of scripting languages (i.e., python) and some prior geospatial experience will be helpful. Please [register here for the workshop](https://uarizona.co1.qualtrics.com/jfe/form/SV_3eq2ax2JjH52Wiy)

<br/>

As we explore these topics together, I hope it will spark curiosity and wonder, but also appropriate caution. As our AI systems are getting more powerful and more autonomous, it's important that we integrate them into our current workflows with thought and care. 



<br/>
<br/>

## Schedule Fall 2025

| Date |  Topic | Description |
| :--: | :--: | :-- |
| 09/04/2025   | [The Geospatial AI Landscape](https://docs.google.com/presentation/d/14Yhtt5N2mZVx_RzDXFwmsEya7UvcabITFn2JooQbjy4/edit?usp=sharing) | Join us as we explore the convergence of GIS/Remote Sensing with AI and how this will lower technical barriers while being a force multiplier in geographic data analyis. [Recording Here](https://arizona.zoom.us/rec/share/hVglda-983S96pSiHi9kfhx5qMV_AJQ2hxH02RDWjeHu_aPu_RD9-uMQc8CqtP_e.1GCnPOMiZVkcXHkc?startTime=1756999291000)
|  09/11/2025   | Hands-On 👋 <br/>  [Coding Agents in QGIS and Earth Engine](#setup-for-coding-agents-9112025)  | The session will demonstrate two AI tools for autonomous geospatial analysis: <br/><br/> - Execute commands in QGIS with Anthropic's Claude <br/> - Generate analysis code in Earth Engine using Google's Gemini. <br/><br/> To follow along, please see the pre-session setup instructions [here](#setup-for-coding-agents-9112025).  |
|    09/18/2025 | Hands-On 👋 <br/> [End-to-End Deep Learning Workflow for Aerial Imagery Analysis](#setup-for-end-to-end-deep-learning-for-aerial-imagery-9182025)  | This session will walk through a complete machine learning workflow from getting a pretrained model, to zero-shot predictions, to image labeling and training. Several open-source tools will be used including Data-to-Science, jupyter notebooks, pytorch, github, and Huggingface. <br/><br/> To follow along, please see the pre-session setup instructions [here](#setup-for-end-to-end-deep-learning-for-aerial-imagery-9182025). |







<br/>
<br/>



## The Instructor

The series is expert-led by educators at the [University of Arizona Data Science Institute](https://datascience.arizona.edu/) and [Cyverse](https://cyverse.org/). 
<br/>
<br/>

<img src="https://github.com/ua-datalab/Geospatial_Workshops/blob/main/images/gillan_headshot_2023.jpg" width=300>


[Jeffrey Gillan Ph.D](https://www.gillanscience.com), is a research data scientist with Cyverse and has 17 years of experience in geospatial science. His remote sensing expertise includes drone-based photogrammetry, LiDAR, and hyperspectral image analysis. He is an advovate open science and enjoys building imagery processing pipelines. 

Dr. Gillan is available for consulations and collaborations if you are looking to incorporate geospatial data science in your research or grant proposal. 

<br/>
<br/>


## Setup for Coding Agents (9/11/2025)
To participate in this hands-on session, each attendee needs to have their own computer. If you are attending in-person at the UA library, please bring your laptop. You can also join us via Zoom from your home computer. Additionally, you will need to install software prior to the session and have Google Earth Engine Accounts. We will BRIEFLY go over software and account requirements at the beginning of the session, but will not dedicate significant time to it. I would like to spend the session exploring agentic data analysis and learning from each other what works, what doesn't work, and best practices for usage. 


### QGIS & MCP
Before the session begins, each attendee will need to have a recent version of QGIS installed on their machine. Additionally, you will need to set up the MCP server and install a QGIS plugin. Full instructions are [here](https://github.com/jjsantos01/qgis_mcp). 


### Google Earth Engine
To have a play with agentic EE, check out this demo jupyter notebook
[![Open Colab Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/google/earthengine-community/blob/master/experimental/functionsmith/ee_companion.ipynb). 


For the demo to work, the user needs to have **1.** an [Earth Engine Project ID](https://code.earthengine.google.com/register), and **2.** a [Gemini API Key](https://ai.google.dev/gemini-api/docs/api-key). Both of these items are free to obtain. 

These two items needs to be saved as [Colab Secrets](https://colab.sandbox.google.com/github/google-gemini/cookbook/blob/main/quickstarts/Authentication.ipynb)

<img src="https://github.com/jeffgillan/earthengine-community/blob/master/experimental/functionsmith/colab_secrets.png" width=400>




<br/>
<br/>

## Setup for End-to-End Deep Learning for Aerial Imagery (9/18/2025)

For this technical session, every student will get their own virtual machine on the powerful cloud computer [Jetstream2](https://jetstream-cloud.org/index.html). Together we will work through entire machine learning workflows for high-resolution airplane and drone imagery. We will step through the process of finding pretrained models on the web, applying zero-shot prediction on our dataset, labeling our training data, and fine-tuning a model to fit our specific use case. We will be working primarily in a Jupyter Lab environment and using python to instruct the computer. Knowledge of python will be helpful, but not totally necessary because all the code will be pre-written for you. 

Setting up VMs for every student takes preparation so I need to know ahead of time who is serious about participating. **PLEASE NOTIFY ME OF YOUR INTENT TO PARTICIPATE BY THURSDAY SEPTEMBER 11, 2025. jgillan@arizona.edu**

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc-sa.png" width="128">  [  CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)

[UArizona DataLab](https://www.datascience.arizona.edu/education/uarizona-data-lab), Data Science Institute, University of Arizona, 2025.

<img src="https://datascience.arizona.edu/sites/default/files/Data%20Science%20Institute_Webheader%20%281%29_0.svg" width="256">
