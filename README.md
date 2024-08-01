
News & Metadata Search Application
Overview
The News & Metadata Search Application is a versatile tool designed to search for news articles related to a person, city, country, and keywords from various sources, including NewsAPI, Lovin Malta, and Times of Malta. Additionally, the application allows users to extract metadata from image files, including GPS coordinates and the country information based on these coordinates.

Features
News Search: Search for news articles using a person's name, city, country, and keywords.
Multiple Sources: Fetch articles from NewsAPI, Lovin Malta, and Times of Malta.
Metadata Extraction: Extract and display metadata from image files, including GPS coordinates and reverse geocoded country information.
Save Results: Save the search results in either JSON or CSV format.
Drag-and-Drop Support: Easily drag and drop image files into the application for metadata extraction.
Scrollable Results: Browse search results and metadata comfortably with a scrollable interface.
Prerequisites
Python 3.x
Required Python libraries:
requests
beautifulsoup4
Pillow
tkinterdnd2
tkinter
Installation
Clone the Repository

sh
Copy code
git clone https://github.com/yourusername/news-metadata-search.git
cd news-metadata-search
Install Required Libraries

sh
Copy code
pip install requests beautifulsoup4 Pillow tkinterdnd2
Usage
Run the Application

sh
Copy code
python app.py
Search for News Articles

Enter the person's name, city, country, and keywords into the respective fields.
Provide your NewsAPI key.
Click on the "Search" button to fetch articles from the available sources.
The results will be displayed in the results pane.
Save Search Results

Click on the "Save Results" button to save the fetched articles in JSON or CSV format.
Extract Image Metadata

Drag and drop an image file (PNG, JPG, JPEG, TIFF) into the application window.
The extracted metadata will be displayed in the results pane.
Notes
NewsAPI Key: You must provide your own NewsAPI key to use the news search functionality. You can obtain an API key by signing up at NewsAPI.
Reverse Geocoding: The application uses OpenStreetMap's Nominatim service for reverse geocoding GPS coordinates extracted from image metadata.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

Acknowledgements
NewsAPI
Lovin Malta
Times of Malta
OpenStreetMap Nominatim
