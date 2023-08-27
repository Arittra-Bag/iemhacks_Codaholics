# YouTube Summary Extension for Any Browser

![Extension Logo](extension/images/icon.png)

## Table of Contents

- [Problem Statement](#problem-statement)
- [Overview](#overview)
- [Features](#features)
- [Installation and Usage](#installation-and-usage)
- [Contributing](#contributing)
- [License](#license)
- [Team](#team)

## Problem Statement

To make an extension which can summarize the content of any YouTube video by providing its transcript.

## Overview

The YouTube Summary Extension is a browser extension that simplifies and enhances your YouTube experience by providing concise summaries of video transcripts. It allows users to quickly grasp the content of videos, saving time and improving comprehension.

## Features

- **Transcript Summarization**: Automatically generates a summary of the video transcript.
- **User-Friendly Popup**: A user-friendly interface with a single "Summarise" button.
- **Modern UI**: A sleek and modern user interface for a pleasant user experience.
- **Cross-Browser Compatibility**: Compatible with popular web browsers (Chrome, Firefox, Edge, etc.).

## Installation and Usage

### Prerequisites

- Python installed on your system.

#### 1. Clone the Repository

You can clone the GitHub repository containing the extension code to your local machine using the following command:

```bash
git clone https://github.com/yourusername/your-extension-repo.git
```

#### 2. Install Required Dependencies

Navigate to the project directory and install the required dependencies using pip (Python's package manager):

```bash
cd your-extension-repo
pip install -r requirements.txt
```

#### 3. Set Up the Backend

Run the backend server by executing `app.py`:

```bash
python app.py
```

This will start the backend server, which is responsible for processing data for the extension.

#### 4. Install the Extension

**For Chrome:**

1. Open the Chrome browser.
2. Go to `chrome://extensions/`.
3. Enable "Developer mode" in the top right corner.
4. Click on "Load unpacked" and select the `extensions` folder from your cloned repository.

**For Firefox:**

1. Open the Firefox browser.
2. Type `about:debugging` in the address bar.
3. Click on "This Firefox" on the left sidebar.
4. Click on "Load Temporary Add-on" and select any file in the `extensions` folder from your cloned repository.

#### 5. Use the Extension

1. Visit YouTube and play a video.
2. Click on the YouTube Summary Extension icon in the browser toolbar.
3. Click the "Summarise" button.
4. The video's summary will appear in the popup.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Team

**Team Name: Codaholics**

- Argha Dey ([GitHub](https://github.com/arghadey22))
- Arittra Bag ([GitHub](https://github.com/Arittra-Bag))
- Aalok Shaw ([GitHub](https://github.com/shawaalok2003))
- Soumi Guria ([GitHub](https://github.com/soumiguria))
