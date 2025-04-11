

# Animal Detection Model

This repository contains an animal detection model capable of detecting 80 different types of animals. The model is built using YOLOv5.

## Prerequisites

Before running the detection model, ensure you have the following prerequisites installed:

- Python (version X.X.X)

## Installation

### For macOS:

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/animal-detection.git
   ```

2. **Navigate to the Repository**: Change into the cloned repository directory:
   ```bash
   cd animal-detection
   ```

3. **Install Requirements**: Install the required dependencies by running the following command:
   ```bash
   pip install -r requirements.txt
   ```

### For Windows:

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/animal-detection.git
   ```

2. **Navigate to the Repository**: Change into the cloned repository directory:
   ```bash
   cd animal-detection
   ```

3. **Install Requirements**: Install the required dependencies by running the following command:
   ```bash
   pip install -r requirements.txt
   ```

### For Linux:

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/animal-detection.git
   ```

2. **Navigate to the Repository**: Change into the cloned repository directory:
   ```bash
   cd animal-detection
   ```

3. **Install Requirements**: Install the required dependencies by running the following command:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Follow these steps to run the animal detection model:

1. **Download Pre-trained Model**: Download the pre-trained YOLOv5 model from [here](link-to-model-file) and place it in the repository directory.

2. **Run the Model**: Open your preferred code editor or terminal and execute the following command:
   ```bash
   python detect.py --weights "path/to/your/model.pt" --img 640 --conf 0.25 --source "path/to/your/video.mp4"
   ```
   Replace `"path/to/your/model.pt"` with the path to your pre-trained YOLOv5 model file, and `"path/to/your/video.mp4"` with the path to the video file you want to detect animals in.

3. **View Results**: Once the script finishes running, the detected animals will be annotated in the video. You can view the output video to see the detections.

## Supported Animals

The model is capable of detecting the following 80 animals:

- Bear
- Brown bear
- Bull
- Butterfly
- Camel
- Canary
- Caterpillar
- Cattle
- Centipede
- Cheetah
- Chicken
- Crab
- Crocodile
- Deer
- Duck
- Eagle
- Elephant
- Fish
- Fox
- Frog
- Giraffe
- Goat
- Goldfish
- Goose
- Hamster
- Harbor seal
- Hedgehog
- Hippopotamus
- Horse
- Jaguar
- Jellyfish
- Kangaroo
- Koala
- Ladybug
- Leopard
- Lion
- Lizard
- Lynx
- Magpie
- Monkey
- Moths and butterflies
- Mouse
- Mule
- Ostrich
- Otter
- Owl
- Panda
- Parrot
- Penguin
- Pig
- Polar bear
- Rabbit
- Raccoon
- Raven
- Red panda
- Rhinoceros
- Scorpion
- Sea lion
- Sea turtle
- Seahorse
- Shark
- Sheep
- Shrimp
- Snail
- Snake
- Sparrow
- Spider
- Squid
- Squirrel
- Starfish
- Swan
- Tick
- Tiger
- Tortoise
- Turkey
- Turtle
- Whale
- Woodpecker
- Worm
- Zebra

---

Feel free to customize the paths and instructions as needed for your specific setup. Additionally, provide any additional information or troubleshooting tips that users may find helpful.
