# Wink to Scroll

## Project Overview
"Wink to Scroll" is a web application that allows users to scroll through a webpage using eye winks. The application utilizes OpenCV along with HTML, CSS, and JavaScript to detect winks through the user's webcam and automatically scroll the page.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Folder Structure](#folder-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- Detects winks using the webcam.
- Scrolls the webpage up or down based on wink direction.
- Simple and intuitive interface.

## Technologies Used

### Frontend
- **HTML**: For structuring the content of the application.
- **CSS**: For styling and layout.
- **JavaScript**: For adding interactivity and handling OpenCV integration.

### Computer Vision
- **OpenCV**: For detecting winks via the webcam.

## Installation

### Prerequisites
- A modern web browser
- Python (for running a local server, if needed)
- Git

### Clone the repository
```bash
git clone https://github.com/LokeshS1411/wink-to-scroll.git
cd wink-to-scroll
```
## Running the Project

Simply open the `index.html` file in your browser. Ensure that your webcam is enabled, as the application will request access to it to detect winks.

## Folder Structure
```
wink-to-scroll/
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── index.html
└── README.md
```

## Future Enhancements
- Improve the accuracy of wink detection.
- Add support for custom gestures.
- Implement functionality to control other aspects of the browser, such as clicking or navigating between pages.

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
