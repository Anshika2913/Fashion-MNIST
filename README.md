<h1>🧠 Fashion MNIST Image Classification (CNN + Transfer Learning)</h1>

<h2>📌 Overview</h2>
<p>
This project focuses on building an image classification model using the <b>Fashion MNIST dataset</b>. 
The goal is to classify grayscale images of clothing items into 10 categories using 
<b>Convolutional Neural Networks (CNNs)</b> and <b>transfer learning</b>.
</p>

<h2>🚀 Features</h2>
<ul>
    <li>Built a CNN model for image classification</li>
    <li>Achieved <b>~96% test accuracy</b></li>
    <li>Applied <b>Transfer Learning (VGG16)</b></li>
    <li>Used data augmentation and dropout regularization</li>
    <li>End-to-end pipeline: preprocessing → training → evaluation</li>
</ul>

<h2>🗂 Dataset</h2>
<ul>
    <li>Fashion MNIST Dataset</li>
    <li>60,000 training images</li>
    <li>10,000 test images</li>
    <li>10 classes (T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)</li>
</ul>

<h2>🛠 Tech Stack</h2>
<ul>
    <li>Python</li>
    <li>PyTorch</li>
    <li>NumPy</li>
    <li>Matplotlib</li>
</ul>

<h2>⚙️ Model Architecture</h2>
<ul>
    <li>Convolutional Neural Network (CNN)</li>
    <li>Pretrained <b>VGG16 model</b> (Transfer Learning)</li>
    <li>Layers used:
        <ul>
            <li>Convolution + ReLU</li>
            <li>Max Pooling</li>
            <li>Fully Connected Layers</li>
            <li>Dropout for regularization</li>
        </ul>
    </li>
</ul>

<h2>📊 Results</h2>
<ul>
    <li>Training Accuracy: ~97%</li>
    <li>Test Accuracy: <b>~96%</b></li>
    <li>Improved performance using transfer learning and tuning</li>
</ul>

<h2>🔄 Workflow</h2>
<ol>
    <li>Data Loading & Preprocessing</li>
    <li>Data Augmentation</li>
    <li>Model Building (CNN + VGG16)</li>
    <li>Training & Optimization</li>
    <li>Evaluation on Test Data</li>
</ol>

<h2>▶️ How to Run</h2>

<h3>Option 1: Google Colab</h3>
<p>Open the notebook in Colab and run all cells.</p>

<h3>Option 2: Local Setup</h3>
<pre>
pip install torch torchvision matplotlib numpy
</pre>

<pre>
python main.py
</pre>

<h2>📌 Future Improvements</h2>
<ul>
    <li>Hyperparameter tuning</li>
    <li>Deploy model using Streamlit</li>
    <li>Try advanced architectures (ResNet, EfficientNet)</li>
</ul>

<h2>👩‍💻 Author</h2>
<p>
<b>Anshika Patel</b><br>
GitHub: https://github.com/Anshika2913<br>
LinkedIn: https://linkedin.com/in/anshikaapatel29
</p>
