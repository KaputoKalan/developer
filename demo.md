Create a Chrome Manifest V3 extension that, when clicked on a LinkedIn search results page, opens a small window with a page designed to scrape the search results and collect the name and contact information of the displayed profiles.

The extension should have the following requirements:

The extension must be compatible with Chrome Manifest V3.

The extension should be activated when the current page is a LinkedIn search results page.

When the extension is clicked on a LinkedIn search results page, it should open a small window containing a page specifically designed for scraping the search results.

The page in the small window should automatically extract the name and contact information of each displayed profile on the search results page.

The extension should only extract data from the profiles displayed on the current search results page.

The extracted data should include the name and contact information of the profiles.

The extension should store the collected data in memory for further processing and export.

The page in the small window should display the collected data, showing the name and contact information of the profiles.

The extension should include a button on the page in the small window that, when clicked, exports the collected data as a CSV file.

The exported CSV file should include the name and contact information of the profiles, formatted appropriately for CSV.

The extension should use Chrome's storage API to store the collected data in memory.

The extension should handle any errors or exceptions gracefully and provide appropriate error messages to the user if necessary.

Please note that scraping LinkedIn's website may potentially violate their terms of service. It's important to review and comply with LinkedIn's policies to avoid any legal issues.

The extension should be implemented using a combination of JavaScript, HTML, and CSS. The necessary files for the extension should include manifest.json, popup.html, popup.js, styles.css, background.js, content_script.js, and shared_dependencies.md, similar to the original prompt.
