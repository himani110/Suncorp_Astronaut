# Astronaut API Testing

# Table of Content
- [Purpose&Objective](#purpose-and-objective)
- [Getting Started](#getting-started)
- [Prerequisites Links](#prerequisites-links)
- [Steps To Build This Project](#steps-to-build-this-project)
- [Features](#features)
- [Languages](#languages)
- [Technologies and Tools](#technologies-and-tools)


 # Purpose and Objective
The _Purpose_ of this document is to give the end user the high-level view of Unit testing performed while performing the validation of Astronaut API.
API endpoint : https://spacelaunchnow.me/api/ll/2.2.0/astronaut/

The _Objective_ is to provide user descriptive steps on how to execute it.
 
 # Getting Started

  *To get this project up and running on your local machine for development and testing purposes.* <li> Make sure all prerequisties are met  
<li> Clone this project on your machine by running  

     git clone 

Or you can simply download it from here 
<li> Open the project contents on your Postman 
<li> Click on the run button
  
  # Prerequisites Links
  - Postman: https://www.postman.com/
  - NodeJs: https://nodejs.org/en/
  - npm: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm
  - newman: https://www.npmjs.com/package/newman
  
 # Steps To Build This Project 
  There are two approach to achieve this :

 ### Approach 1 :
  
  **GUI || Using Postman > Runner  **
  
  Install Postman tool on your desktop, export the collection.json file, at run the collection.
  Below are the detailed Steps:
  1. Install the Postman tool on you desktop, using below link: https://www.getpostman.com/apps
  2. After successfully installation of Postman, Follow the steps for importing the collection.
  3. Download the repository from Github to your local system- It has “Astronaut.postman_collection.json” file.
  4. Go to Home > Import an existing file> upload “Astronaut.postman_collection.json” file
  5. Execute the collection Using Runner option.

  ### Approach 2 :
  
 **Command Line || Using Newman**
  
  Nemwan is an add-on for Postman.
  It is a command Line 
  Below are the steps:
  1. Install npm,if not installed.
  2. Open command line or Terminal and install Newman via npm  npm install -g newman
  3. Run your collection using this command: Newman run astronaut.postman_collection.json
  [*User is executing the command from the location where json file is exported]
  
#  Features
  
  ## Collection
  - GetAll
  - Get By Mode
  - Get By Filter
  - SearchByNationality
  
 ## Collection Variables
  - baseURL -> https://spacelaunchnow.me/api/ll/2.2.0
  - fil_nation > Nationality
  - searchBy > Chinese
  
  ## Report 
  - Console logs has been added for JavaScript Snippets
  - Postman report is generated.
  
  ## TestSummary Report

<table style="width:100%">
  <tr>
    <th>API's</th>
    <th>Test cases Executed</th>
    <th>Test cases Passed</th>
    <th>Test cases Failed</th>
  </tr>
  <tr>
    <td>GET ALL</td>
    <td>3</td>
    <td>2</td>
    <td>0</td>
  </tr>
  <tr>
    <td>GETByMode</td>
    <td>3</td>
    <td>2</td>
    <td>0</td>
  </tr>
  <tr>
    <td>GetByFilters</td>
    <td>2</td>
    <td>2</td>
    <td>0</td>
  </tr>
  <tr>
    <td>SearchbyNationlaity</td>
    <td>2</td>
    <td>2</td>
    <td>0</td>
  </tr>  
  <tr>
    <td>Total Test cases</td>
    <td>9</td>
    <td>9</td>
    <td>0</td>
  </tr> 
</table>

# Languages
  - javaScript Snippets 
  
# Technologies and Tools
  - Postman: [https://www.postman.com/]
  - NodeJs: [https://nodejs.org/en/]
  - npm: [https://www.npmjs.com/]
  - newman: [https://www.npmjs.com/package/newman]
  
<p> </p>
<h3 align="center"> I hope it help </h3>
