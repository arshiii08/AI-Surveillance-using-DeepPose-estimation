# 📡 Privacy-Preserving Surveillance Using WiFi CSI and Pose Estimation

This project explores an innovative surveillance approach using WiFi Channel State Information (CSI) combined with AI-powered pose estimation to detect human activity — including suspicious or violent behavior — without compromising individual privacy.

---

## 🚀 Overview

Conventional CCTV-based systems are plagued by privacy concerns, high operational costs, and visual limitations. This project proposes a non-visual alternative using everyday WiFi signals. By analyzing CSI variations caused by human movement and combining it with models like DensePose, we can estimate human posture and behavior in real-time without any camera input.

---

## 🧠 Key Features

- 🔐 **Privacy-first approach**: No visual or personally identifiable data.  
- 📶 **WiFi-based activity recognition**: Leverages CSI data to infer human motion.  
- 🤖 **AI-powered behavior detection**: Utilizes modified DensePose architecture.  
- 🏠 **Plug-and-play deployment**: Can integrate with existing WiFi infrastructure.  
- 🛡️ **Applicable for sensitive environments**: Schools, hospitals, homes, etc.

---

## 📁 Repository Structure

├── Minor_Project_Final.ipynb      # Main implementation notebook
├── models/                        # Trained AI model files (to be added)
├── datasets/                      # CSI data used for training/testing (to be added)
├── README.md                      # Project overview and setup
├── requirements.txt               # Required libraries and dependencies
└── utils/                         # Preprocessing and utility scripts (if any)


---

## 🛠️ Methodology

1. **Data Collection**: CSI data collected using WiFi routers.
2. **Pose Estimation Model**: DensePose architecture adapted to work with signal features.
3. **Training Pipeline**: Trained on labeled human movements using transfer learning.
4. **Real-time Inference**: Signal-to-pose inference on edge-compatible devices.
5. **Testing & Validation**: Evaluated in controlled and real-world environments.

---

## 🧪 Sample Applications

- Home and hospital safety systems
- Surveillance in camera-restricted zones
- Intrusion detection for smart homes

---

## 💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/wifi-csi-surveillance.git
cd wifi-csi-surveillance
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

###  3. Run the Notebook

Open the **Minor_Project_Final.ipynb** notebook in Google Colab or a local Jupyter environment and execute the cells sequentially.
