# Conflict-Analytics-Lab

## Table of Contents
1. [Description](#description)
2. [Tech Assets](#techassets)
3. [Usage](#usage)
4. [Features](#features)
5. [Data Sources](#datasources)
6. [Troubleshooting](#troubleshooting)
7. [Costs involved](#costsinvolved)
8. [Passwords and credentials](#passwordsandcredentials)
9. [Contact Information](#contactinformation)
   
## Description
The OpenJustice AI, developed by the Conflict Analytics Lab, is a specialized GPT designed for the legal field. Its primary aim is to assist professional groups in effectively addressing their legal challenges. As this project marks the early stages of the platform's deployment, understanding current user engagement and platform performance is crucial. The insights gained will enable targeted improvements, enhancing the platform's capability to track, analyze, and respond to user interactions effectively. This, in turn, will improve the platform's usability, ensuring it meets the needs of the community and maximizes its societal benefits.

This repository contains all the project files organized into four main folders:
- **Dashboards**: Contains user guides for different pages of the dashboard and the link to access the dashboard, which is editable (client only).
- **Research Files**: Contains documented raw research work done for client update meetings.
- **Weekly Updates**: Summarized slide decks for weekly meetings with client feedback in red text.
- **Code Files**: Includes proof of concept code example in PDF format for evaluating the current GPT performance, with actual data blurred due to the signed NDA. And the actual code is set up in client's Google Cloud environment.

The single PDF file, "Solution", is an all-in-one final document, which summarize all the essential information or instruction for this project while the folders mentioned above are categorized raw files.

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

Access details for these tools and prerequisites were already set in their environment, so they won't need any extra set up to access to this solution.

## Usage
As the code demo is built on their Google Cloud (notebook with comments and explanations) with customized connections, no extra steps are needed to run the code. The usage of the dashboard is thoroughly explained in the user guide found under the **Appendix** section in **Solution** file or under the **Dashboards** folder.

## Features
- Proposals on metrics (including both Google Analytics and conversation data from their GPT model)
- Proposals on the future user feedback mechanism
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


