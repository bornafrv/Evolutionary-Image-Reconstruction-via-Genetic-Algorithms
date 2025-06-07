# 🧬 EvoPaint: Evolutionary Image Reconstruction via Genetic Algorithms

This project implements a genetic algorithm to reconstruct target images by evolving populations of abstract shapes. Over successive generations, the algorithm optimizes the visual resemblance between a rendered image and a given target, showcasing the creative power of evolutionary computation.

---

## 📂 Project Structure

- `AI_CA2_Notebook.ipynb`  
  Main notebook implementing the entire pipeline: initialization, fitness evaluation, genetic operations, and visualization.

- `Instruction.pdf`  
  Detailed project guidelines, objectives, and requirements.

- `Report.pdf`  
  Comprehensive report with methodology, algorithm analysis, performance discussion, and results.

- `README.md`  
  This file — overview and usage instructions.

- `target_images.zip`  
  A collection of reference images used for reconstruction. Must be extracted before running the notebook.

---

## ⚙️ Key Features

### 🎯 Fitness-Driven Approximation
Evaluates the similarity between the target and candidate image using pixel-wise comparison.

### 🧬 Core Genetic Operations
- **Selection**: Chooses the fittest individuals for reproduction.
- **Crossover**: Combines traits from parents to generate offspring.
- **Mutation**: Introduces random variations to maintain diversity.

### 📈 Real-Time Visualization
Observe the approximation progress live as the population evolves.

### 🖼️ Flexible Target Input
Easily switch between different images to test algorithm scalability and generalization.

---

## 🧪 Requirements

Python 3.x

Libraries: random, PIL, numpy, matplotlib, cv2, math, tabulate

## 📊 Insights
EvoPaint demonstrates the power of nature-inspired optimization. It’s a visual and computational experiment in how simple rules and randomness can produce sophisticated image approximations.

## 👨‍🏫 Project Context

This project was developed as part of the Artificial Intelligence coursework at the University of Tehran.

Instructor: Dr. YaghoobZadeh

