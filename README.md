# Tesla Stock Trade Dashboard

## Overview

Tesla Stock Trade Dashboard is a web application that provides a user-friendly interface for monitoring and analyzing Tesla stock trades. The dashboard is built using HTML, Bootstrap, JavaScript, Google Charts, and requires a valid API key for fetching real-time stock data.

## Features

- Real-time Tesla stock data visualization using Google Charts.
- User-friendly interface with Bootstrap for a responsive design.
- Interactive charts for better analysis of stock trends.
- Integration with a third-party API for fetching live stock data.

## Technologies Used

- HTML
- Bootstrap
- JavaScript
- Google Charts
- AlphaVentage is used for fetching live stock data (Replace CWZM20VHC0WG0X31 ley with the actual name of the API you're using)

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/SidharthaPaidi/Tesla-Stock-Trade-Dashboard.git
    cd Tesla-Stock-Trade-Dashboard
    ```

2. Obtain an API key:

    - Visit [https://www.alphavantage.co/] to obtain your API key.
    - Copy the API key and replace `[YOUR_API_KEY]` in the code with your actual key.

3. Open `index.html` in your web browser or deploy the project to a web server.

## Usage

- Open the dashboard in your web browser.
- Explore the Tesla stock data visualizations.
- Customize the dashboard as needed.

## API Key Configuration

Replace `[YOUR_API_KEY]` in the code with your actual API key. This key is required for fetching live stock data.

```javascript
// Example API Key Configuration in JavaScript
const apiKey = 'YOUR_API_KEY';
// Replace 'CWZM20VHC0WG0X31' with your actual API key
