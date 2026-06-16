# Simple RNN Question & Answer Model

This repo contains a simple RNN (Recurrent Neural Network) model trained on a question and answer dataset. You give it a question, and it tries to predict the answer based on what it learned during training.

---

## What's in here

- The RNN model code
- Training script
- The dataset used for training (`100_Unique_QA_Dataset.csv`)

---

## How it works

The model was trained on a set of question-answer pairs. It learns the patterns between questions and their corresponding answers, and then uses that knowledge to predict answers for new questions you give it.

It's a pretty straightforward implementation, nothing too fancy, just a basic RNN doing its thing.

---

## Want to try it out?

If you want to run or test the model yourself, use the dataset already included in this repo:

```
100_Unique_QA_Dataset.csv
```

That's the same dataset the model was trained on, so it should work well out of the box.

Just load it up, run the training script, and start asking questions.

---

## Requirements

Make sure you have the following installed before running anything:

- Python 3.x
- PyTorch
- NumPy
- Pandas

Install them with:

```bash
pip install numpy pandas torch
```

---

## Notes

- This is a simple model, so don't expect perfect answers every time. It works best on questions similar to the ones in the training dataset.
- If you want better results, you can expand the dataset or tweak the model architecture a bit.

---

Feel free to open an issue if something doesn't work or if you have any questions.
