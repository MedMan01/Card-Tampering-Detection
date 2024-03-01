# PAN Card Tampering Detection
## Overview
This project is aimed at utilizing computer vision techniques to detect tampering or forgery in PAN (Permanent Account Number) cards. The primary objective is to aid various organizations in verifying the authenticity of PAN cards submitted by their employees, customers, or any other individuals.

## Methodology
The detection process involves several steps leveraging computer vision algorithms:

### 1.	Structural Similarity Index (SSIM):
•	We utilize SSIM to determine the structural similarity between the provided PAN card image and an authentic reference image.<br>
•	A SSIM value of approximately 31.2% serves as a threshold to classify the provided image as potentially fake or tampered.<br>
### 2.	Shape Analysis:
•	We analyze the shape of the PAN card images by identifying contours and determining thresholds in grayscale binary images.<br>
• This aids in recognizing differences or similarities in the structural shapes of the images.<br>
### 3.	Visualization:
• The project offers visual representations of the differences and similarities between the provided image and the authentic reference image.<br>
•	Visualization includes displaying images with contours, highlighting differences, and showcasing threshold analysis.<br>

## Usage
This project is designed to be employed by various organizations that require individuals to provide identification documents for verification purposes. It can be used to ascertain the authenticity of PAN cards, as well as other forms of identification such as Aadhar cards, voter IDs, etc.

## How to Use
1.	Clone the repository to your local machine.
2.	Install the necessary dependencies.
3.	Provide the PAN card image to be analyzed.
4.	Execute the detection script.
5.	Review the output to determine the authenticity of the provided PAN card.
## Future Enhancements
•	Improve accuracy by incorporating additional image processing techniques.<br>
•	Expand compatibility to support various types of identification documents.<br>
•	Enhance visualization capabilities for clearer analysis.<br>
