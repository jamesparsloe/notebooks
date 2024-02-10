# Notebooks

Just playing around.

These notebooks are self-contained (apart from third-party packages/dependencies) and _should_ run on Colab. They're just a place for me to quickly test out new ideas, things I'm learning, and have somewhere to copy and paste from when I need it.

| Notebook | Description |
|----------|-------------|
| [Mamba MNIST](./mamba-mnist.ipynb) [Colab](https://colab.research.google.com/github/) | Applying Mamba to conditional MNIST generation |

## Colab

Colab doesn't seem to like Triton out of the box. The suggestion from [here](https://github.com/pytorch/pytorch/issues/107960) is to execute

```python
!ldconfig /usr/lib64-nvidia
```