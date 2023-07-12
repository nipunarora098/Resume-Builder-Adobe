# PapyrusNebulae 2023 Document Cloud Hackathon: Round 2
## Problem Statement
The challenge is to create a Resume Builder API that utilizes the Adobe Document Generation API to generate PDF resumes from DOCX-based templates. The API should be able to receive user input data, such as personal information, skills, experiences, and education, and merge it with the chosen template to produce a formatted resume.
## Resume Builder API and UI
The Resume Builder project consists of an API and a user interface built with React. The API utilizes the Adobe Document Generation API to generate PDF resumes from pre-built templates and user-provided data. The frontend provides a user-friendly interface for users to fill in the necessary details and submit the form, which triggers the API request to generate the resume.
## Project Structure
  The project is structured as follows:
  ```shell
          resume-builder/
          |── ResumeTemplates                  # pre-built templates
          ├── api/                             # API server code
          ├── frontend-resume-builder/         # Frontend UI code
          ├── README.md                        # Project README file
  ```

## Features
The Resume Builder project includes the following features:
- Template Selection: Users can choose from a variety of pre-built resume templates to customize their resumes.
- User Input: Users can input their personal information, including contact details, skills, experiences, education, and any other relevant details required for the resume.
- Resume Generation: The API processes the user input and merges it with the selected template to generate a professional-looking resume in PDF format.
- PDF Download autmatically.
- Error Handling: The system handles and displays appropriate error messages in case of any issues or missing information during the resume generation process.
- API Integration: The API interacts with the Adobe Document Generation API to merge the template and user data, ensuring accurate and high-quality resume generation.
- Testing: Frontend and Backend includes unit tests to ensure the reliability and correctness of the API and frontend components.


## Prerequisites
Before setting up and running the project, ensure the following prerequisites are met:
- Node.js and npm (Node Package Manager) are installed on your machine.
  
## Installation and Setup
Technologies Used : React , Express 
To set up the project locally, follow these steps:

1. Clone the repository:
    ```shell
   git clone https://github.com/nipunarora098/Resume-Builder-Adobe.git
	
2. Setup Frontend .
   - Go to client directory
	```shell
	cd frontend-resume-builder

 
 - Install Dependancies
	```shell
 	npm init
  
	npm install
 - Start Frontend
 	```shell
 	npm start
2. Set up the API:
   - Go to api directory
	```shell
 	cd api
-  Install Dependancies
	```shell
 	npm init	
 	npm install
- Start backend
	```shell
 	npm run dev
