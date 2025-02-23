# Umbrella

This project is a simple, client-side web application that allows users to customize an umbrella by uploading a logo. It provides an instant preview of the umbrella with the uploaded logo and allows users to change the umbrella's color.

## Features

* **Logo Upload:** Users can upload a logo in PNG or JPG format to be displayed on the umbrella.
* **Instant Preview:** The uploaded logo is immediately displayed on the umbrella preview.
* **Color Switching:** Users can change the umbrella's color using color swatches.
* **File Information:** Displays the uploaded file's name and provides a button to remove it.
* **Simple Implementation:** Built using only HTML, CSS, and JavaScript, without any external libraries or frameworks.


## Usage

1.  **Clone the repository:**
    ```bash
    git clone [repository_url]
    ```
2.  **Open `index.html` in your web browser:**
    * You can open the file directly from your file system.
    * Alternatively, you can use a local server (e.g., VS Code's Live Server) for development.
3.  **Customize the Umbrella:**
    * Click on a color swatch to change the umbrella's color.
    * Click the "UPLOAD LOGO" button to select and upload a logo file.
    * The logo will be displayed on the umbrella preview.
    * The file name will be displayed next to the upload button, with a close button to remove the logo.

## File Structure
custom-umbrella/
├── umbrella.html
└── images/
├── blue_umbrella.png
├── pink_umbrella.png
└── yellow_umbrella.png


* `index.html`: The main HTML file containing the structure and logic of the application.
* `images/`: A folder containing the umbrella images.

## Instructions for Setting up Images

1.  Create a folder named `images` in the same directory as the `index.html` file.
2.  Download the umbrella images (blue, pink, and yellow) and save them in the `images` folder.
3.  Ensure the images are named exactly `umbrella_blue.png`, `umbrella_pink.png`, and `umbrella_yellow.png`.

## Technologies Used

* HTML
* CSS
* JavaScript

## Notes

* This project is designed for demonstration purposes and may require further development for production use.
* The styling is based on visual estimation from the provided image and may not be pixel-perfect.
* No error handling or input validation is implemented.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.

## License

[Your License (e.g., MIT License)]
