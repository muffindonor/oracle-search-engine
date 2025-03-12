# BadgerSearch

## Overview
BadgerSearch is a custom search engine developed as part of a college course project by a team of students. The project’s primary goal is to crawl select pages from the Oracle website, extract and index the words found on those pages, and store them in a Firebase database. Users can then perform searches using a simple search bar, with the results based on the words extracted from Oracle’s pages.

In addition to its core functionality, BadgerSearch includes:
- An **Admin Tab** for data management and review, accessed with the password: 123456
- A **Statistics Tab** that visualizes database information using graphs.
- A **Music Player** to enhance user experience, because why not.

## Features
- **Oracle Website Crawling**: Automatically retrieves and processes content from specified Oracle pages.
- **Firebase Integration**: Stores the extracted words and related data in a Firebase database.
- **Search Functionality**: Allows users to input search terms and returns results based on the indexed content.
- **Admin Interface**: Provides tools for administrators to manage the stored data and monitor system performance.
- **Data Visualization**: Displays statistical data via graphs to offer insights into the search engine’s underlying data.
- **Music Player**: A built-in music player adds an element of entertainment to the application.

## Technologies Used
- **Python & Jupyter Notebook**: Core logic and data processing are implemented using Python in a Jupyter Notebook environment.
- **Firebase**: Utilized as the backend database for storing and managing indexed words.
- **Web Scraping Tools**: Employed for fetching and parsing content from Oracle’s web pages.
- **HTML/CSS/JavaScript**: For building the web interface, including the search bar, admin, and statistics pages.
- **Graphing Libraries**: Libraries such as Chart.js (or similar) are used to render graphs for the statistics tab.

## Setup and Installation

1. Click 'Open in Collab' in BadgerSearch.ipynb
2. In the colab page, click Runtime -> Run all
3. Use the app's UI to search terms extracted from Oracle's pages
