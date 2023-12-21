# AItinerary
AItinerary is an innovative travel planning platform that leverages artificial intelligence to revolutionize the way users create personalized travel itineraries. The system combines advanced natural language processing, ChatGPT integration, and Unsplash APIs to understand user preferences and generate comprehensive travel plans with pictures.

* Front End: React and Vite
* Back End: AWS Lambda Functions
* Hosted Website: https://aitinerary.net
  
# Project Structure
The project is organized into several components:

* front-end Folder: Contains the React and Vite code for the front-end user interface.

* lambda-chatgpt-integration Folder: Includes the Lambda function code for ChatGPT integration.

* lambda-place-extractor Folder: Holds the Lambda function code for extracting major places using ChatGPT.

* lambda-unsplash-api Folder: Contains the Lambda function code for integrating with the Unsplash API.

# Lambda Functions:
Create three Lambda functions in your AWS account.

For each Lambda function, upload the respective ZIP file found in the corresponding folder (lambda-chatgpt-integration, lambda-place-extractor, lambda-unsplash-api).

Set the required environment variables, including the ACCESS_KEY for Unsplash API, in the Lambda function configurations.

# Access Key Configuration:
Ensure that you've configured the ACCESS_KEY in the environmental variables of the Lambda functions:
OPENAI_API_KEY: Configure and add the OPENAI_API_KEY for Chatgpt API's
lambda-unsplash-api: Configure the ACCESS_KEY for Unsplash API.

# Additional Notes:
Refer to the provided architecture document for an overview of the project.

The hosted website is available at https://aitinerary.net.

# Contributors
Amogha Manjunatha Kuruvadi
Arpan Mondal
Indrasena Kalyanam
