# Poetic Prowess : Poetry Generator

## Table of Contents
1. [Project Description](#project-description)
2. [Project Demo](#project-demo)
3. [Badges](#badges)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Configuration](#configuration)
7. [Contributing](#contributing)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)
10. [Documentation](#documentation)

## Project Description
This project is a poetry Generator that uses a custom database containing lyrics of various hip hop artists. The generator uses a combination of Markov chains and LSTM neural networks to compose rap lyrics. The code is split into two parts: the backend, which handles the model training and generation, and the frontend, which provides an interface to generate lyrics from a given prompt.

## Badges
[Add relevant badges here, such as build status, version, etc.]

## Installation
To install and run the Hip Hop Lyrics Generator, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running: `pip install -r requirements.txt`.

## Usage
To use the Hip Hop Lyrics Generator, follow these steps:

1. Prepare your own dataset of hip hop lyrics and save it in a text file. Ensure that each line represents a separate sentence or line of lyrics.
2. Adjust the `depth` and `maxsyllables` parameters in the code according to your preference. `depth` controls the depth of the LSTM network, and `maxsyllables` sets the maximum number of syllables allowed in each generated line.
3. Train the model using your dataset by setting `train_mode = True` and providing the path to your dataset in the `data` variable. The model will be saved as `poem.h5`.
4. Once the model is trained, you can set `train_mode = False` and use the trained model to generate rap lyrics based on a prompt.

## Configuration
This project does not require any special configuration. However, you can experiment with different values for the `depth` and `maxsyllables` parameters to achieve different results in the generated lyrics.

## Contributing
If you would like to contribute to this project, feel free to submit pull requests or open issues on the GitHub repository.

## License
[Specify the license under which the project is distributed.]

## Acknowledgments
[Add any acknowledgments or credits to people or resources that contributed to the project.]

## Documentation
The complete documentation for this project can be found in the code itself. Detailed comments are provided to explain the purpose and functionality of each function and component.
