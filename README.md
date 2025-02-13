# Secure Data Hiding in Image Using Steganography

## Introduction
This project implements steganography to securely hide data inside an image using the Least Significant Bit (LSB) technique. It ensures confidential communication without raising suspicion.
## Features
- ✅ **Secure Data Hiding**: Uses LSB technique to embed text inside an image.
- ✅ **Data Extraction**: Ability to extract hidden data from the stego image.
- ✅ **Encryption**: Can encrypt the message before embedding for extra security.

## Technologies Used
- **Programming Language**: Python
- **Library Used**:
  - OpenCV – For image processing
- **Platform**: Windows/Linux
- **Algorithm Used**: LSB (Least Significant Bit) steganography

## Installation
Make sure you have Python 3.x installed. Then, install the OpenCV library using this command
  ```bash pip install opencv-python```
<pre id="exampleCode">
import cv2
import numpy as np

def embed_message(image_path, message):
    # Your code to embed the message
    pass

def extract_message(image_path):
    # Your code to extract the message
    pass
</pre>
<button onclick="copyToClipboard('exampleCode')">Copy Code</button>
<script>
function copyToClipboard(elementId) {
  var copyText = document.getElementById(elementId);
  var textarea = document.createElement("textarea");
  textarea.textContent = copyText.textContent;
  document.body.appendChild(textarea);
  textarea.select();
  document.execCommand("copy");
  document.body.removeChild(textarea);
  alert("Copied to clipboard!");
}
</script>

