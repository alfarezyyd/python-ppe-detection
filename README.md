# 🦺 **PPE Object Detection**

> _Safety first — Safety Always!_

> _Utamakan keselamatan dan kesehatan kerja!_

## 👋 Manpower

- [**Azizah Pauziah**](https://www.github.com/)  
  _2210631250006_
- [**Nasywa Syifa Hanifah**](https://www.github.com/)  
   _2210631250023_
- [**Aditya Alfarezy Damanik**](https://www.github.com/)  
   _2210631250037_
- [**Vernanda Ayu Prastika**](https://www.github.com/)  
   _2210631250102_

## Related Link

- [Dataset Vest](https://universe.roboflow.com/mainel/vest-cye3g)
- [Laporan UAS](https://docs.google.com/document/d/1Af-wU06vOFDZHdqPS0KJ_9QTKGA6iUvTd2lBjKeU0wA/edit?usp=sharing)
- [GitHub Repository](https://github.com/alfarezyyd/python-ppe-detection)

## 🌟 Noble Purpose (Tujuan Mulia)

In the workplace, safety is a fundamental right for every individual. Through an intelligent and automated Personal Protective Equipment (PPE) detection system, this project aims to:

- **Reduce the risk of workplace accidents** caused by negligence in using PPE.
- **Promote a more disciplined and safety-conscious work culture.**
- **Provide accurate and real-time data** as a foundation for better decision-making.
- **Contribute to the improvement of workplace safety standards**, especially in high-risk industrial sectors.

The purpose of this project is to make technology a tool for **protection, not merely convenience**.

## Prerequisites

- Python 3.11.12 or newer
- pip (Python package manager)

## Run Locally

Clone the project

```bash
  git clone https://github.com/alfarezyyd/python-ppe-detection
```

Go to the project directory

```bash
  cd python-ppe-detection
```

Create virtual environment

```bash
  python -m venv venv
  source venv/bin/activate  # Windows: venv\Scripts\activate
```

Install dependencies

```bash
  pip install -r requirements.txt
```

## Current Device

      Model Name: MacBook Air
      Model Identifier: MacBookAir10,1
      Model Number: MGN63ID/A
      Chip: Apple M1
      Total Number of Cores: 8 (4 performance and 4 efficiency)
      Memory: 8 GB

## Project Structure

    .
    ├── README.md
    ├── build
    │   ├── best_vest_model.h5
    │   └── best_vest_model.onnx
    ├── images
    │   └── vest_ppe
    ├── dataset
    │   └── test
    |     ├── images
    │     └── labels
    └── train
    |     ├── images
    │     └── labels
    └── valid
    |     ├── images
    │     └── labels
    ├── media
    │   └── output.png
    ├── requirements.txt
    ├── runs
    │   └── detect
    │   ├── yolo_comparison_model
    │   │   ├── args.yaml
    │   │   └── weights
    │   └── yolo_comparison_model2
    │   ├── args.yaml
    │   ├── labels.jpg
    │   ├── labels_correlogram.jpg
    │   ├── train_batch0.jpg
    │   ├── train_batch1.jpg
    │   ├── train_batch2.jpg
    │   └── weights
    ├── src
    │   ├── crawl-image.ipynb
    │   ├── preparation.ipynb
    │   ├── train-with-cnn.ipynb
    │   └── train-with-yolo.ipynb
    └── yolo11n.pt

    12 directories, 27 files

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`API_KEY`

## Screenshots

![App Screenshot](https://github.com/alfarezyyd/python-ppe-detection/blob/main/media/output.png)

## Support

For support, email adityaalfarezyrezy@gmail.com.

## Contributing

Contributions are always welcome!

Feel free to raise issues and enhancement requests!
