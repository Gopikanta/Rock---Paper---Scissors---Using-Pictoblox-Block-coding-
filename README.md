# Rock---Paper---Scissors---Using-Pictoblox-Block-coding-


🪨📄✂️ Rock Paper Scissors using PictoBlox & OpenML

📖 About the Project

This project is an interactive Rock Paper Scissors game developed using PictoBlox, a block-based programming platform that integrates machine learning and AI concepts. The main objective of this project is to recognize real-time hand gestures (rock, paper, and scissors) through a webcam and use a trained ML model to play the game automatically.

By using the OpenML environment in PictoBlox, a custom image classification model was created and trained on images captured directly from the webcam. Once the model achieved satisfactory accuracy, it was exported into block code to enable real-time gesture detection and game logic implementation.

🧠 Machine Learning Workflow

Dataset Creation:

Used the webcam to capture multiple images for each hand gesture:

✊ Rock

🖐️ Paper

✌️ Scissors

Labeled the images accordingly in the OpenML environment.

Model Training:

Trained the model using adjustable parameters such as:

Epochs: Number of times the model sees the entire dataset.

Batch Size: Number of samples processed before updating the model.

Learning Rate: Controls how much the model learns in each update.

The model was trained and evaluated to achieve accurate gesture recognition.

Model Integration:

Exported the trained model to PictoBlox block code.

Integrated it with logic blocks to detect the user’s gesture in real time.

Game Implementation:

The program randomly generates the computer’s choice.

The webcam detects the user’s gesture using the trained model.

The winner is decided based on standard Rock-Paper-Scissors rules.

⚙️ Tools & Technologies

PictoBlox – for creating block-based AI applications.

OpenML Environment – for model training and testing.

Webcam – for capturing real-time hand poses.

Machine Learning Model – for gesture recognition.

🎮 How It Works

Launch PictoBlox and open the OpenML environment.

Capture and label images for rock, paper, and scissors gestures.

Train the model by setting epochs, batch size, and learning rate.

Test the model accuracy and export it to block coding.

Create game logic to compare your gesture with the computer’s random choice.

Run the project — show your hand to the camera and play in real time!

📊 Results

The model successfully recognized hand gestures with good accuracy.

Real-time detection worked smoothly through the webcam.

The game could identify and display the result of each round instantly.
