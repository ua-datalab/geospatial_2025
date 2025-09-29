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

[Worshop Registration](https://uarizona.co1.qualtrics.com/jfe/form/SV_3eq2ax2JjH52Wiy)   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  [Feeback Form]  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 

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
| 09/04/2025 <br/> [Recording Here](https://youtu.be/MDK98eEPjpo)  | [The Geospatial AI Landscape](https://docs.google.com/presentation/d/14Yhtt5N2mZVx_RzDXFwmsEya7UvcabITFn2JooQbjy4/edit?usp=sharing) | Join us as we explore the convergence of GIS/Remote Sensing with AI and how this will lower technical barriers while being a force multiplier in geographic data analysis. 
|  09/11/2025 <br/> [Recording Here](https://youtu.be/83_DOVV5luM)  | Hands-On 👋 <br/>  [Coding Agents in QGIS and Earth Engine](#setup-for-coding-agents-9112025)  | The session will demonstrate two AI tools for autonomous geospatial analysis: <br/><br/> - Execute commands in QGIS with Anthropic's Claude <br/> - Generate analysis code in Earth Engine using Google's Gemini. <br/><br/> To follow along, please see the pre-session setup instructions [here](#setup-for-coding-agents-9112025).  |
|    09/18/2025 <br/> [Recording Here](https://youtu.be/mRQuSAbTS1I) | Hands-On 👋 <br/> [End-to-End Deep Learning Workflow for Aerial Imagery Analysis](#setup-for-end-to-end-deep-learning-for-aerial-imagery-9182025)  | This session will walk through a complete machine learning workflow from getting a pretrained model, to zero-shot predictions, to image labeling and training. The example workflow will use the python library [DeepForest](https://deepforest.readthedocs.io/en/v1.5.0/index.html)  for detecting trees from high-resolution airplane or drone imagery. [![Open Colab Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ua-datalab/geospatial_2025/blob/main/notebooks/deepforest_colab_final.ipynb)  <br/><br/> To follow along, please see the pre-session setup instructions [here](#setup-for-end-to-end-deep-learning-for-aerial-imagery-9182025). |







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
Before the session begins, each attendee will need to have a recent version of QGIS installed on their machine. You will need Claude desktop installed on your computer. Additionallly, you need to set up the MCP server and install a QGIS plugin. Full instructions are [here](https://github.com/jjsantos01/qgis_mcp). 


### Google Earth Engine
To have a play with agentic EE, check out this demo jupyter notebook
[![Open Colab Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/google/earthengine-community/blob/master/experimental/functionsmith/ee_companion.ipynb). 


For the demo to work, the user needs to have **1.** an [Earth Engine Project ID](https://code.earthengine.google.com/register), and **2.** a [Gemini API Key](https://ai.google.dev/gemini-api/docs/api-key). Both of these items are free to obtain. 

These two items needs to be saved as [Colab Secrets](https://colab.sandbox.google.com/github/google-gemini/cookbook/blob/main/quickstarts/Authentication.ipynb)

<img src="https://github.com/jeffgillan/earthengine-community/blob/master/experimental/functionsmith/colab_secrets.png" width=400>

<br/>
<br/>

### Data for QGIS/Claude

Download the [digital surface model (426mb)](https://data.cyverse.org/dav-anon/iplant/projects/cyverse_training/datalab/nextgen_geospatial/scr_25april25_dsm.tif)

Download the [orthomosaic (900mb)](https://data.cyverse.org/dav-anon/iplant/projects/cyverse_training/datalab/nextgen_geospatial/scr_25april25_ortho.tif
)

Download [polygon file](https://data.cyverse.org/dav-anon/iplant/projects/cyverse_training/datalab/nextgen_geospatial/peloncillo_west_aoi.gpkg
)
<br/>
<br/>

### Prompts for QGIS/Claude

ping qgis

Your working directory for this project is /Users/jgillan/Documents/qgis_mcp

Connect to qgis and help me with some geographic analysis. As we proceed, please follow my instructions precisely and do not execute any code and analysis without my express permission. I'm going to explain the task I want completed, you will NOT launch into code execution until you have reasoned through the steps required to complete the task and summarized them for me. It's important to understand before doing and keeping me in the loop before any action. When I give you permission to proceed with the code generation and execution, you will write a summary report for me that includes the final successful code. I want to keep that code for future use. Please write out successful code to python files within the working directory.

Add the file scr_25april25_dsm.tif to the map

Create a hillshade layer of the dsm

Make a presentation quality map (.png) that displays the DSM on top of the hillshade. Make the dsm layer have a rainbow color ramp. Also make the DSM transparent enough to be able to see the hillshade layer underneath. This map is for an important presentation in front of a bunch of cartographers. Make sure it has a good north arrow and scale bar. Please put a legend showing the elevation of the DSM. 

From the working directory, add the layer scr_25april25_ortho.tif to the map. I am interested in identify green vegetation in the image. Can you do some band math to create a green leaf index that is similar to NDVI but using only the rgb bands?

Create a rectangular polygon layer as a geojson. Please make about 20 x 10 meters in size and put it dead center of the map display. 

Clip out the dsm layer using the new geojson polygon. 

Run a python script that is located in my working directory. 

<br/>
<br/>

## Setup for End-to-End Deep Learning for Aerial Imagery (9/18/2025)

We will be using Google Colab as our computing environment. This is free to use but with limited computing resources. The only setup I recommend is getting a [Colab Pro account](https://colab.research.google.com/signup). This is FREE for university affiliated people and will give you access to higher RAM and better GPUs. 

Together we will work through entire machine learning workflow to identify trees in a high-resolution drone orthomosaic. We will step through the process of finding pretrained models on the web, applying zero-shot prediction on our dataset, labeling our training data, and fine-tuning a model to fit our specific use case. We will be working primarily in a Jupyter Lab environment and using python to instruct the computer. Knowledge of python will be helpful, but not totally necessary because all the code will be pre-written for you. Access the machine learning workflow here [![Open Colab Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ua-datalab/geospatial_2025/blob/main/notebooks/deepforest_colab_final.ipynb)



<br/>
<br/>
<br/>
<br/>

## Attendance

90 total registrations
* 19 UA Graduate Students (Geographic Information Systems Tech; Geography & Development; Information Science; Geosciences; Biomedical Sciences; Landscape Architecture & Planning)
* 8 UA faculty (Geographic Information Systems Tech; Libraries, Ecology & Evolutionary Biology; Information Science; Ag & Resource Econ; Natural Resources & Environment)
* 11 UA Staff (Academic Affairs; Natural Resources & Environment;  Cooperative Extension)
* 6 UA postdocs (Ag Resource Econ; Information Science; Geographic Information Systems Tech; Geography & Development)
* 2 undergraduate student
* 42 Not affiliated with UA

Non-UA affiliation include: DroneDeploy, Crossbill Geospatial, Worldsphere, WSP, University of Nebraska Lincoln, University of Alaska Fairbanks, Waste Management, USDA Agriculture Research Service, Colorado University Boulder, Northern Arizona University, American Forest Management, University of Tehran, Buenos Aires University, Sistemas, Institute of Technology Hyderabad, James Cook University, Tufts University, The Nature Conservancy, GEOInovo, City of Phoenix Contractor, Namibia University of Science & Tech, Sanborn Map Company, North Carolina State University, Central Arizona Project, University of California Davis




<br/>
<br/>

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-nc-sa.png" width="128">  [  CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/)

[UArizona DataLab](https://www.datascience.arizona.edu/education/uarizona-data-lab), Data Science Institute, University of Arizona, 2025.

<img src="https://datascience.arizona.edu/sites/default/files/Data%20Science%20Institute_Webheader%20%281%29_0.svg" width="256">
