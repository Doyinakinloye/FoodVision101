# FoodVision101

A deep learning project for food image classification using transfer learning and modern computer vision techniques. Built with Tensorflow and trained on the Food101 dataset, it demonstrates scalable model development, evaluation, and deployment for real-world image recognition tasks.

📊 Results

* Achieved **79%** top-1 accuracy on the Food101 test set.

* Performance was limited by computational constraints, preventing longer training runs and hyperparameter tuning.

* Despite these limitations, the model shows strong generalization and promising results compared to baseline approaches.

Hyperparameters
- learning rate: 1e-4
- epochs: 10
- Optimizer: Adam
- Metric: Accuracy

⚙️ Process Overview

1) Data Preparation

- Loaded and preprocessed the Food101 dataset.

- Applied augmentations (random flips, rotations, normalization).

2). Model Development

- Leveraged transfer learning with pretrained architectures (e.g., EfficientNet).

- Fine-tuned layers for food classification.

3). Training

- Used PyTorch training loops with optimizer (Adam) and loss function (CrossEntropy).

4). Evaluation

- Measured accuracy and loss on validation/test sets.

- Visualized predictions and misclassifications.

🚧 Limitations

- Could not train for extended epochs due to hardware and runtime constraints.

Results are promising but leave room for improvement with:

- Longer training schedules.

- Training on more powerful GPU's for longer epochs.
