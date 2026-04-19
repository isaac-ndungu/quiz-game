# CLI Quiz Game

An interactive, terminal-based quiz application written in Python. Questions are loaded from a JSON file, shuffled randomly, and scored with instant feedback per question and a final result summary.


## Features

- Questions loaded from an external `questions.json` file
- Random question order using `random.shuffle()`
- Input validation with `try/except` — only `A`, `B`, `C`, or `D` are accepted
- Per-question feedback (Correct / Wrong)
- Final percentage score with a performance message


## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook (if running via `.ipynb`)

### Running the Script

**Terminal:**
```bash
python quiz.py
```

**Jupyter Notebook:**

Run each cell with **Shift + Enter**. When prompted, type your answer (`A`, `B`, `C`, or `D`) in the `input()` box and press **Enter**.


## How It Works

1. Questions are loaded from `questions.json`
2. The question order is randomized each run
3. Each question displays its text and multiple choice options
4. The user enters a letter answer — invalid inputs are caught and skipped
5. A running score is tracked and a final percentage is calculated


## Score Feedback

| Score         | Feedback              |
|---------------|-----------------------|
| 100%          | Perfect Score!        |
| 80% – 99%     | Great job             |
| 60% – 79%     | Fair job              |
| 40% and below | Do better next time   |
