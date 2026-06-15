# Dogs vs Cats Mini Dataset for Kids

A small, kid-friendly dataset of dog and cat images designed for teaching machine learning basics to children.

## 📁 Dataset Structure
```text
dogs-vs-cats-mini/
├── dogs/ # 300 dog images
├── cats/ # 300 cat images
```

- **Two classes**: `dogs` and `cats`
- **Images per class**: 300
- **Total images**: 600

## 🎯 Purpose

This dataset is perfect for:
- Introduction to machine learning for kids
- Simple image classification projects
- Learning about training ML models
- Hands-on coding activities for beginners

## 📊 Details

| Attribute | Value |
|-----------|-------|
| Classes | 2 (dogs, cats) |
| Images per class | 300 |
| Total images | 600 |
| Dataset size | Mini/small - 13.2 MB|
| Source | Compiled from larger online datasets |

## 🚀 Quick Start

```python
from pathlib import Path

dogs_dir = Path("dogs")
cats_dir = Path("cats")

print(f"Dogs: {len(list(dogs_dir.glob('*'))) } images")
print(f"Cats: {len(list(cats_dir.glob('*'))) } images")
```

## ⚠️ Notes

- Images were collected and prepared from various publicly available larger datasets
- Ideal for educational purposes and beginner ML projects
- Small size makes it perfect for quick training on local machines

## 📝 License

Public dataset for educational use.
