# AI Maths Word Problem Solver

A Python-based AI application that interprets and solves mathematical word problems using natural language processing (NLP) and deep learning.

## Features
- **TensorFlow Model**: Converts natural language problem statements into equations for accurate solution generation.
- **NLP Preprocessing**: Uses NLTK for tokenization, parsing, and handling multi-step problems.
- **Tkinter Interface**: Simple GUI for entering word problems and viewing solutions.
- **Dataset**: Utilizes the MAWPS dataset, augmented for improved robustness.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Yashkashte5/Math-AI-Word-problem-Solver.git
   cd Math-AI-Word-problem-Solver
   ```
2. Create and activate a Python virtual environment:
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Tkinter application:
   ```bash
   python main.py
   ```
2. Enter a mathematical word problem in the GUI and view the generated solution.

## Project Structure
```
Math-AI-Word-problem-Solver/
│── main.py                  # Entry point for GUI application
│── src/                     # Source code for model and preprocessing
│── models/                  # Trained TensorFlow models
│── datasets/                # MAWPS dataset and augmentations
│── requirements.txt         # Python dependencies
│── README.md                # Project documentation
```

## Future Improvements
- Improve accuracy on multi-step and complex word problems.
- Integrate more advanced transformer-based NLP models.
- Optionally create a web interface for easier access.
