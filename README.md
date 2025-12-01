# Web Scraper

A powerful Java-based web scraper with a GUI that automatically collects and organizes data from websites. Extract text, links, images, and more with an intuitive user interface.

## Features

- **GUI Interface**: User-friendly Swing-based desktop application
- **Multiple Data Types**: Extract text, links, images, and metadata from web pages
- **Custom Data Structures**: Implements custom Queue (QueueDSA) for efficient data handling
- **URL Support**: Scrape multiple URLs with error handling
- **Export Options**: Save scraped data to files
- **SSL/TLS Support**: Handle secure connections
- **Regex Filtering**: Advanced text pattern matching and filtering
- **Real-time Processing**: Live scraping with progress updates

## Project Structure

```
Web_Scraper/
├── src/
│   └── WebScraperApp.java       # Main application class with GUI
├── lib/                          # External libraries (JSoup, etc.)
├── run.bat                       # Windows batch runner
├── run.ps1                       # PowerShell runner
├── README.md                     # This file
├── LICENSE                       # Project license
└── Web_Scraper.iml              # IntelliJ IDEA project file
```

## Requirements

- **Java 8+**
- **JSoup Library** (included in lib/)
- Windows/Linux/macOS

## Running the Application

### Windows (Batch)
```bash
run.bat
```

### Windows (PowerShell)
```bash
.\run.ps1
```

### Command Line (All Platforms)
```bash
javac -cp lib/* src/WebScraperApp.java
java -cp lib/*:src WebScraperApp
```

## Usage

1. Launch the application
2. Enter the URL of the website you want to scrape
3. Select the data types to extract (text, links, images, etc.)
4. Click "Scrape" to start the process
5. Review results in the GUI
6. Export or save data as needed

## Technical Details

- **Custom Data Structure**: Implements a circular queue with O(1) operations
- **HTML Parser**: Uses JSoup library for reliable HTML parsing
- **Multi-threaded**: Handles network requests efficiently
- **Error Handling**: Gracefully handles SSL, network, and parsing errors

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Abdul-Kabeer78

