# My_Stego_AICTEProject
Project based on Secure Data Hiding in images using Steganography.

**Project Overview:**
This project demonstrates a method of securely hiding secret messages inside an image using Steganography. It utilizes a password-based system to encrypt and decrypt the hidden messages. The image appears unchanged visually, making it undetectable to the human eye. Only authorized users with the correct passcode can decrypt and access the hidden message.

**Features:**
Invisible Encryption: Secret data is embedded in an image without any visible alterations.
Password Protection: A passcode is required to decrypt the hidden message, adding an extra layer of security.
Real-Time Decryption: The message is instantly displayed after entering the correct passcode.

**Technologies Used**
Programming Language: Python
Libraries:OpenCV
Platform: Windows

**Installation:**
Requirements:-Python, stego py need OpenCV library,pip install cv2.

**How It Works**
Image Loading: The image file is read and stored in memory.
Message Encoding: The secret message is embedded into the image pixel values (RGB channels) in such a way that it is not noticeable to the human eye.
Password-based Encryption: The secret message is encrypted with a passcode. Only users with the correct passcode can access the hidden message.
Message Retrieval: To retrieve the hidden message, the correct passcode must be provided. Upon successful verification, the message is displayed.




