# ImageRekogintion
Rekoginizes objects in images while utilizing AWS servies.

## Description
Takes images from AWS S3 buckets then identifies objects within the picuture. The function utilized AWS Rekognition to identify the objects which are outlined with red boxes and given lables. Labels include object name and confidence percentage of the object.

---

## Getting Started
- Make sure to have Visual Studio Downloaded with Python Extension
- Be able to sign into AWS services

--- 

## Libraries

- boto3 for interacting with AWS services
- matplotlib for visualization.
- PIL (Python Imaging Library) for handling image data.
- BytesIO from the io module to work with image data.

--- 

## Running Program
Open the terminal and type

    python file_name.py

This should return 10 objects and their confidnece level in the output termial and open a new tab for the image

## Example Input/Output

### Example Input

<img width="415" height="350" alt="image" src="https://github.com/user-attachments/assets/7d38342d-cf64-481b-8aa0-9d6ad507a7f9" />

### Example Output

<img width="415" height="350" alt="image" src="https://github.com/user-attachments/assets/e73fa0e5-e2be-4eba-992c-8d581e84ad5a" />

