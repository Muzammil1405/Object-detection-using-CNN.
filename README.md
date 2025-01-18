# Object Detection Using CNN

Welcome to the **Object Detection Using CNN** project! 🎉 This repository contains a Python implementation for detecting objects in images using a pre-trained Faster R-CNN model from the PyTorch library. The project is simple, easy to use, and leverages the power of the COCO dataset for detecting 80 different classes of objects.

---

## Features 🚀

- **Pre-trained Faster R-CNN Model**: Utilizes the ResNet-50 backbone for accurate and efficient object detection.
- **Supports Multiple Classes**: Detects objects like people, cars, animals, furniture, and more, all from the COCO dataset.
- **Threshold Control**: Allows you to adjust the confidence level for filtering detected objects.
- **Visual Output**: Displays images with bounding boxes and labels drawn around detected objects.
- **No Training Needed**: Uses pre-trained weights, making it beginner-friendly.

---

## Example Output 🌟

![Example Output](https://dummyimage.com/800x400/000/fff&text=Example+Output)

The above image is an example of the model detecting objects in an image, drawing bounding boxes, and labeling them.

---

## Installation 🛠️

To get started, ensure you have Python 3.7 or later installed. Then, install the required libraries:

```bash
pip install torch torchvision opencv-python matplotlib
```

---


## Key Components 🔍

### `get_prediction(img_path, threshold=0.5)`
- Takes an image path and a confidence threshold as inputs.
- Returns the bounding boxes and labels for detected objects.

### `draw_boxes(img_path, boxes, labels)`
- Draws bounding boxes and labels on the image using OpenCV.

### Pre-trained Model
- **Model**: Faster R-CNN with ResNet-50 backbone.
- **Dataset**: Pre-trained on the COCO dataset.

---

## Supported Classes 🏷️

The model can detect 80 classes, including:
- Person
- Car
- Dog
- Bicycle
- Traffic light
- And many more!

For a full list of classes, check the COCO dataset [here](https://cocodataset.org/#home).

---

## Contributing 🤝

Contributions are welcome! If you’d like to improve this project, feel free to fork the repository, make changes, and submit a pull request.

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add a new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## License 📜

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you like!

---

## Acknowledgments 🙌

- [PyTorch](https://pytorch.org/) for providing an excellent deep learning framework.
- The [COCO Dataset](https://cocodataset.org/#home) for making object detection tasks possible.
- The PyTorch community for their fantastic support and resources.

---

Start detecting objects in your images today! If you have any questions, feel free to open an issue or reach out. 😊
