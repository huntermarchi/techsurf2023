# TechSurf2023

# Project's Title:

Design & Develop an impressive tool that utilizes generative AI to generate content while maintaining the style and tone of previously written content.
So we designed two applications for AI Generative .

1. AI image generator
2. AI text generator

                                        CONTENTSTACK AI IMAGE GENERATOR

  Below is the homepage of AI Image generator  🏆🏆


                                                    IMAGE 1 

  
<img width="1440" alt="Screenshot 2023-08-21 at 5 38 56 PM" src="https://github.com/huntermarchi/techsurf2023/assets/95737632/29c1d355-c77f-4597-a6c4-64a075671124">


The working images are as follows of our Image Generator :

                                                   IMAGE 2


<img width="1440" alt="Screenshot 2023-08-21 at 5 34 16 PM" src="https://github.com/huntermarchi/techsurf2023/assets/95737632/f00a923a-6ed7-4c5f-b272-7d6b18bc3930">


So if we search football then our appliaction give 1024 * 1024 (It generates 4 images ) shown below :


                                                  IMAGE 3
               

<img width="1440" alt="Screenshot 2023-08-21 at 5 38 05 PM" src="https://github.com/huntermarchi/techsurf2023/assets/95737632/d681cd0b-3163-4782-a0a4-daa4c1908037">

                                                   IMAGE 4


<img width="1440" alt="Screenshot 2023-08-21 at 5 33 15 PM" src="https://github.com/huntermarchi/techsurf2023/assets/95737632/59616531-5097-49f5-8bad-98cc7998823f">

<br>


So for giving these images and working of our project we connected this with : https://api.openai.com/v1/images/generations


Link for my AI Generator Application : https://huntermarchi.github.io/techsurf2023/


# HOW TO MAKE THE RUNNING ENVIRONMENT FOR ABOVE APPLICATION 

                            pip install openai

To install the official Node.js library, run the following command in your Node.js project directory.

                        npm install openai@^4.0.0
 All API requests should include your API key in an Authorization HTTP header as follows:

                        Authorization: Bearer OPENAI_API_KEY

 Example curl command:
                           curl https://api.openai.com/v1/models \
  -H "Authorization: Bearer $OPENAI_API_KEY" \
  -H "OpenAI-Organization: org-ud1aMk8vQtEmb0HbOw8Cfb7Y"


  Example with the openai Python package:

import os
import openai
openai.organization = "org-ud1aMk8vQtEmb0HbOw8Cfb7Y"
openai.api_key = os.getenv("OPENAI_API_KEY")
openai.Model.list()


 Example with the openai Node.js package:

import { Configuration, OpenAIApi } from "openai";
const configuration = new Configuration({
    organization: "org-ud1aMk8vQtEmb0HbOw8Cfb7Y",
    apiKey: process.env.OPENAI_API_KEY,
});
const openai = new OpenAIApi(configuration);
const response = await openai.listEngines();









