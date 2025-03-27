# Image Forgery Detection using ELA and CNN

## 📌 Overview
This project focuses on detecting image forgery using **Error Level Analysis (ELA)** and **Convolutional Neural Networks (CNNs)**. ELA helps highlight inconsistencies in image compression, which are then analyzed by a deep learning model to classify images as authentic or tampered.

## 🔍 Methodology
1. **Error Level Analysis (ELA)**: Detects altered image regions by analyzing compression differences.
2. **Preprocessing**: Converts images to ELA format and normalizes them for model input.
3. **CNN Model**: Trained to classify images as forged or authentic.
4. **Evaluation**: Performance assessed using accuracy, precision, recall, and F1-score.

## 🛠️ Technologies Used
- **Python**
- **TensorFlow/Keras**
- **OpenCV**
- **Matplotlib**
- **NumPy & Pandas**

## 🚀 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/Nagendra0228/Image-forgery-Detection-using-ELA-and-CNN.git
   cd Image-forgery-Detection-using-ELA-and-CNN
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the preprocessing and training scripts:
   ```sh
   python preprocess.py
   python train.py
   ```
4. Test the model:
   ```sh
   python test.py --image path/to/image.jpg
   ```

## 📊 Results
The model achieves high accuracy in detecting forged images, demonstrating the effectiveness of **ELA combined with deep learning**.

## 🤝 Contributing
Feel free to fork the repo, create feature branches, and submit pull requests!
## 📜 License
This project is open-source and available under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---
🔥 **Author**: [Nagendra Pai](https://github.com/Nagendra0228)  
📧 **Contact**: painagendra0228@gmail.com
