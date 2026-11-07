# Lakers Game Prediction Using Markov Chains

## Overview
This project explores first- through fourth-order Markov chain models to predict Los Angeles Lakers game outcomes using historical win-loss sequences. It was developed for EAI6000: Fundamentals of Artificial Intelligence at Northeastern University.

## Technologies
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib

## Methodology
1. Represent game outcomes as wins (W) and losses (L).
2. Estimate transition probabilities from historical results.
3. Compare first- through fourth-order Markov chain models.
4. Run 1,000 simulations per model order and visualize prediction accuracy.

## Results
| Markov Order | Mean Accuracy |
| --- | ---: |
| First | 48.71% |
| Second | 47.85% |
| Third | 49.30% |
| Fourth | 50.59% |

The fourth-order model achieved the highest average accuracy in this experiment, but improvements were small and higher-order models did not consistently outperform simpler models.

## Limitations and Reproducibility
The model does not account for injuries, opponent strength, or roster changes. The original Lakers CSV dataset is not included in this repository, so the notebook cannot currently be reproduced from scratch without that dataset. Saved notebook outputs are provided for review.

## AI Assistance Disclosure
ChatGPT assisted with code organization, comments, testing, and debugging. The notebook includes an AI assistance disclosure.

## Academic Context
This is a course project and a demonstration of probabilistic modeling, not a production-ready sports prediction system.
