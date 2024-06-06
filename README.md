# Math-With-Hand-Gestures

## Overview
This is an engaging project that uses hand gestures to solve basic math problems, combining elements of computer vision and generative AI.

## Project Setup
### Prerequisites
- Python 3.9+
- Google Gemini API Key ([Google API Quick Start](https://ai.google.dev/gemini-api/docs/quickstart?lang=python); Free of charge)
- Anaconda or Miniconda installed on your machine

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Kanon14/Math-With-Hand-Gestures
cd Math-With-Hand-Gestures
``` 

2. Create and activate a Conda environment:
```bash
conda create -n handenv python=3.10 -y
conda activate handenv
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
1. Execute the project:
```bash
python main.py
```
2. Draw the math problem you want to solve on the web camera canvas (single-handed)
- Draw: [0, 1, 0, 0, 0]
- Clear: [1, 0, 0, 0, 0]
- Send and compute: [1, 1, 1, 1, 0]