# AzureOAIProjectChallenge

## Main objectives
* Create a simple application for Azure Open AI to automate the QnA of a mock company.

## What to consider when creating an Azure Open AI solution
![Image Description](https://github.com/amticianelli/AzureOAIProjectChallenge/blob/main/img/image_projectreq.png)

## 1.0 Business description
### Techtronics Inc.
Techtronics Inc.
Company Overview
Techtronics Inc. is a leading innovator in the smart home technology space. Our mission is to enhance the everyday lives of our customers through intuitive, reliable, and eco-friendly smart devices.



## 2.0 Business needs
* Techtronics has all their products mapped, they have all the descriptions on their webside but the detailed technical information are inside pdf files.
* Techtronics wants to automate their QnA about their products by using their PDFs, they will make the Chat public available.

## 3.0 Requirements
* Techtronics wants to use a simple Chatbot application
* The POC can be created using the following repo: https://github.com/microsoft/sample-app-aoai-chatGPT
* The example data is inside the directory: mockdata

    ### 3.1 Installation / How to create the basic environment
    * Install Docker Desktop, download it on the following link: https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe
    
    * Install Docker Desktop using Powershell
    ```powershell
    "Docker Desktop Installer.exe" install
    Start-Process 'Docker Desktop Installer.exe' -Wait install
    start /w "" "Docker Desktop Installer.exe" install
    ```

    * On your Visual Studio code, install Dev Container module
    * Clone the sample chat repository
    ```powershell
    git clone https://github.com/microsoft/sample-app-aoai-chatGPT
    ```

    * When opening the project locally, click on the left bottom option and select: "Reopen in container"

    ### 3.2 Configure
    * Following the steps to start the sample chat application, edit the .env file and set to your environment

## 4.0 Goals
* Goals to be achieved (only the main one is required)

    ![Image Description](https://github.com/amticianelli/AzureOAIProjectChallenge/blob/main/img/simple_appflow.png)
    ### 4.1 Main
    * Use the customer data to answer the questions based on his data only
    * After succeeding in answering the questions, use Copilot Designer to create a logo to the company and change it inside the chatbot

    ### 4.2 Extra
    * Are the prompts accurate? What can be changed to achieve a better response?
    * Publish the application in Azure App Services
   
    
    ## 4.3 Epic
    * The customer want to know what are being asked in the application, so they can best enhance their clients' experience. Extend the application by storing the prompts in Azure Cosmos DB.


## 5.0 Sending the result
* Validation still TBD
