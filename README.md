# Fashion-MNIST Dataset (FashionMNIST_dataset)

## Overview

This DeepTrackAI repository provides a copy of the **Fashion-MNIST** dataset, created by Zalando Research as a **drop-in replacement** for the original [MNIST dataset](http://yann.lecun.com/exdb/mnist/).  

Fashion-MNIST contains grayscale images of fashion products 
from 10 categories, intended for benchmarking machine learning and computer vision algorithms. Each image is 28×28 pixels (grayscale) and associated with a single label from one of 10 classes. The dataset is split into a training set of 60,000 images and a test set of 10,000 images.

### Labels
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

### Summary
- **Dataset Size**: 70,000 images (60,000 training + 10,000 test)  
- **Image Size**: 28×28 pixels  
- **Color**: Grayscale  
- **Labels**: 10 fashion product classes  
- **Format**: PNG images, 8-bit

---

## Original Source

- **Title**: Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms  
- **Authors**: Han Xiao, Kashif Rasul, Roland Vollgraf  
- **Source**: [Official GitHub Repository](https://github.com/zalandoresearch/fashion-mnist)  
- **License**: [MIT License](https://opensource.org/licenses/MIT)  

If you use this dataset in your research, you must follow the licensing requirements and properly attribute the original authors.

---

## Dataset Structure

```bash
/FashionMNIST_dataset  
  ├── train/          # Training images
  │   ├── 0_xxxxx.png
  │   ├── 1_xxxxx.png
  │   └── ...
  └── test/           # Test images
      ├── 0_xxxxx.png
      ├── 1_xxxxx.png
      └── ...
```

Each filename begins with its class label (0–9), followed by an identifier.

---

## How to Access the Data

### Clone the Repository
```bash
git clone https://github.com/DeepTrackAI/FashionMNIST_dataset
cd FashionMNIST_dataset
```

---

## Attribution

This replication dataset is based on the original Fashion-MNIST dataset. When using this replication, please cite the original paper.

### Cite the original paper:
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

This dataset is distributed under the **MIT License**.  

```
MIT License

Copyright (c) 2017 Zalando SE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```
