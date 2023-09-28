# WebScrapingAPIService

This application is a Web Scraping API service that allows users to input a webpage URL and receive structured data scraped from that webpage.

## Prerequisites

Before you begin, make sure that you have a working installation of [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/).

## Setting Up and Running the Application

### Backend Setup

1. Navigate to the backend directory:
    ```bash
    cd path/to/backend-directory
    ```

2. Install the necessary Node.js dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root of the backend directory with your environment variables, for example:
    ```env
    WEB_SCRAPING_API_KEY=your-api-key-here
    PORT=8080
    ```
    Note: Port 3000 should be reserved for running the frontend of the application.

4. Start the backend server:
    ```bash
    npm start
    ```

### Frontend Setup:

1. Open a new terminal and navigate to the frontend directory:
    ```bash
    cd path/to/frontend-directory
    ```

2. Install the necessary Node.js dependencies:
    ```bash
    npm install
    ```

3. Start the frontend development server:
    ```bash
    npm start
    ```

The frontend server should open a new browser window/tab with the application running. If it doesn't, you can manually navigate to [http://localhost:3000](http://localhost:3000).

## Usage

1. Enter a URL into the input field.
2. Check if you want to obtain a screenshot of the scraped website as well.
3. Select the data you wish to scrape using the provided options.
4. Click the 'Scrape' button to initiate the web scraping process.
5. Once the data is scraped, it will be displayed on the website.
6. Press the 'Get Sentiment Analysis' button to obtain the overall sentiment of the scraped data.
7. Press the 'Download Scraped Text' button to download a JSON file with the scraped data.
8. Enter a URL of a blog post below, to count the words of its content.

![Screenshot of Web Scraping Application](https://github.com/denisafilip/WebScrapingAPIService/blob/main/websiteScreenshot.png)






