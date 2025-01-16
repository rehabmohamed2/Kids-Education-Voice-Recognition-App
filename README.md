# Kids-Learning-App

## 📖 Project Overview
This interactive learning application is designed to engage kids in a fun and educational way through voice recognition and interactive feedback. The app combines the power of speech recognition and deep learning to teach children about numbers, motions, and animals. With an intuitive interface, kids can actively participate by speaking their responses and receive real-time feedback for their efforts. The app includes gamified elements such as moving characters and changing images to keep the experience exciting and motivating.

---

## 🌟 Features

### 1. Voice-Activated Learning Modules
- Three main modules: **Learn Numbers**, **Learn Motions**, and **Learn Animals**.
- Kids interact with the app by speaking answers, recognized using pre-trained machine learning models.

### 2. Dynamic Feedback System
- Provides immediate feedback within the same frame:
  - "Correct!" in green for right answers.
  - "Wrong, try again!" in red for incorrect responses.
- Updates content dynamically when the child gives the correct response.

### 3. Interactive Animations
- In the **Learn Motions** module, kids direct a moving character (Dora) within a box by saying commands like "Up," "Down," "Left," or "Right."

### 4. Kid-Friendly Interface
- Clean and vibrant design with a colorful background and buttons.
- Easy-to-read text and a clear layout tailored for children.

### 5. Gamified Elements
- Images for numbers and animals change dynamically upon correct responses to maintain engagement.
- Real-time character movements based on voice commands in the motion learning module.

---

## 🛠️ Tech Stack

- **Frontend**: Python (Jupyter Notebook for prototyping), Tkinter for the user interface.
- **Machine Learning**: TensorFlow/Keras models for speech recognition.
- **Deep Learning Models**:
  - **Numbers Recognition**: `numbersv3.h5`
  - **Motion Commands**: `motions.h5`
  - **Animal Recognition**: `animalsv3.h5`
- **Interactive Media**: PNG assets (e.g., `dora.png`, `back.png`) for visuals and animations.

---

## 🚀 Getting Started

### Prerequisites
Ensure the following are installed:
- Python 3.7+
- TensorFlow/Keras
- Required libraries: `pip install -r requirements.txt`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rehabmohamed2/Kids-Education-Voice-Recognition-App.git
   cd kids-learning-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

---

## 📂 Project Structure

```
Kids-Learning-App/
├── app.ipynb             # Jupyter Notebook for prototyping
├── app.py                # Main Python application file
├── models/
│   ├── animalsv3.h5      # Model for animal recognition
│   ├── motions.h5        # Model for motion commands
│   ├── numbersv3.h5      # Model for numbers recognition
├── assets/
│   ├── dora.png          # Dora character image
│   ├── back.png          # Background image
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---


## 📈 Future Enhancements
- Add more learning modules (e.g., colors, shapes).
- Include additional gamified elements like points and badges.
- Introduce multi-language support for global accessibility.
- Optimize voice recognition for accents and background noise.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## 📧 Contact
For any inquiries, reach out via:
- [GitHub](https://github.com/rehabmohamed2)
- Email: [rehabmohamed151220@gmail.com)

---

### ⭐ Support the Project
If you find this project helpful, give it a ⭐ on GitHub!

