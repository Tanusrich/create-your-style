# Virtual Try-On with Gradio

This project demonstrates a Virtual Try-On application using Gradio, where users can try on garments on an uploaded image of a person.

## Features

- **Virtual Try-On**: Upload an image of a person and select a garment to see how it looks.
- **Automatic Masking**: Option to use auto-generated masks for the uploaded images.
- **Garment Description**: Add descriptions for garments for better understanding.
- **Post Outfits**: Users can post their virtual try-on outfits for others to view and rate.
- **Like and Dislike**: Viewers can like or dislike posted outfits.

## Requirements

- Python 3.x
- Gradio
- gradio-client
- PIL (Pillow)
- numpy

## Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd Virtual-Try-On
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python app.py
   ```

## Usage

1. **Launch the Application**: Start the application by running the following command in your terminal:

   ```bash
   python app.py
   ```

2. **Upload Image**: Upload an image of a person that you want to try garments on. Use the provided input field labeled "Human: Mask with pen or use auto-masking".

3. **Select Garment**: Choose a garment image that you want to virtually try on. Use the "Garment" input field for this.

4. **Virtual Try-On**: Click on the "Try On" button to initiate the virtual try-on process. The system will overlay the selected garment on the uploaded image of the person based on your settings.

5. **Post Outfit** (Optional): After trying on the garment, you have the option to post the outfit by clicking on the "Post Outfit" button. This will save the outfit image for others to view and rate.

6. **View and Rate Posted Outfits**: Click on the "View Posted Outfits" button to see outfits that other users have posted. You can view these outfits and rate them using the provided like and dislike buttons.


## API Used

This project utilizes the IDM-VTON API provided by kadirnar on the Hugging Face Spaces platform. The API is used for performing virtual try-ons by overlaying selected garments on uploaded images of individuals.
