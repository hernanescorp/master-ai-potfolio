# Glossary of Part 2 Programming for AI

## What is a framework really?

A framework is basically:

a set of pre-built tools to develop something complex more easily.

For example:

Framework | What it's for
--- | ---
TensorFlow | Deep Learning
PyTorch | Neural networks
JAX | Accelerated numerical computation
Django | Web applications
Apache Spark | Big Data

## What is a GPU?
Graphics Processing Unit GPU

Originally:

made for graphics/video games

But they turned out to be PERFECT for AI because they can do:

thousands of mathematical operations at once.

### CPU vs GPU
CPU

Few very complex operations.

Ideal for:

operating system
logic
normal applications

Example:

8 very powerful cores.
GPU

Thousands of small cores.

Ideal for:

matrices
tensors
massive multiplications

Neural networks do A LOT of matrix multiplications.

That's why AI uses GPUs.

## And what is a TPU?
Tensor Processing Unit TPU

Special hardware created by Google specifically for AI.

It's like:

an ultra-specialized GPU for tensors.

Very used in:

giant models
Gemini
research
massive training

# JAX — Compact Summary

## What is JAX?

JAX is a Python framework/library created by Google for:

- High-performance numerical computing
- Deep Learning
- Tensor operations
- AI model training

Main idea:

```text
NumPy + GPU + automatic differentiation + optimized compilation
```

---

## Key Features

### 1. NumPy-like syntax

```python
import jax.numpy as jnp
```

---

### 2. GPU / TPU acceleration

JAX can automatically execute computations on:
- CPU
- GPU
- TPU

This makes neural network training much faster.

---

### 3. Automatic differentiation

Very important for Deep Learning and backpropagation.

Gradient computation:

```math
\nabla L(\theta)
```

---

### 4. JIT Compilation

Using:

```python
jit()
```

JAX compiles Python code into highly optimized machine code.

---

## Common Applications

- Deep Learning
- AI Research
- Scientific Computing
- Optimization
- Large-scale neural networks

---

## Related Concepts

| Concept | Meaning |
|---|---|
| GPU | Hardware specialized for parallel computation |
| TPU | Google's AI accelerator hardware |
| Tensor | Multidimensional mathematical structure used in AI |
| Gradient | Derivative used to train neural networks |

---

## Why is it important?

JAX helps move from:
> “Using AI tools”

to:
> “Understanding how AI works internally”.