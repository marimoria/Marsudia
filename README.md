# Marsudia Arduino Trashbin 🗑️
🌿🗞️ An Arduino-based smart trashbin built to recognize organic & inorganic matter using Arduino sensors.

## 🛠️ Features
- ♻️ **Automatic** classification.
- 🔍 **Sensor-based** detection.
- ⚙️ Servo Mechanism for **Lid/Compartment Control**.
- 🧠 Marsudia Website to document & share.

## 🚀 Live Demo & Paper
[🔗 Click here to view it live](https://marimoria.github.io/Marsudia/).
[📃 Click here to view our paper](https://drive.google.com/file/d/1xtQZ9iF_dgD9lXMwCHjTpvPHFTkrkfkV/view?usp=sharing).
> 📌 Please read our paper for detailed experimentation process & results.

## 🔬 Abstract
```yaml
Waste is leftover material generated from human activities or natural
processes and requires optimal processing efforts to avoid negative impacts on the
environment. Unfortunately, the lack of facilities and the low awareness of the
community in sorting waste are the main obstacles in the waste management
process. Therefore, this research aims to develop an innovative Arduino-based
smart trash can that can automatically sort inorganic and organic waste. In
addition, this research also aims to raise awareness and inspire the community
through the provision of web-based tutorials.

This research is a type of quantitative study using experimental methods.
The experimental technique was carried out by testing the trash can with 20 pieces
of waste (10 organic and 10 inorganic). After that, the data generated is processed
through quantitative calculations. Then, the accuracy results are used to explain
the steps for creating the trash bin and tutorial website.

The Marsudia website is designed as a platform connecting users and the
system (interface) that allows control via the web with various devices without the
need for additional software installation by utilizing the Arduino Cloud System.
The website structure includes a homepage with the main product display, a
navigation bar for accessing menus such as Coding, Tutorial, Equipment, and
Details. The Coding page serves to provide code, the tutorial gives instructions on
how to run the trash, the equipment page provides tools and materials, and the
details page explains the accuracy of the trash. Based on the experimental results,
the Arduino-based automatic waste sorter can sort waste with an accuracy of 90%,
a precision of 100%, and a recall capability of 80%, making it effective but in
need of system improvement.

Keywords: Arduino, smart trash bin, waste sorting
```

## 📦 Built With
Website:
- [Vue 3](https://vuejs.org/)
- [Vite](https://vitejs.dev/)

Trashbin:
- Arduino Uno R3
- Breadboard
- Sensor Inductive Proximity LJ12A3-4-Z/BX
- Sensor Capacitive Proximity LJC18A3-B-Z/AX
- Sensor Hujan (Sensor Raindrop)
- Sensor Ultrasonic HC-SR04
- DC Servo Motor SG90
- Motor Stepper 5V 28BYJ-48 dan ULN2003 Driver

## ⚙️ Setup Instructions
```bash
# Clone the repository
git clone https://github.com/marimoria/Marsudia.git
cd marimoria-web

# Install dependencies
npm install

# Run dev server
npm run dev

# Build the project
npm run build
```

## ⭐ Acknowledgement
- This project was made, built, and documented as a part of SMA Marsudirini Bekasi Scientific Research Project.
- This project was made sincerely with the help of @marimoria & @bladeve.
