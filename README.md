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

(https://www.google.com/imgres?q=busy%20street&imgurl=https%3A%2F%2Fc8.alamy.com%2Fcomp%2FDBGC3A%2Fbusy-times-square-in-manhattan-new-york-city-street-with-crowds-of-DBGC3A.jpg&imgrefurl=https%3A%2F%2Fwww.alamy.com%2Fstock-photo%2Fbusy-street-new-york.html&docid=mI5dCoWwG7pajM&tbnid=3UBOXlqzRIWMKM&vet=12ahUKEwijp9KbzvSOAxX1k2oFHbd8AIkQM3oECGIQAA..i&w=1300&h=1015&hcb=2&ved=2ahUKEwijp9KbzvSOAxX1k2oFHbd8AIkQM3oECGIQAA)
