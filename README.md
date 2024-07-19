# Conflict-Analytics-Lab

## Table of Contents
1. Description
2. Tech Assets
3. Usage
4. Features
5. Data Sources
6. Troubleshooting
7. Costs involved
8. Passwords and credentials
9. Contact Information
   
## Description
The OpenJustice AI, developed by the Conflict Analytics Lab, is a specialized GPT designed for the legal field. Its primary aim is to assist professional groups in effectively addressing their legal challenges. As this project marks the early stages of the platform's deployment, understanding current user engagement and platform performance is crucial. The insights gained will enable targeted improvements, enhancing the platform's capability to track, analyze, and respond to user interactions effectively. This, in turn, will improve the platform's usability, ensuring it meets the needs of the community and maximizes its societal benefits.

This repository contains all the project files organized into four main folders:
- **Dashboards**: Contains user guides for different pages of the dashboard and the link to access the dashboard, which is editable (client only).
- **Research Files**: Contains documented raw research work done for client update meetings.
- **Weekly Updates**: Summarized slide decks for weekly meetings with client feedback in red text.
- **Code Files**: Includes proof of concept code demos for evaluating the current GPT performance, with actual data blurred due to the signed NDA.

## Tech Assets
The project utilizes several Google Cloud tools to align with clients' current working environment, including:
- Looker Studio
- Vertex AI
- BigQuery
- Firestore
- Cloud Storage (optinal)

And prerequisites including:
- Python
- Google Cloud SDK
- Required Python libraries (listed in the code files)
Access details for these tools and prerequisites were well explained to clients or already set in their environment, so they won't be displayed here due to NDA restrictions.

## Usage
As the code demo is built on their Google Cloud (notebook with comments and explanations) with customized connections, no specific instructions are needed to run the code. The usage of the dashboard is thoroughly explained in the user guide found in the **Dashboards** folder.

## Features
- List of documentations of proposals on metrics (including both Google Analytics and conversation data from their GPT model)
- Customizable dashboards in Looker Studio

## Data Sources
The data used in this project are internal to Conflict Analytics Lab, comprising two primary sources:
- **Google Analytics**: Contains web page data such as traffic attribution and user behaviors, directly connected to the dashboard.
- **Firestore**: Contains legal AI conversational data, which is processed, evaluated, and stored in BigQuery to facilitate dashboard connectivity.
  
## Troubleshooting
- Ensure Google Cloud credentials are correctly set up.
- Check for necessary permissions on Google Cloud services.
- Verify that all required Python libraries are installed.

## Costs involved
Monthly costs are associated with using Google Cloud services and these costs are covered by the client (Conflict Analytics Lab).

## Passwords and credentials
There are no passwords required for this project. All necessary links for client access are included in this repository, with permissions granted during the initial project stage.

## Contact Information
For any questions or concerns, please contact:
- Name: Alisa Liu
- Email: ziyang.liu@mail.mcgill.ca
- GitHub: https://github.com/18ZL107


