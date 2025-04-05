# Image-Resizer
A simple web-based image resizer tool that allows users to easily upload an image, adjust its dimensions (with an option to lock the aspect ratio), and download a resized version. Additionally, the tool provides an option to reduce the image quality when downloading.

# Features
Image Upload: Click the upload box or browse to select an image.

Dynamic Dimension Adjustment: Automatically fills in the image’s original width and height upon upload.

Aspect Ratio Lock: When enabled, resizing one dimension automatically adjusts the other.

Quality Reduction Option: Optionally reduce the quality of the image during the download.

Instant Download: Resized image is instantly available for download.

# Demo



# Getting Started
Prerequisites
To run the project, simply have a modern web browser installed. No additional installation or server setup is required.

#Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/image-resizer.git
cd image-resizer
Open the project:

Open index.html in your preferred web browser.

# Project Structure
graphql
Copy
Edit
image-resizer/
├── index.html       # Main HTML file that structures the app layout.
├── style.css        # CSS file for styling the app.
├── script.js        # JavaScript file containing the functionality to handle image resizing and download.
└── resources/       # Folder containing images and other assets.

# How It Works
Upload an Image:
Click on the upload box to select an image file. The image preview will appear once uploaded.

Adjust Dimensions:
The original dimensions are loaded automatically. Modify the width or height as desired. With the aspect ratio lock enabled, the other dimension will adjust accordingly.

Quality Control:
Toggle the "Reduce quality" checkbox if you want the image to be saved with lower quality (70% of original).

Download Resized Image:
Click the "Download" button to generate and save the resized image to your device.

Customization
CSS: Modify style.css to change the look and feel of the application.

JavaScript: Enhance functionality or add more features by editing script.js.

# Contributing
Contributions are welcome! If you have suggestions or improvements, please feel free to create an issue or submit a pull request.

# License
This project is licensed under the MIT License.
