    <h1>💖 Vinted "Sort by Likes" Scraper</h1>

    <h2>📝 Description</h2>
    <p>
        This script allows you to search for items on Vinted and sort the results by the number of "likes" (hearts), a feature not natively available on the platform. It automates the process of finding the most popular items by scraping search results across multiple pages and re-ordering them based on the like count.
    </p>

    <h2>✨ Features</h2>
    <ul>
        <li><strong>💖 Sort by Popularity:</strong> Automatically scrapes and re-orders Vinted search results based on the number of likes.</li>
        <li><strong>🎨 Customizable Searches:</strong> Specify the search term, gender, size, and an optional maximum price.</li>
        <li><strong>🤖 Automated Browsing:</strong> Uses Puppeteer to navigate through multiple pages of search results effortlessly.</li>
        <li><strong>⌨️ Interactive CLI:</strong> A simple command-line interface guides you through setting up your search criteria.</li>
    </ul>

    <h2>📋 Requirements</h2>
    <p>Before you begin, ensure you have the following installed on your system:</p>
    <ul>
        <li><strong>🟢 Node.js:</strong> A JavaScript runtime environment.</li>
        <li><strong>📦 npm (Node Package Manager):</strong> Included with the Node.js installation.</li>
        <li><strong>🌐 Google Chrome:</strong> The script uses Puppeteer which controls a Chrome browser instance.</li>
    </ul>

    <h2>🚀 Usage</h2>
    <ol>
        <li>
            <strong>📥 Download and Extract:</strong><br>
            Extract the <code>.zip</code> file to your desired folder.
        </li>
        <li>
            <strong>📂 Navigate to Project Directory:</strong><br>
            Open your terminal or command prompt and use the <code>cd</code> command to navigate into the project folder.
        </li>
        <li>
            <strong>🛠️ Install Dependencies:</strong><br>
            Run the following command to install the necessary packages:
            <pre><code style="background: #f4f4f4; padding: 5px 10px; border-radius: 5px;">npm update</code></pre>
        </li>
        <li>
            <strong>▶️ Run the Script:</strong><br>
            Execute the following command in your terminal:
            <pre><code style="background: #f4f4f4; padding: 5px 10px; border-radius: 5px;">node index.js</code></pre>
        </li>
        <li>
            <strong>💬 Follow the On-Screen Prompts:</strong><br>
            The script will ask for your search details (term, pages, price, gender, and size).
        </li>
        <li>
            <strong>👀 View the Results:</strong><br>
            A new Chrome window will open and begin the search. Once finished, the results will be displayed in that window, sorted from most to least liked.
        </li>
    </ol>

    <div style="background-color: #fffbe6; border-left: 4px solid #ffeb3b; padding: 10px 15px; margin-top: 20px;">
        <p><strong>⚠️ Important:</strong> Do not interfere with the running script by clicking anything on the website. The browser window needs to be maximized to work properly.</p>
    </div>

    <h2>📜 Disclaimer</h2>
    <p>
        This is an unofficial tool and is not affiliated with Vinted. It is intended for personal use only. Please be mindful of Vinted's terms of service when using this script. The author is not responsible for any potential consequences of its use.
    </p>