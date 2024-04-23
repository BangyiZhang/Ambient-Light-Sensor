# LightSense Web

## Project Overview

**LightSense Web** is a website that utilizes the Ambient Light Sensor API (Device Light API) to report real-time environmental light intensity and has the capability to collect light intensity data over a period of time. The goal of this project is to provide real-time ambient light data to help users understand the lighting conditions around them.

## Technology Stack

- **Ambient Light Sensor API (Device Light API)**: Used to detect the ambient light levels around the device.
- **Programming Languages**: HTML5, JavaScript.
- **Database**: MongoDB, used for storing light data.
- **Backend Framework**: Node.js, managing server-side logic and database interactions.

## Installation Guide

### Prerequisites

Ensure your machine has Node.js and MongoDB installed. You can download and install them from their official websites:

- [Node.js Official Website](https://nodejs.org/)
- [MongoDB Official Website](https://www.mongodb.com/try/download/community)

### Installation Steps

1. **Clone or Download the Project** Clone the project repository to your local machine:

   ```
   bashCopy code
   git clone https://github.com/BangyiZhang/Ambient-Light-Sensor.git
   cd Ambient-Light-Sensor
   ```

2. **Install Dependencies** Navigate to the `server` directory within the project and install the necessary npm packages:

   ```
   bashCopy code
   cd server
   npm install
   ```

3. **Start MongoDB** Start the MongoDB database service. Depending on your operating system, this may involve running the `mongod` command or starting the MongoDB service through a service manager.

4. **Run the Application** Within the `server` directory, run the following command to start the Node.js server:

   ```
   bashCopy code
   node app.js
   ```

5. **Access the Frontend Application** Open the `index.html` file in a browser or access it through the configured server address, typically [http://localhost:3000](http://localhost:3000/).

## Usage Instructions

- Upon opening the website, the page will display the current ambient light intensity.
- Through the website interface, you can start and stop the data collection feature, which will store light intensity data in the backend database.
