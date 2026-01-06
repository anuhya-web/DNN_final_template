# DNN_final_template

README — Visual Storytelling with Spatial & Cross-Modal Attention

🚀 Overview
This repository explores how attention mechanisms can improve visual storytelling and sequence prediction.

Instead of relying only on a basic CNN encoder, the model learns to:
•	Spatial attention focuses on the meaningful parts of an image

•	Cross-Modal fusion attention connects images and text in a shared space

•	reconstruct sharper visuals and produce more coherent outputs

By enriching visual features and aligning them with language features, the system produces representations that are more informative and easier for downstream tasks.

Attention: CNN encoders compress images into small latent vectors.



🚀 Installation:
   Create a new notebook environment in Google Colab
   
⚙️ Requirements

•	Python 3.8+ versions
•	PyTorch
•	matplotlib
•	numpy
•	torchvision
•	Transformers


🚀 Features

1️⃣ Spatial Attention

•	sharpens important areas and includes temperature and gamma controls for more precise focus

2️⃣Cross-Modal Fusion Attention

•	It helps the model to learn clear features that understand both the image and the text 

3️⃣ Enhanced Loss Strategy

•	L1 Loss -----> preserves edges
•	MSE Loss -----> stabilizes training
•	Perceptual Loss ------> improves textures
•	Edge Loss ------> sharpens contours 



 🚀 HuggingFace Dataset Support:
 
Compatible with datasets containing sequences of images + captions (e.g. daniel3303/StoryReasoning).

Dataset Requirements contains:

“captions” -----> list of caption strings
“frames” -----> list of PIL images



📂 Project Structure
DNN_final_template/
│

├── experimental_notebook

├── requirements.txt

├── Results

└── README.md


 🤝 Contributing
Community contributions are encouraged.
Enhancements such as new attention designs, better fusion strategies, or training                improvements are welcome — feel free to open an issue and we’ll plan it together.


  📜 License
  

MIT License.

 
