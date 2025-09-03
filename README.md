# Fashion-MNIST Dataset (FashionMNIST_dataset)

## Overview

This DeepTrackAI repository provides a copy of the **Fashion-MNIST** dataset available at the [fashion-mnist GitHub Repository](https://github.com/zalandoresearch/fashion-mnist). The dataset was created by Zalando Research as a drop-in replacement for the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/) and is described in [Xiao et al, arXiv, 2017](https://arxiv.org/abs/1708.07747).  

Fashion-MNIST contains grayscale images of fashion products from 10 categories, intended for benchmarking machine learning and computer vision algorithms.

### Summary
- **Number of images**: 70,000 (60,000 training + 10,000 test)  
- **Image size**: 28 × 28 pixels
- **Image format**: 8-bit grayscale PNG
- **Labels**: 10 fashion product classes
  
| Label | Description |
|-------|-------------|
| 0     | T-shirt/top |
| 1     | Trouser     |
| 2     | Pullover    |
| 3     | Dress       |
| 4     | Coat        |
| 5     | Sandal      |
| 6     | Shirt       |
| 7     | Sneaker     |
| 8     | Bag         |
| 9     | Ankle boot  |

---

## Original Source

- **Title**: Fashion-MNIST  
- **Authors**: Han Xiao, Kashif Rasul, Roland Vollgraf (Zalando Research)  
- **Source**: [Fashion-MNIST GitHub Repository](https://github.com/zalandoresearch/fashion-mnist)
- **Reference article**: Xiao, H., Rasul, K., & Vollgraf, R. *arXiv*:1708.07747 (2017). [https://arxiv.org/abs/1708.07747](https://arxiv.org/abs/1708.07747)
- **License**: [MIT License](https://github.com/zalandoresearch/fashion-mnist/blob/master/LICENSE)

If you use this dataset in your research, please follow the licensing requirements and properly attribute the original authors.

---

## Dataset Structure

```bash
/FashionMNIST_dataset   
  ├── train/          # Training images (labeled by filename)
  │   ├── 0_000000.png
  │   ├── 0_000001.png
  │   └── ...
  └── test/           # Test images (labeled by filename)
      ├── 0_000000.png
      ├── 0_000001.png
      └── ...

```

Each filename begins with its class label (0–9), followed by a sequential numerical identifier.

---

## How to Access the Data

### Clone the Repository
```bash
git clone https://github.com/DeepTrackAI/FashionMNIST_dataset
cd FashionMNIST_dataset
```

---

## Attribution

If you use this dataset, please cite both the FashionMNIST dataset and the reference article.

### Cite the dataset:
Zalando Research. *Fashion-MNIST*. GitHub (2017). Retrieved from [github.com/zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist)

```bibtex
@misc{fashionmnist,
  title        = {Fashion-MNIST GitHub Repository},
  author       = {Zalando Research},
  year         = {2017},
  howpublished = {\url{https://github.com/zalandoresearch/fashion-mnist}}
}
```

### Cite the reference article:
Xiao H, Rasul K, Vollgraf R. *Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms*. arXiv preprint arXiv:1708.07747 (2017). [https://arxiv.org/abs/1708.07747](https://arxiv.org/abs/1708.07747)

```bibtex
@online{xiao2017fashionmnist,
  author        = {Han Xiao and Kashif Rasul and Roland Vollgraf},
  title         = {Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms},
  year          = {2017},
  eprinttype    = {arXiv},
  eprint        = {1708.07747},
  archivePrefix = {arXiv},
  primaryClass  = {cs.LG}
}
```

---

## License
This replication dataset is shared under the [MIT License](https://github.com/zalandoresearch/fashion-mnist/blob/master/LICENSE), consistent with the original licensing terms.
