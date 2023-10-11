# 3D Printing AI Assistants

This project aims to leverage AI capabilities to assist in the 3D printing process by generating stories or prompts that inspire and guide the creation of 3D-printed objects.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project focuses on utilizing artificial intelligence to enhance the 3D printing experience. By generating creative prompts or stories, it provides inspiration and guidance to users during the 3D printing process. The generated content can serve as a foundation for designing unique and intriguing 3D-printed objects.

## Usage

To use this project, follow these steps:

1. Clone the repository:

      ```bash
      git clone https://github.com/yourusername/3D-Printing-AI-Assistants.git
      cd 3D-Printing-AI-Assistants

2. Install the required Python packages:
   
      ```bash
      pip install -r requirements.txt

3. Set a Prompt for Generating the Story:
Open the generate_story.py file and modify the PROMPT variable to set your desired input for generating a story or prompt for your 3D printing project:

     ```python
     # Set your prompt for generating the sketch
     PROMPT = "valve for controlling high pressure gas flow"

The above prompt will generate a sketch like below:

![alt text](https://github.com/MRHaghighat/3D-Printing-AI-Assistants/blob/main/img/valve.png)

Once the prompt generates an initial sketch which can be modified by trying different prompt, we gan also get its variation as below:

![alt text](https://github.com/MRHaghighat/3D-Printing-AI-Assistants/blob/main/img/valv-var.png)

4. Run the Python script to generate advice:

     ```bash
     python generate_story.py


# Contributing
We welcome contributions! To contribute to this project, please follow the Contribution Guidelines. Feel free to submit issues or create pull requests.

# License
This project is licensed under the MIT License.
