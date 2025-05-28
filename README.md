Multi-Scale and Multi-Task Ship Detection using Texture-Semantic Collaboration Learning


📌 Overview
This project presents an advanced deep learning approach for detecting ships in remote sensing imagery using a novel combination of texture analysis and semantic understanding across multiple scales and tasks. The work is motivated by the limitations of traditional ship detection methods when faced with varying ship sizes, orientations, and cluttered maritime backgrounds.

The proposed system leverages Active Rotating Filters (ARF) and Oriented Response Networks (ORN) to achieve high-accuracy detection under diverse environmental conditions, supporting applications in maritime surveillance, illegal fishing prevention, and vessel tracking.

📚 Project Features
⚙️ Deep Learning Backbone: Faster R-CNN with enhancements like ARF, rotation-invariant features, and context modules.
🖼️ Texture-Semantic Collaborative Learning: Fusion of visual texture with semantic segmentation to improve ship localization.
🌐 Multiscale Analysis: Improved Feature Pyramid Network (IFPN) for better detection of ships of different sizes.
🧠 Custom Dataset: Includes 1,500 labeled ship training images and 3,000 testing images from remote sensing sources.
📊 Evaluation Metrics: Utilizes mAP, IoU, precision, and recall to validate performance.



🧪 Technologies Used
Languages: Python

Frameworks & Libraries:
TensorFlow / Keras
PyTorch (optional)
NumPy, Scikit-learn
Matplotlib, Seaborn, Plotly
OpenCV, Pillow

IDE: Jupyter Notebook

Hardware: Recommended i5 Dual Core, 16–32 GB RAM, 200 GB HDD



🚀 How to Run
Clone the repository:
git clone https://github.com/your-repo/ship-detection-project.git
cd ship-detection-project

Install required packages:
pip install -r requirements.txt

Run model training:
python src/train_model.py

Evaluate results:
python src/evaluate.py


📈 Results
Training Accuracy: 97%
Validation Accuracy: ~94%
mAP: 0.88
IoU Score: 0.84
Heatmaps and detection outputs show improved recognition of ships under variable lighting and rotation, outperforming conventional methods.


🧪 Testing & Validation
Unit Testing
Integration Testing
Functional Testing
Visualization of false positives/negatives using RGB histograms


📌 Real-World Applications
Maritime surveillance and coastal security
Illegal fishing and smuggling detection
Port traffic monitoring
Environmental and disaster response


🔬 Future Enhancements
Integrate transformer-based feature extraction
Improve ship orientation estimation using bow direction
Optimize model for real-time deployment on drones and satellites


📄 References
Remote Sensing Journal
IEEE Transactions on Geoscience
ISPRS Journal
SAR + Optical Fusion Studies

👥 Contributors
Vamsi Krishna K
Rohith Chowke
K.V. Sravan Kumar

