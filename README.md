# <b>TCID</b> (<b>T</b>ext-<b>C</b>ode <b>I</b>nconsistency <b>D</b>etector)

TCID is a neural-based approach to predict inconsistent text-code inconsistencies by leveraging:

 1. the advances in natural language processing and machine learning;
 2. the abundance of text-code data available in open source public repositories;
 3. the power of human cognizance.

## Prerequisites

1. Install Mini[conda](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html) if you already do not have:

2. Create Python virtual environment with dependencies:

```bash
$> ./create_env
$> conda activate tdc3 # name of the environment is tdc3
$> python -c "exec(\"import nltk\nnltk.download('punkt')\nnltk.download('stopwords')\")"
```

## Usage

Follow the instructions in the tcid folder. 

