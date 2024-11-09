# MachineLearningStocks in Python: A Starter Project and Guide

[![forthebadge made-with-python](https://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

MachineLearningStocks is designed to be an **intuitive** and **highly extensible** template project applying machine learning to making stock predictions. This project is intended to help users grasp the overall workflow of machine learning in stock prediction, offering insight into its complexities and nuances. After exploring this guide and experimenting with the project, users are encouraged to make their own enhancements—a comprehensive list of possibilities is provided at the end to spark ideas.

In this project, we focus on cleaning and preparing a dataset of historical stock prices and fundamentals using `pandas`. We then apply a `scikit-learn` classifier to identify relationships between stock fundamentals (e.g., PE ratio, debt/equity, float, etc.) and the annual price change, benchmarked against an index. Following this, we perform a simple backtest and generate predictions on current data.

While I would not recommend live trading solely based on this project's predictions, it serves as a strong foundational tool for building a profitable trading system. I have adapted code from this project for live trading, achieving respectable returns (around 20% in backtests and 10-15% in real trading).

This project holds personal significance for me. It was my first substantial Python project, my introduction to machine learning, and my first use of Git. Initially, my code contained various inefficiencies and bad practices. Over time, I have refined it, though minor issues may still exist (please raise an issue or submit a PR if you spot one). Both the project and my programming skills have significantly evolved since the first version, but continuous improvement is always possible.

*Disclaimer: This project is purely educational. Backtested performance can often be misleading—trade responsibly!*

*MachineLearningStocks is designed to predict which stocks may outperform, but it does not suggest portfolio allocation strategies.*


