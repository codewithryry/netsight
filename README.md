# NetInsight

NetInsight is a web application that provides detailed insights about your network, including IP address information, geolocation, network speed, and device/browser details. It’s built using HTML, CSS, and JavaScript, with external libraries for styling and functionality.

## Features

- **Dark Mode Toggle**: Switch between light and dark themes.
- **IP Address Display**: Shows the user’s current IP address.
- **IP Details**: Fetches and displays information about the user’s IP, such as ISP, city, country, etc.
- **Geolocation Map**: Displays a map showing the user's location based on IP.
- **Network Speed Test**: Measures and displays download, upload, and ping speeds.
- **Browser & Device Information**: Displays relevant information about the user’s browser and device.

## Getting Started

### Prerequisites

- A modern web browser to load the application.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/NetInsight.git
    ```

2. Open the `index.html` file in your browser.

### Usage

1. Open `index.html` in a browser.
2. Use the toggle to switch between dark and light mode.
3. View your IP details, geolocation, and perform a speed test by clicking the "Start Speed Test" button.
4. Browser and device information is automatically displayed under the respective section.

## Project Structure

- `index.html`: The main HTML structure of the web app.
- `styles.css`: Contains styling for the web app.
- `script.js`: JavaScript logic for fetching IP, performing the speed test, and other interactivity.

## Future Improvements

- Add a server-side backend for more advanced IP and geolocation details.
- Improve the speed test by implementing more detailed metrics.
- Enhance error handling for cases when IP or geolocation data isn’t available.

