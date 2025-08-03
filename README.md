# AI Evaluations Book Code Examples

This repository contains the code examples that accompany the *AI Evaluations* book. The goal is to provide **practical, hands‑on snippets** that bring the concepts in the book to life, so you can see how to compute metrics, run diagnostics, and build an evaluation workflow step by step.

## How to Run the Notebooks

You don’t need to install anything locally—all notebooks can run entirely in your browser.

- **Just click and run:** Open any notebook in [Google Colab](https://colab.research.google.com) and execute the cells.
- No setup, no downloads, no Python installation required.

## What’s Inside

- 📂 **`/notebooks`** – Jupyter notebooks for each chapter.

Each notebook is self‑contained and mirrors a concept from the book.

- **Chapters 2–5:** Walk through a simplified **offline evaluation workflow** using a movie recommendation example. You’ll see:
  - How to create mock datasets
  - A toy recommendation algorithm
  - Functions to compute metrics like precision

- **Chapters 6–10:** Currently in progress—new notebooks will be added as these chapters are written. In these later chapters, we’ll use the LLaMA large language model from Hugging Face as an example to demonstrate model evaluations in practice. Hugging Face provides a standardized interface for loading and working with models, making it easy to swap in other out‑of‑the‑box models—like image classifiers for tasks such as animal detection. The emphasis in these chapters isn’t on building or fine‑tuning the model itself, but on illustrating all the steps, considerations, and details involved in evaluating a model effectively.

---

> ### **Why Notebooks?**
> Jupyter notebooks are perfect for this project because they blend **narrative, code, and output in one place.**
> - **Narrative:** Each notebook mirrors the explanations in the book, so you can read, tweak, and experiment without flipping between code and text.
> - **Interactive:** You can run each cell step by step, inspect outputs, and modify code on the fly.
> - **Accessible:** Since they run in the browser via Colab, you don’t need to set up a development environment—just click and explore.

---

> ### **Why Python?**
> Python is the **lingua franca of AI and machine learning**—the most widely used language for experimentation and production alike.
> - **Rich ecosystem:** Libraries like `pandas`, `numpy`, and `matplotlib` make data handling and visualization simple and concise.
> - **Familiarity:** Most data scientists and ML engineers already know Python, making the examples easy to follow.
> - **Flexibility:** It’s just as good for quick experiments in notebooks as it is for production‑grade AI pipelines.

---

## Why This Repo Exists

Evaluations, whether its offline, online or an LLM-as-a-judge, are the reality check for your AI model. These examples are here to help you:
- Understand the math and code behind key evaluation metrics
- See how to structure diagnostics to spot model behavior issues
- Use the code as a reference (or even a starting point) for your own evaluation workflows
