Requirements
Python: Make sure you have Python installed. You can download it from www.python.org
Pillow Library: This is a powerful library for image processing in Python. You can install it using pip:
pip install Pillow
NumPy Library: This library will be useful for numerical operations. Install it with:

pip install numpy

How to Use it:

Encryption:

Load the image and convert it to a NumPy array.
Add a key to each pixel value to obscure the image data.
Swap the values of adjacent rows.
Save the manipulated pixel data as a new image.

Decryption:

Load the encrypted image and convert it to a NumPy array.
Swap the values of adjacent rows back to restore the original order.
Subtract the key from each pixel value to revert to the original pixel values.
Save the manipulated pixel data as a new image.
Running the Program
Replace the value of image_path variable with the path to your input image.
You can change the values of output_encrypted_path and output_decrypted_path to your desired output file names.
Change the key variable if you want a different encryption key.
Run the script, and it will encrypt the image and then decrypt it, saving both the encrypted and decrypted images to specified paths.
