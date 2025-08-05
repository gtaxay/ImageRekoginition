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

<img width="415" height="350" alt="image" src="https://github.com/user-attachments/assets/6de251f0-2034-4b1b-8c2e-a999fc0eae6b" />


### Example Output

<img width="600" height="450" alt="image" src="https://github.com/user-attachments/assets/20b9cfc8-ad8a-475c-8227-2e73a2886257" />


