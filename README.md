# Image Encryption and Decryption

This Python script provides functionalities to encrypt and decrypt images using the Python Imaging Library (PIL). Encryption involves adding a key to each RGB value of the pixels, and decryption reverses this process.

## Requirements

- Python 3.x
- Pillow (Python Imaging Library)

## Installation

1. Clone or download the repository to your local machine.

2. Install the required dependencies using pip:

    ```
    pip install pillow
    ```

## Usage

1. Place the image file you want to encrypt in the project directory.

2. Open the Python script (`image_encrypt_decrypt.py`) and modify the `image_path` variable to specify the path to your image file.

3. Choose a key (an integer value) for encryption and decryption. Modify the `key` variable accordingly.

4. Run the script:

    ```
    python image_encrypt_decrypt.py
    ```

5. The script will encrypt the image and save the encrypted version as `encrypted_image.png`. It will then decrypt the encrypted image and save the decrypted version as `decrypted_image.png`.

## Example

```python
# Example usage
image_path = "C:/Users/Admin/Downloads/text.jpg"
key = 250000  # Change this key as needed
encrypt_image(image_path, key)
decrypt_image("encrypted_image.png", key)
```
![WhatsApp Image 2024-03-12 at 20 52 23_e8c3bc4b](https://github.com/Janani-m17/PRODIGY_CS_02/assets/124059957/b0589e1a-ddc0-4c1c-b6a3-5b78ab98b6ab)

![WhatsApp Image 2024-03-12 at 21 26 53_5267cbd8](https://github.com/Janani-m17/PRODIGY_CS_02/assets/124059957/de60462a-7605-412a-ac41-9242c2556f9b)


## Note

- Ensure that the image file exists at the specified path and that you have write permissions to the directory for saving the encrypted and decrypted images.

- The encryption and decryption process can take some time, depending on the size of the image.
