# Fine-Tuning MoLFormer on Lipophilicity Dataset

This repository contains the implementation of my **Neural Networks: Theory and Implementation (NNTI)** course project at **Saarland University**. The goal of the project is to enhance the performance of the **MoLFormer** chemical language model on the **Lipophilicity dataset (MoleculeNet)** using fine-tuning techniques and data selection methods.

## Project Overview

The project explores different techniques for **fine-tuning MoLFormer** and **selecting influential data points** to improve model performance.

### Tasks Completed:

- **Task 1: Fine-Tuning MoLFormer**  
  - Applied **Bayesian hyperparameter optimization** to fine-tune MoLFormer on the **Lipophilicity dataset**.  
  - Performed **unsupervised fine-tuning** using **Masked Language Modeling (MLM)** before adapting the model for regression.  

- **Task 2: Influence Function-Based Data Selection**  
  - Used **influence functions** with **LiSSA approximation** to identify the most influential data points for fine-tuning.  
  - Investigated how **data selection impacts model performance**.  

- **Task 3: Advanced Fine-Tuning Techniques** *(Ongoing)*  
  - Experimenting with **BitFit, LoRA, and iA3** for parameter-efficient fine-tuning.  
  - Exploring **uncertainty-based and S2L data selection** to improve model generalization.  

## Repository

This project is a work in progress, and further improvements and evaluations are underway. 🚀
