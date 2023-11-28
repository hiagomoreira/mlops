# PetCare Solutions MLOps Project

## Background

In a world where responsible pet adoption is a priority, "PetCare Solutions" (fictional) has established itself as a leading platform for connecting animal shelters with potential new pet owners.

PetCare Solutions currently utilizes an animal classification algorithm (for dogs and cats) in their photos. However, they are facing challenges in allowing their data science team and machine learning engineers to effectively enhance and deploy models. The company aims to create an MLOps platform that fosters collaboration and continuous model improvement, enabling seamless model enhancements and deployments.

The client has provided the training code attached to this task.

## Project Deliverables

1. **GitHub Repository:**
    - Link to the GitHub repository containing the project code.

2. **Project Report (PDF):**
   - A comprehensive report in PDF format that includes:
       - Project overview and objectives.
       - Approach and methodology used.
       - Challenges faced and solutions implemented.
       - Contributions of each team member.
       - Conclusion and future recommendations.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/hiagomoreira/mlops.git
   cd mlops
   git checkout t1_data_versioning
   ```

2. **Suggestion - Create and Activate the Virtual Environment:**

   ```bash
   python -m venv venv       # Creates the virtual environment
   source venv/bin/activate  # Activates the virtual environment on Linux/Mac
   .\venv\Scripts\activate   # or Activates the virtual environment on Windows
   ```

3. **Install Dependencies:**

   ```bash
    pip install -r requirements.txt
   ```

4. **Get Dataset from Google Drive:**

   - Use DVC to pull the dataset from Google Drive.

     ```bash
     dvc pull -r gdrive
     ```

5. **Run the Training Code:**

     ```bash
     python cnn_image_classifier.py
     ```
