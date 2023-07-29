# Immo Eliza Deployment
A personal project @ [BeCode.org](https://becode.org/) as part of the **AI Bootcamp** in Gent.

## Description
The purpose of the project is to deploy a machine learning model that predicts prices in Belgium's real estate sales. The model is to be deployed on Render. To achieve this goal, an API capable of predicting real estate prices in Belgium was created during the [Immo Eliza Analysis](https://github.com/MykolaSenko/My_BeCode_Projects/tree/main/5_ImmoElizaAnalysis) based on a machine learning model. The API was deployed to [Render](https://immoeliza-api-yqiy.onrender.com). This API will allow web developers to build a website around it. FastAPI was chosen as the framework for implementing this project due to its capabilities and speed. After that, a Docker file containing all necessary code and environment was created.

The data required for prediction should be provided in the following format:
{
    "data": {
        "property_type": "str",
        "floor": "NonNegativeInt",
        "bedrooms_number": "NonNegativeInt",
        "habitable_surface": "NonNegativeFloat",
        "bathroom_number": "NonNegativeInt",
        "condition": "NonNegativeInt"
    }
}

To obtain the prediction, a POST request should be made to the API.

## Installation
To run the project instalations are not needed.

## Usage
The project is hosted at the URL: https://immoeliza-api-yqiy.onrender.com/. To make a price prediction, you should navigate to: https://immoeliza-api-yqiy.onrender.com/docs. On the documentation page, click on a "POST" bookmark. Than you will be prompted to input your data.
The result of the prediction will be given below the input section or somewhere on the page.

## Timeline
The project lasted 3 days July 26-28, 2023.

## Author
The project was made by Junior AI & Data Scientist Mykola Senko [LinkedIn](https://www.linkedin.com/in/mykola-senko-683510a4/) | [GitHub](https://github.com/MykolaSenko)

## Instruction
The project was made under the supervision of [Vanessa Rivera Quiñones](https://www.linkedin.com/in/vriveraq/) and [Samuel Borms](https://www.linkedin.com/in/sam-borms/?originalSubdomain=be)

## License
This project is under GPL License which allows to make modification to the code and use it for commercial purposes.

Gent, July 28, 2023.

[def]: image.png