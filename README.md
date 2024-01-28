# Project 7 - MLOps and DataOps

---
Welcome to the Health Insurance Prediction Project!

This project aims to provide insights into creating a health insurance prediction application using machine learning. Follow the steps below to set up the environment and run the application:

---


**Step by Step Guide:**

1. **Create Virtual Environment:**
   Open your terminal and run the following command to create a virtual environment.
   ```bash
   python3 -m venv .venv
   ```

2. **Activate the Environment:**
   Activate the virtual environment using the command:
   ```bash
   source .venv/bin/activate
   ```
   <img width="639" alt="activate_env" src="https://github.com/keiziapurba/project7_mlops/assets/91368463/46bd4242-2110-413d-b388-ba940e1bf315">


3. **Install Dependencies:**
   Create a file named `requirements.txt` and install the dependencies using the following command:
   ```bash
   pip3 install -r requirements.txt
   ```
   If any issues arise, consider installing the dependencies one by one.

4. **Create app.py:**
   Develop the main application file, `app.py`, to manage the Flask web application.
   <img width="556" alt="app" src="https://github.com/keiziapurba/project7_mlops/assets/91368463/801e8a6c-7530-4bef-a9c9-8055717a1b65">


5. **Build Machine Learning Model:**
   Run the `modellingInsurance.ipynb` notebook to create the ML model (file: .pkl).
   
6. **Organize Folders:**
   Move the 'packages' folder to the 'modules' folder.

7. **Run the Application:**
   Start the Flask application using the command:
   ```bash
   flask run --port 8000
   ```
   <img width="852" alt="run-port" src="https://github.com/keiziapurba/project7_mlops/assets/91368463/511020ca-0edc-441c-aa07-6f435c25c639">


8. **Use Postman for Prediction:**
   Open Postman, import the provided cURL command, and click 'Send' to receive prediction results.
   <img width="1440" alt="prediction-in-postman" src="https://github.com/keiziapurba/project7_mlops/assets/91368463/c8323009-5f22-4fb1-ab74-a0f3bb6105ce">


Feel free to explore and enhance the project based on your needs. Happy coding!
