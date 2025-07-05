# HyperLogLog (HLL)

This repository provides a Python implementation of the **HyperLogLog** algorithm for cardinality estimation — a probabilistic method for estimating the number of distinct elements in a dataset with low memory usage.

## 🔍 What is HyperLogLog?

**HyperLogLog** is a probabilistic data structure that estimates the number of distinct elements in a multiset. It is especially useful for big data applications where exact counting is computationally expensive or memory-intensive.

## 🗂️ Repository Contents

### `hll.py` — Naive Implementation

This file contains a **basic implementation** of the HyperLogLog algorithm, written from scratch for educational purposes.

Key features:
- Simple and readable implementation.
- Uses hashing and bucket-based register updates.
- Implements the core HLL logic: hashing, bucket indexing, and rank calculation.

Limitations:
- Performance may degrade for large-scale datasets.
- Does not optimize memory or time complexity.

---

### `23914_23629_23634.py` — Optimized Version

This file builds on top of `hll.py` and **optimizes the `get_nearest_neighbours` function**, which is a core bottleneck in the naive implementation.

Enhancements include:
- Faster nearest neighbor searches using optimized data structures or algorithms.
- More scalable for larger data streams.
- Reduced runtime and memory usage.

---

## 🚀 How to Run

Make sure you have Python 3.x installed.

```bash
# Run the naive version
python hll.py

# Run the optimized version
python 23914_23629_23634.py

```

## 👥 Contributors

- [@sashank-810](https://github.com/sashank-810)
- [@skmanoj2006](https://github.com/skmanoj2006)
- [@Vishnutejas-2005](https://github.com/Vishnutejas-2005)
