# Final-year-project: Automatic Facial Age Estimator Web App
Web Application for Automatic Facial Age Estimation of Black Persons(Deep learning approach)

## Home
- The welcome Page looks like this:
  
 ![App Home](https://github.com/htaofeek01/Final-year-project/blob/main/images/home.JPG)
 
## Tools used
- Programming language and frameworks: Python, Tensorflow, Ktrain, Flask, Git-Bash
- Model training and evaluation: Google colab, Vs code
- WebApp: HTML, CSS, JSON, Python, Flask
- Dataset: BlackFaces
- Offline testing: Vscode terminal and Chrome browser
  
## Flow Chart

![Flow chart](https://github.com/htaofeek01/Final-year-project/blob/main/images/flowchart.png)

## Project Files
- `frontend`: contains all Html files associated with the User interface design.
- `model`: contains the Age prediction model.
- `Template`: contains the CSS files and bootstrap used to properly render the Html pages for clean and attractive UI.
- `images`: contains images from project.
- `static`: contains associated image files used for the AFAE system such as background, favicon.
- `test`: contains the temporary files used in testing the AFAE system.
- `app.py`: flask app.
- `imageScript.py`: Python script used to download the collected images submitted to FAED dataset in batches.
- `requirements.txt` :To effectively setup and run the web App on a new machine, the user has to install this file.
- `storage.py`: a python script that captures and stores users’ data in the `Storage.json` file.
- `Storage.json`: serves as the Authenticator of user identity as registered or new user before using the AFAE system.
- `fyp_age_estimation(ktrain).ipynb`: Jupyter notebook used in training the model.
- `databank.xlsx`: A spreadsheet from which the dataset can be downloaded.
- `BlackFaces` : contains dataset extracted from `databank.xlsx`.
  
## How To Use this Web app
1. You can either clone this repo or download the code as zip file.
   - Extract the zip file on your PC.
   - The model size is above Github file size limit. Download the model [here](https://drive.google.com/drive/folders/1KlAGHDwihZIUSw7oi5FGVXxtaH7_a0qq?usp=sharing) and place the model binary files in the `model` folder
   - Open a Terminal(Cmd/Bash) to run the App

2. It's recommended that a virtual environment is used to install the app packages. [Read more on virtual env](https://docs.python.org/3/library/venv.html)
   - For Gitbash: Type the code `python -m venv afae_venv` to setup a virtual environment. And
   - Activate the virtual env. with `source venv /afae_venv`

3. Install the requirements.txt file to automatically download and setup the app dependencies(packages).
   - Use the command `pip install -r requirements.txt` to set up the app on your PC

4. Launch the WebApp(Offline Setup)
   - Use `python app.py` or `flask --app run app.py`

5. The terminal should display a default IP address to run WebApp in your browser.
   - Ensure the computer is connected to the internet so that the Web UI bootstrap components can be loaded for a beautiful interface.
   - Proceed to test the App

6. Register as new user or loging with initial credentials after your first login.
   - You try the Automatic Facial age estimation as many time as you want.
   - Ensure the system can detect your face(proper room lightning)
   - The Age Demo looks like this:
     
    ![Age Demo](https://github.com/htaofeek01/Final-year-project/blob/main/images/result1.JPG)

7. For live testing and Demo anywhere.
   - App not available

   *PS: Incase of any bug or misinformation, kindly reach out to the developer of the WebApp via email*
   [Taofeek Hammed](htaofeek95@gmail.com)
   
## Conclusion
Overall, this research contributes valuable insights and a high-performance model and Web Application for Automatic Facial Age Estimation of black persons using a Deep learning approach, with implications for diverse applications in industries such as
security, healthcare, and personalized user experiences.

(c) `Teekay.ai` 2024. All rights reserved.
