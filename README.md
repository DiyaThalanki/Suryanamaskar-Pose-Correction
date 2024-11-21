# Suryanamaskar Pose Correction

## 📖 Project Overview  
The **Suryanamaskar Pose Correction** project is an interactive tool designed to help users perform the Surya Namaskar (Sun Salutation) sequence with precision and alignment. Through the use of advanced pose tracking and 3D visualization, the application provides real-time feedback, ensuring that users perform each asana (pose) correctly. It assists practitioners in refining their technique by detecting errors in posture and offering corrections based on pre-defined target outlines.

Whether you're a beginner learning the sequence or an experienced yogi aiming for perfect alignment, this tool provides a guided and structured approach to mastering Surya Namaskar.

---

## ✨ Features  
- **Real-Time Pose Detection**: The application uses PoseNet to track and evaluate user movements, providing immediate feedback and suggestions for correction.
- **3D Pose Visualization**: Pre-modeled target poses are rendered in a 3D interactive environment, providing users with a clear visual reference.
- **Pose Accuracy Validation**: The system compares live user poses with pre-modeled asana outlines, offering feedback on misalignments or deviations.
- **Step-by-Step Guidance**: The tool takes users through each step of the Surya Namaskar sequence, offering detailed instructions and corrections throughout the process.
- **User-Friendly Interface**: An intuitive web interface allows users to interact with the system easily, making the experience accessible for beginners.

---

## 🛠️ Technologies Used  
- **Three.js**: A powerful JavaScript library used to render and display the 3D models of the poses directly in the browser.
- **Blender**: Used to create and export high-quality, accurate 3D models of each Surya Namaskar asana for visualization.
- **PoseNet and MediaPipe**: A deep learning model for detecting body keypoints in real-time, enabling the evaluation of user poses and alignment.
- **JavaScript**: The scripting backbone for handling application logic, pose detection, and user interaction.
- **HTML/CSS**: For building and styling the user interface, ensuring the application is visually appealing and easy to navigate.

---

## 🌞 Surya Namaskar Sequence (Asanas)  
The following are the 12 asanas that form the Surya Namaskar sequence, each offering unique benefits for the body and mind:

1. **Pranamasana (Prayer Pose)**: A grounding posture to begin the sequence, focusing on breath and intention.
2. **Hasta Uttanasana (Raised Arms Pose)**: A stretch that opens up the chest and improves flexibility.
3. **Hasta Padasana (Hand-to-Foot Pose)**: A forward bend that stretches the hamstrings and relieves tension.
4. **Ashwa Sanchalasana (Equestrian Pose)**: A deep lunge that opens the hips and strengthens the legs.
5. **Parvatasana (Mountain Pose)**: A posture that stretches the spine and strengthens the arms and legs.
6. **Bhujangasana (Cobra Pose)**: A backbend that helps open the chest and strengthens the spine.

---

## 🚀 How to Run the Project  
Follow these steps to set up and run the project:  

1. **Clone the Repository**:  
   ```bash  
   git clone <repository_url>  
   cd Suryanamaskar-Pose-Correction 
2. **Start a Python Server**:  
   ```bash  
   python -m http.server 8000
3. **Access the Application**:  
   Open your browser and navigate to: http://localhost:8000
   Open index.html to begin using the application.
