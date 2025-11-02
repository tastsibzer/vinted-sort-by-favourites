# 💖 Vinted "Sort by Likes" Scraper

## 📝 Description

This script allows you to search for items on Vinted and sort the results by the number of "likes" (hearts), a feature not natively available on the platform. It automates the process of finding the most popular items by scraping search results across multiple pages and re-ordering them based on the like count.

## ✨ Features

-   **💖 Sort by Popularity:** Automatically scrapes and re-orders Vinted search results based on the number of likes.
-   **🎨 Customizable Searches:** Specify the search term, gender, size, and an optional maximum price.
-   **🤖 Automated Browsing:** Uses Puppeteer to navigate through multiple pages of search results effortlessly.
-   **⌨️ Interactive CLI:** A simple command-line interface guides you through setting up your search criteria.

## 📋 Requirements

Before you begin, ensure you have the following installed on your system:

-   **🟢 Node.js:** A JavaScript runtime environment.
-   **📦 npm (Node Package Manager):** Included with the Node.js installation.
-   **🌐 Google Chrome:** The script uses Puppeteer which controls a Chrome browser instance.

## 🚀 Usage

1.  **📥 Download and Extract:**
    Extract the `.zip` file to your desired folder.

2.  **📂 Navigate to Project Directory:**
    Open your terminal or command prompt and use the `cd` command to navigate into the project folder.

3.  **🛠️ Install Dependencies:**
    Run the following command to install the necessary packages:
    ```bash
    npm update
    ```

4.  **▶️ Run the Script:**
    Execute the following command in your terminal:
    ```bash
    node index.js
    ```

5.  **💬 Follow the On-Screen Prompts:**
    The script will ask for your search details (term, pages, price, gender, and size).

6.  **👀 View the Results:**
    A new Chrome window will open and begin the search. Once finished, the results will be displayed in that window, sorted from most to least liked.

> **⚠️ Important:** Do not interfere with the running script by clicking anything on the website. The browser window needs to be maximized to work properly.

## 📜 Disclaimer

This is an unofficial tool and is not affiliated with Vinted. It is intended for personal use only. Please be mindful of Vinted's terms of service when using this script. The author is not responsible for any potential consequences of its use.