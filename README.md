<h1> Multi-Stream Fusion of Swin Transformer and CNNs for Automated Retinal Disease Diagnosis </h1>h1>
This repository contains the official implementation of a hierarchical fusion framework for diagnosing Age-related Macular Degeneration (AMD), Cataracts, and Diabetic Retinopathy. 
By integrating the local feature extraction of EfficientNetV2 and DenseNet121 with the global context of Swin Transformers, we achieve a state-of-the-art accuracy of 97.5% on the AMDNet23 benchmark.

🚀 **Key Features:**

* **Hybrid Architecture:** Combines Swin-Tiny, EfficientNetV2-S, and DenseNet121.

* **Triple Fusion Paradigm:** Includes implementation for Concatenation, Self-Attention, and Meta-Training Decision Fusion.

* **Optimized Training:** Two-phase training (Frozen Head → Full Fine-tuning) with Early Stopping.
