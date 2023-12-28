# SUCredit

## Overview
The goal of the SUCredit is to develop a mobile application specifically designed for Sabanci University students. This app aims to track and calculate the total SU and ECTS credits, including basic science and engineering credits, that a student has earned, and determine the remaining credits required for graduation. 

## Objective and Scope
- **Functionality**: The app allows students to calculate their accumulated credits and categorizes them into engineering and basic science credits. 
- **User Interface**: Features a login page, a program selection page for choosing majors, and a detailed course page with checkboxes to mark completed or future courses.
- **Utility**: Offers insights into total science and engineering credits and students' graduation status based on course selections.

## Backend Architecture and Web API
- **Get All Majors and Programs**: Provides a list of all majors and programs with details like ID and name.
- **Get All Courses**: Returns a comprehensive list of courses categorized by faculty, including ID, name, faculty, credit type, and value.
- **Get Courses by Major ID**: Lists courses specific to a chosen major, detailing ID, name, credit type, and value.
- **Get Basic Science and Engineering Credits for Courses**: Details courses and their values for basic science and engineering credit types.

## Response Fields
- **serviceMessageCode**: Indicates the success or failure of requests.
- **serviceMessageText**: Descriptive text for the request outcome.
- **items**: List of items returned by the API.

### Additional Backend Features
- Caching for optimized load times.
- Server-side data validation for integrity.
- SSL encryption and authentication for security.
- API rate limiting to prevent abuse.
- Robust error handling for reliability.

## Technologies Used
- **Backend**: Docker, MongoDB.
- **Data Fetching**: Postman.
- **Frontend Development**: Android Studio, Java.
