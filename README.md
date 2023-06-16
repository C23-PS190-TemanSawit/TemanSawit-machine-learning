# Teman Sawit Machine Learning
<img src="https://github.com/TemanSawit/TemanSawit-machine-learning/assets/43689683/c9df0052-18b0-4cf4-bc71-fbc79c63e66e"  width="250" height="250"><br /><br />
Repository for Bangkit 2023 Capstone project. Our team consist of 2 Machine Learning, 2 Android, and 2 Cloud Computing. <br />

|          Nama         | Bangkit-ID |       Path       |
|:---------------------:|:----------:|:----------------:|
|  Syafitri Rihandini  |  M132DKY4822  | Machine Learning |
|  Aditya Shiva Al-Hakim  |  M280DKX3890  | Machine Learning |
|   Rischa Nurul Hidayati    |  C177DSY2224  |  Cloud Computing |
|  Muh. Falach Achsan Yusuf  |  C300DSX2627  |  Cloud Computing |
|    Noor Saputri      |  A057DSY1102  |  Mobile Development  |
|    Muhammad Sohiburroihan Akbar      |  A057DSX1726  |  Mobile Development  |

## What's Teman Sawit?
TemanSawit is an app designed to assist middle to lower-scale oil palm farmers in making informed decisions and improving their productivity. The app addresses the challenges faced by farmers in selecting quality oil palm seedlings and determining fruit maturity levels. By providing features such as palm seedling abnormality detection, fruit maturity level detection, and digital harvest recording, TemanSawit aims to minimize the risk of seedling selection errors, optimize oil palm production, and enhance the management and transparency of oil palm sales data.

## Our Models
TemanSawit has 2 models, an image classification for classifyin oil palm fruit ripeness, and object detection for detecting oil palm seedlings gender. <br />
![image](https://github.com/TemanSawit/TemanSawit-machine-learning/assets/43689683/4437aba9-a22e-4644-af53-c6f6b05c52f5)
![image](https://github.com/TemanSawit/TemanSawit-machine-learning/assets/43689683/ab7475b5-ab06-48ce-86f4-1d32fd934232) <br /><br />

Our ripeness classification were trained on 600+ images for 6 different classes, achieving roughly 78% validation accuracy and 75% F1 score. <br />
![image](https://github.com/TemanSawit/TemanSawit-machine-learning/assets/43689683/d453d3bd-f354-4045-bfc5-fbda604dc122) <br />
![image](https://github.com/TemanSawit/TemanSawit-machine-learning/assets/43689683/877f00c0-1c47-4e33-af89-2f89cd7782ba) <br /><br />

## Ripeness Classification

### Dataset
Dataset Link:
Ripeness Classification
- Train : https://drive.google.com/drive/folders/1_cXUhdfJh4ao9aaUf9u5rV4Up6QYdBut?usp=sharing
- Validation : https://drive.google.com/drive/folders/172gf2HmEuce8DGKSxsk95QrDFndeLyHu?usp=sharing
Seedlings Detection : https://www.kaggle.com/datasets/syafitririhandini/palm-oil-seedlings

### Requirements
To run the notebook and utilize the model, the following dependencies are required:
- Tensorflow
- Matplotlib
- NumPy
- PIL
- random
- cv2
- shutil
- os

### Classification Image Step
1. Clone the repository.
```bash
git clone https://github.com/C23-PS190-TemanSawit/TemanSawit-machine-learning.git
```
2. Install the required dependencies.
```bash
pip install tensorflow matplotlib numpy pillow cv2
```
3. Navigate to the classification directory and open the notebooks.
Optional : Link your google drive by running the first 2 cells. For the exact step, read [here](https://stackoverflow.com/a/69881106).
4. Run the cells in the notebook to train the model and evaluate its performance.
5. The train model will be saved automatically if you provide the checkpoint callback.
6. Use the saved model for inference in your applications.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code as per the license terms.
