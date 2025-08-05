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

The script will:
- Fetch an image from your S3 bucket
- Use AWS Rekognition to identify objects (up to 10)
- Print each label and confidence score in the terminal
- Display the image with bounding boxes and labels in a new window

## Example Input/Output

### Example Input

<img width="415" height="350" alt="image" src="https://github.com/user-attachments/assets/6de251f0-2034-4b1b-8c2e-a999fc0eae6b" />


### Example Output

<div style="display: flex; gap: 10px; flex-wrap: wrap;">
<img width="500" height="370" alt="image" src="https://github.com/user-attachments/assets/52abf8cd-2bf1-4811-b247-e5592a45c572" />
<img width="170" height="300" alt="image" src="https://github.com/user-attachments/assets/e79d38c6-a503-4b3f-bdb4-c83a2a4b6d51" />
</div>


