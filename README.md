SECURE DATA HIDING IN IMAGE USING STEGANOGRAPHY:

This project focuses on the technique of embedding secret data within digital images using steganography, specifically through the Least Significant Bit (LSB) method. The goal is to ensure the secure transmission of sensitive information by hiding it in such a way that its presence remains undetectable to unauthorized users.

By using images as carriers for hidden messages, this project provides an additional layer of security beyond traditional encryption methods. The hidden data can only be extracted using specialized techniques, making it a valuable tool for secure communication and data protection in various fields such as cybersecurity, digital forensics, and confidential communications.

FEATURES:

•Easy-to-use Graphical User Interface (GUI)

•Hide text messages inside images

•Reveal hidden messages from images

•Supports PNG and JPG formats

•Open, hide, reveal, and save images easily

REQUIREMENTS:

•Python 3.6 or higher

LIBRARIES:

•Tkinter (comes with Python)

•Pillow (for image processing)

•Stegano (for hiding and revealing messages)

INSTALLATION:

1. Install Python Libraries
Open Command Prompt and run:

   pip install pillow stegano


2. Run the Program
Use this command to start the application:

   python steganography_gui.py

HOW TO USE:

1. Open Image – Select an image file (PNG or JPG).


2. Hide Message – Type your secret message and click "Hide Data".


3. Save Image – Save the image with the hidden message.


4. Reveal Message – Load a steganographed image and click "Show Data" to read the hidden message.

FUTURE IMPROVEMENTS:

•Add password protection for messages

•Support for hiding messages in audio and video files

•Improve the interface design.

