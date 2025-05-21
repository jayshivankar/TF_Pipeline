# TensorFlow Data Pipelines with Performance Optimization

This repository contains two Jupyter notebooks demonstrating the construction and optimization of input data pipelines in TensorFlow using the `tf.data` API.

## 📁 Contents

- [`tf_data_pipeline.ipynb`](./tf_data_pipeline.ipynb)  
  Introduces the basics of building a data pipeline in TensorFlow. This notebook walks through reading datasets, applying transformations, batching, and shuffling for effective data preprocessing.

- [`prefetch_caching_pipeline.ipynb`](./prefetch_caching_pipeline.ipynb)  
  Demonstrates how to improve data pipeline performance using `cache()` and `prefetch()` to overlap data preprocessing and model execution, minimizing training bottlenecks.

## 🚀 Key Concepts Covered

- `tf.data.Dataset` fundamentals
- Reading and preprocessing data
- Mapping, batching, and shuffling datasets
- Performance best practices:
  - **Caching**: Reduce preprocessing costs
  - **Prefetching**: Improve pipeline throughput
- Monitoring pipeline performance using `time` module

## 📌 Requirements

- Python 3.7+
- TensorFlow 2.x
- Jupyter Notebook or compatible environment (e.g., VS Code, Google Colab)

Install dependencies using:

```bash
pip install tensorflow notebook
```

## 📈 Use Case

These notebooks are ideal for:
- Beginners learning `tf.data` basics
- Practitioners optimizing model training time
- Anyone building efficient input pipelines for deep learning

## 🧠 Reference

- [TensorFlow `tf.data` Guide](https://www.tensorflow.org/guide/data)
- [TensorFlow Performance Guide](https://www.tensorflow.org/guide/data_performance)


