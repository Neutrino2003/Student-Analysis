# Student-Analysis
A Python-based analytics tool that processes quiz performance data to generate detailed student insights, performance metrics, and personalized recommendations.

## Features

- **Performance Analysis**
  - Overall quiz performance metrics
  - Topic-wise strength analysis
  - Accuracy and speed tracking
  - Performance gaps identification

- **Visual Analytics**
  - Performance distribution pie charts
  - Score distribution graphs
  - Topic-wise accuracy bar charts
  - Progress timeline plots

- **Personalized Insights**
  - Learning style identification
  - Consistency tracking
  - Pattern recognition
  - Topic-specific recommendations

## Setup & Usage

### 1. Required Files
Place your data files in your working directory:
- `LLQT.json` - Quiz questions and answers
- `rJvd7g.json` - User responses
- `XgAgFJ.json` - Performance data

### 2. Configuration
Update these variables in `analysis.ipynb`:

```python
# filepath: analysis.ipynb
# Configure file paths
QUIZ_FILE = '/path/to/LLQT.json'
RESPONSE_FILE = '/path/to/rJvd7g.json' 
PERFORMANCE_FILE = '/path/to/XgAgFJ.json'

# Set user ID for analysis
user_id = "your_user_id_here"
```
# Note
Will add a python file with oops implementation of the notebook file to integrate it with the application seamlessly
