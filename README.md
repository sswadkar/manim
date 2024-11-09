# manim

This repository contains my experiments with the Manim animation library. It’s a mix of mathematical visualizations, animations, and creative explorations (mostly this last one tbh).

Overview

In this project, I explore a variety of concepts using Manim, from linear transformations and mathematical illustrations to creative animations and effects. This repository is a sandbox for learning and experimenting with different visual representations and animation techniques in Manim.

Requirements

To run the animations, you’ll need the following dependencies installed on your machine:

	•	Python (version 3.7 or later)
	•	Manim Community Edition (install instructions below)
	•	FFmpeg (for rendering videos)
	•	MacTeX (for LaTeX support if using LaTeX expressions in animations)

## Installation

Follow these steps to set up Manim and its dependencies.

### Step 1: Install Python

Download and install Python 3.7 or later from python.org. Make sure to add Python to your system’s PATH.

### Step 2: Set Up a Virtual Environment (Recommended)

To keep dependencies isolated, create a virtual environment in the project directory:

```
python3 -m venv manim_env
source manim_env/bin/activate  # On macOS/Linux
manim_env\Scripts\activate     # On Windows
```

### Step 3: Install Manim

Install Manim Community Edition via pip:

`pip install manim`

### Step 4: Install FFmpeg

FFmpeg is required for video rendering. Install it with these commands:

	•	macOS (with Homebrew):

brew install ffmpeg


	•	Ubuntu/Linux:

sudo apt update
sudo apt install ffmpeg


	•	Windows: Download FFmpeg from ffmpeg.org, extract it, and add the bin folder to your system’s PATH.

### Step 5: Install MacTeX (for LaTeX Support)

If you want to include mathematical notation in your animations, install MacTeX (on macOS) using Homebrew:

`brew install --cask mactex`

For Windows or Linux, install an equivalent LaTeX distribution:

	•	Windows: MikTeX
	•	Linux: sudo apt install texlive-full

## Usage

To run an animation in Manim, use the following command format:

`manim -pql <file.py>`

Here’s a breakdown of the options:

	•	-p: Preview the rendered video after it’s created.
	•	-ql: Render in low quality for faster processing.

## Example

To run a script named example.py:

`manim -pql example.py`

This command will generate and display the animation in a preview window.

### Project Structure

This repository is organized into folders containing different types of animations, each exploring various concepts or techniques.

```
manim/
├── _llms/               # Experimentations with large language models
├── _test/               # Test scripts and experimental animations
├── .gitignore           # Specifies files and folders to ignore in version control
├── LICENSE              # Project license information
├── README.md            # Project documentation
└── requirements.txt     # List of required Python packages
```

### Contributing

Feel free to fork the repository, try out the scripts, or contribute with new ideas and experiments! If you have questions or suggestions, open an issue or submit a pull request.