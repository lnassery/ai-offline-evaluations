# ai-offline-evaluations

This repository is serves as the source code to accompany the contents of an ai offline evaluations book. The intended use is to practical and hands-on code snippets that are reference throughout the book. 

## Overview

Offline evaluations to measure the effect of your AI model. As you iterate on an AI model, use this book as a reference for the offline evaluation strategies you should implement to verify your changes are moving metrics in the right (positive) direction. 

## What's in this repository
You'll find notebooks for each chapter, with example code to compute the offline evaluation formulas. Each notebook references data that's available in the sourcedata folder. 

For chapters 2 - 5, the notebooks demonstrate a simplified offline evaluation workflow using the movie recommendation example that is detailed in the book. For example, chapter illustrates the anatomy of an offline evaluation by creating mock datasets as input, a mock recommendations algorithm and then a simple function to compute precision as output. 

For chapters 6 - 9, we will use the LLM lama, as our model to demonstrate offline evaluations in practice. You can download lama AI model from huggingface. Huggingface is a standarized interface. The goal is to use a common type of model you can find out of the box image classifers for (like animal detection). There's less focus on the model itself, and more focus on all the elements and details needed to evaluate a model. 
