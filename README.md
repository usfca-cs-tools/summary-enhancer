# Summary Enhancer

Summary Enhancer is a tool for enhancing and improving text summaries from transcriptions using LLMs. It finds key concepts and appends a list of potentially relevant links at the end of the summary. The final output is in markdown format.

## Overview

Summary Enhancer helps you:
- Analyze input summaries for key points.
- Enhance clarity and structure.
- Convert the transcript voice from third person to first person.
- Provide relavant web links to key concepts.

## Installation

1. Ensure that Python 3.12 or later is installed.
2. Clone the repository:
   git clone https://github.com/usfca-cs-tools/summary-enhancer
3. Navigate into the project directory:
   cd summary-enhancer
4. Install the required dependencies:
   pip install -r ../requirements.txt

## Usage

```
$ cat test.text
Today's lecture covered machine learning using scikit-learn.
We discussed supervised learning algorithms including random forests.
```

```
$ ./summary-enhancer test.txt
```

```
$ cat test.md
# Machine Learning Lecture Overview

The lecture focused on machine learning using the scikit-learn library. Key topics included:

- **Supervised Learning Algorithms**
  - Random Forests

This session provided insights into how these algorithms can be applied effectively in various machine learning tasks.

## References

- Random Forests:
  - [https://en.wikipedia.org/wiki/Random_forest](https://en.wikipedia.org/wiki/Random_forest)
  - [https://www.ibm.com/think/topics/random-forest](https://www.ibm.com/think/topics/random-forest)
  - [https://www.geeksforgeeks.org/random-forest-algorithm-in-machine-learning/](https://www.geeksforgeeks.org/random-forest-algorithm-in-machine-learning/)
- Supervised Learning Algorithms:
  - [https://www.geeksforgeeks.org/supervised-machine-learning/](https://www.geeksforgeeks.org/supervised-machine-learning/)
  - [https://www.ibm.com/think/topics/supervised-learning](https://www.ibm.com/think/topics/supervised-learning)
  - [https://en.wikipedia.org/wiki/Supervised_learning](https://en.wikipedia.org/wiki/Supervised_learning)
- machine learning:
  - [https://en.wikipedia.org/wiki/Machine_learning](https://en.wikipedia.org/wiki/Machine_learning)
  - [https://www.ibm.com/think/topics/machine-learning](https://www.ibm.com/think/topics/machine-learning)
  - [https://mitsloan.mit.edu/ideas-made-to-matter/machine-learning-explained](https://mitsloan.mit.edu/ideas-made-to-matter/machine-learning-explained)
- scikit-learn:
  - [https://scikit-learn.org/](https://scikit-learn.org/)
  - [https://github.com/scikit-learn/scikit-learn](https://github.com/scikit-learn/scikit-learn)
  - [https://pypi.org/project/scikit-learn/](https://pypi.org/project/scikit-learn/)
```

