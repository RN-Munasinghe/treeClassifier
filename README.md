🌿 Project Overview
This project focuses on developing a neural network-based classifier to identify and distinguish between three visually similar tree species found in the university garden:

Piper nigrum (Black Pepper)

Piper betle Linn (Betel)

Piper longum (Long Pepper)

Traditional identification methods rely on expert knowledge, so the team aimed to automate this process using machine learning techniques based on leaf characteristics.

📊 Data Collection & Preparation
Leaves were collected from different university locations ensuring healthy, undamaged samples.

Physical traits like length, width, tip length, base angle, number of veins, and petiole length were measured.

A CSV dataset with 75 leaf samples was prepared for training.

🧠 Model Architecture & Training
A Sequential neural network model was built using Keras with:

Input layer

Two hidden layers (ReLU activation)

Output layer (Softmax for 3 species)

Model was trained over 20 epochs, using categorical crossentropy and Adam optimizer.

📈 Results
Achieved 100% accuracy on both validation and test datasets.

The classifier showed strong confidence in distinguishing the three species.

Though results were excellent, the authors noted a potential for overfitting and recommended future testing on more diverse data.

🔍 Conclusion
The project demonstrates a successful application of deep learning in botany, particularly for challenging species identification tasks. It opens up possibilities for automated plant classification tools in environmental monitoring and research.
