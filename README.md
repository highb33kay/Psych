# Psychology Test Software

This is a Node.js-based psychology test software that allows administrators to set up tests in the backend and users to take tests in the frontend.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Available Tests](#available-tests)
  - [Consent Form](#consent-form)
  - [SCL-90](#scl-90)
  - [PCL-R](#pcl-r)
- [Compulsory Forms](#compulsory-forms)
- [Other Forms](#other-forms)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This application provides a platform for conducting psychological tests. Admins can set up various tests in the backend, and users can take these tests in the frontend.

## Getting Started

### Prerequisites

To run this application, you'll need:

- Node.js (Version X.X.X)
- npm (Node Package Manager)
- MongoDB (for storing test data)

### Installation

1. Clone this repository:

   ```
   git clone https://github.com/yourusername/psychology-test-app.git

2. Navigate to the project directory:

``` 
cd psychology-test-app

```

3. Install the required dependencies:

```
npm install
```

4. Configure the MongoDB connection in the .env file:
```
makefile

MONGODB_URI=your_mongodb_uri_here
```

5. Start the application:

```
npm start
```

### Available Tests
- **Consent Form**
  - Description: The Consent Form is an essential document used to inform participants about the purpose, procedures, and risks associated with research or assessment activities.

- **SCL-90**
  - Description: The Symptom Checklist-90 (SCL-90) is a self-report inventory used to evaluate a broad range of psychological symptoms and distress in individuals.

- **PCL-R**
  - Description: The Psychopathy Checklist-Revised (PCL-R) is a comprehensive tool used to evaluate personality traits and behaviors associated with psychopathy.

- **Compulsory Forms**
  - These forms are compulsory to fill out before accessing the other screening forms. After completing these forms, users can access the remaining screening forms from the links below.

- **Other Forms**
  - **Alcohol Screening Questionnaire (AUDIT)**
    - Description: The Alcohol Use Disorders Identification Test (AUDIT) is a widely used screening tool designed to assess alcohol consumption patterns and identify potential alcohol-related problems in individuals.
  - **TIPI**
    - Description: TIPI stands for Ten-Item Personality Inventory, a brief self-report questionnaire aimed at providing a rapid assessment of an individual's personality traits.
  - **Assist Screening Tool**
    - Description: The Alcohol, Smoking, and Substance Involvement Screening Test (ASSIST) is utilized to identify and evaluate substance use and related risks in individuals.
  - **DAST-10**
    - Description: The Drug Abuse Screening Test (DAST-10) is a concise instrument employed to assess drug abuse and potential addiction issues in individuals.
  - **Self Efficacy**
    - Description: This questionnaire assesses an individual's belief in their ability to accomplish specific tasks and handle various situations effectively.
  - **Trauma Screen**
    - Description: This screening tool aims to identify individuals who may have experienced traumatic events or are displaying symptoms associated with trauma.
  - **Psychological Functioning**
    - Description: This assessment form gathers information about an individual's overall psychological functioning, including emotional well-being and coping mechanisms.
  - **Index of Self Esteem (ISE)**
    - Description: The Index of Self-Esteem (ISE) is a self-report questionnaire designed to measure an individual's level of self-esteem and self-worth.
  - **PD Scale**
    - Description: The PD Scale is a screening instrument used to assess personality traits and symptoms related to various personality disorders.

Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.