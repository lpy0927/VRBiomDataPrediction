# VRBiom Dataset - Face Recognition for User Authentication in VR

## Project Overview

The VRBiom dataset is designed for face recognition and user authentication in Virtual Reality (VR) environments. This dataset contains facial image data from different users, enabling identity recognition through facial features. The project combines eye-region feature extraction with behavioral data to enhance continuous authentication in VR environments.

With this dataset, users can perform identity verification using facial image data, which enhances both security and user experience in VR settings.

## Directory Structure


## Dataset Description

The dataset contains facial images of VR users aimed at face recognition via eye-region features. The dataset is ideal for enhancing security in VR environments by continuously authenticating users based on their facial characteristics.

### Dataset Fields
- **Image_ID**: Unique identifier for each image
- **User_ID**: User identifier
- **Timestamp**: Timestamp of the captured image
- **Eye_Region**: Coordinates for the eye region in the image
- **Face_Image**: The facial image of the user
- **Label**: User identity label

### Data Format
- Image data is in `.jpg` format
- Label data is in `.csv` format, containing user IDs and corresponding facial image labels

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/lpy0927/VRbiomDataPrediction.git
