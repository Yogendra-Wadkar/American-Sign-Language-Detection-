<div style="background-color: #e6f2ff; padding: 20px; border-radius: 10px;">

<h1 style="text-align: center;">🤟 American Sign Language Detection 🤟</h1>

<h2>📖 Introduction</h2>
<p>
This project focuses on developing an <b>American Sign Language (ASL) Detection System</b> using <b>Convolutional Neural Networks (CNN)</b> with TensorFlow and Keras.<br>
The model is trained to recognize <b>A–Z alphabets</b> and <b>special gestures</b> (<code>Space</code>, <code>Delete</code>, and <code>Nothing</code>) from static images, providing a practical demonstration of deep learning and computer vision techniques.
</p>

<hr>

<h2>📁 Project Structure</h2>
<pre>
ASL_Detection/
│
├── Dataset/
│   ├── asl_alphabet_train/   # Training images (A-Z + special signs)
│   ├── asl_alphabet_test/    # Testing images (29 sample images)
│
├── asl_model.h5              # Trained CNN model file
├── ASL_Detection_Notebook.ipynb  # Jupyter Notebook (full code)
├── README.md                 # Project introductory file
</pre>

<hr>

<h2>📊 Model Performance</h2>
<ul>
  <li><b>Training Accuracy:</b> ~80.75% (after 10 epochs)</li>
  <li><b>Validation Accuracy:</b> ~58.94%</li>
  <li><b>Testing:</b> On real-world test images, <b>28 out of 29 images</b> were correctly classified.<br>
  <i>Only one minor misclassification: (M classified as N).</i></li>
</ul>

✅ Achieved <b>high prediction accuracy</b> on real input images.

<hr>

<h2>🛠 Requirements</h2>
<p>To run this project, you need to install:</p>

<ul>
  <li>Python 3.x</li>
  <li>TensorFlow</li>
  <li>Keras</li>
  <li>OpenCV</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
</ul>

<p>You can install all dependencies using:</p>

<pre><code>pip install tensorflow keras opencv-python numpy matplotlib</code></pre>

<hr>

<h2>🙏 Acknowledgement</h2>
<p>
Special thanks to <b>Unified Mentor</b> for providing the project guidance and dataset structure.<br>
This project serves as a practical learning implementation of <b>deep learning</b>, <b>image classification</b>, and <b>American Sign Language recognition</b>.
</p>

<hr>

<h2 style="text-align: center;">🚀 Let's decode gestures into language! 🚀</h2>

</div>
