<h1>MNIST Classification with SVM & XGBoost</h1>

<h2>Overview</h2>
<p>This project trains and evaluates two machine learning models, <strong>SVM</strong> and <strong>XGBoost</strong>, on the MNIST dataset. The script includes accuracy evaluation, confusion matrices, and visualization of true vs. predicted labels.</p>

<h2>Features</h2>
<ul>
    <li>Loads the <strong>MNIST dataset</strong> from scikit-learn.</li>
    <li>Trains <strong>SVM</strong> and <strong>XGBoost</strong> classifiers.</li>
    <li>Visualizes model accuracy using <strong>bar charts</strong>.</li>
    <li>Displays <strong>confusion matrices</strong> for error analysis.</li>
    <li>Shows <strong>true vs. predicted labels</strong> using scatter plots.</li>
    <li>Uses <strong>OpenCV</strong> to display upscaled and denoised MNIST images.</li>
</ul>

<h2>Installation</h2>
<pre><code>pip install numpy matplotlib seaborn scikit-learn xgboost opencv-python</code></pre>

<h2>Usage</h2>
<pre><code>python svm_xgb.ipynb</code></pre>

<h2>Code Structure</h2>
<ul>
    <li><strong>Data Loading:</strong> Loads and splits MNIST dataset.</li>
    <li><strong>Feature Scaling:</strong> Scales input data for SVM.</li>
    <li><strong>Model Training:</strong> Trains SVM and XGBoost models.</li>
    <li><strong>Evaluation:</strong> Computes accuracy and confusion matrices.</li>
    <li><strong>Visualization:</strong> Uses Matplotlib and OpenCV for graphs and image display.</li>
</ul>

<h2>Example Output</h2>
<p><strong>Accuracy:</strong></p>
<pre><code>Training SVM...
SVM Accuracy: 0.9806
Training XGBoost...
XGBoost Accuracy: 0.9524</code></pre>

