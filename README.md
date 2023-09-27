##  <img src="https://media.tenor.com/Wq-8a2yGCSkAAAAi/stethoscope-stethoscope-images.gif" width="48" height="48"> Doctor Fee Prediction


This project aims to create a web interface that allows users to predict doctor consultation fees based on their input. The machine learning model was trained on a dataset obtained by scraping data from the Practo website using Selenium. With the use of Python Pandas, the scraped data was thoroughly cleaned & preprocessed for accurate predictions.

![Doctor Fee Prediction](https://github.com/puneetpahadia-da/Doctor_Fee_Prediction_with_Web_Application/assets/97096168/5e7f7967-5c38-48c2-9d73-4bea1d608131)

## Project Details 🚧

This project utilizes Python libraries such as NumPy and Pandas for data cleaning and preprocessing purposes. Matplotlib and Seaborn are used for data analysis and visualization. Scikit-learn (sklearn) is employed for building the machine learning model. Flask, HTML, and CSS are used to build an interactive website.

The main objective is to predict doctor consultation fees based on the following attributes:

- `speciality_of_doctor`: Specialty of the doctor
- `degree_type`: Type of degree (e.g., MBBS, MD, BDS)
- `year_of_experience`: Total years of experience
- `Location`: Clinic location
- `city`: City of the clinic
- `dp_score`: Doctor-patient experience score
- `npv_`: Number of people's votes

## Problem Statement
The problem at hand is to develop a robust machine learning model and an interactive web application that can accurately predict doctor consultation fees based on various attributes. The goal is to create a tool that assists both patients and healthcare providers in estimating the consultation fees for medical professionals.

## Project Roadmap

![Screenshot 2023-08-09 233443](https://github.com/puneetpahadia-da/Doctor_Fee_Prediction_with_Web_Application/assets/97096168/05fb5914-dbef-4f08-bebc-eba1569c8192)

## Python Files 🐍

### Data Extraction 🌐
- The data extraction phase involves collecting raw doctor information from the online medical consultancy booking site Practo. This is achieved using the Jupyter Notebook `Scrapping code.ipynb`.

### Data Preprocessing 🧹
- In the preprocessing phase, data is cleaned, missing values are handled, and exploratory data analysis is performed. The Jupyter Notebook `Preprocessing_EDA.ipynb` includes the cleaning and visualization code.

### Machine Learning Modeling 🤖
- The machine learning model is built using Scikit-learn and is implemented in the Jupyter Notebook `ML_Models.ipynb`. This model predicts the consultation fee for doctors based on the provided attributes.

## DATA 📊

### Raw Data 📂
- The collected data is stored in `raw_practo.csv`.

### Cleaned Data 🧼
- The cleaned data is saved in `clean_practo.csv`.


##  <img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> **User's Manual**

| Files/Folder| Description |
| ------------- | ------------- |
| **Data** | This folder provides scrapped data in csv format |
| **Python Files** | This contains the .ipynb file of the analysis for Data Scraping, Data cleaning, EDA and ML Models.  |
| **Web Application** | This contains the .HTML, app.py and model.pkl file for User Interface  |

<br>

<p align="center"><img src="https://i.pinimg.com/originals/13/66/c9/1366c95f8c249b8422d2caaae287cb63.gif" width="400" ></p>

## Findings from the Doctor Fee Prediction Project 🧪

- According to the Practo dataset, Bangalore has the highest number of doctors.

  ![Screenshot 2023-08-09 233443](https://github.com/puneetpahadia-da/Doctor_Fee_Prediction_with_Web_Application/assets/97096168/2379a6b6-e0d2-44e9-8d4a-82b4d3c2584f)

  
- The most common degrees among doctors are MBBS, BDS, and BPTh/BPT, with the highest representation in the dataset.


  ![Screenshot 2023-08-09 233626](https://github.com/puneetpahadia-da/Doctor_Fee_Prediction_with_Web_Application/assets/97096168/fd159758-6a33-47c6-b5b6-d60d659b582d)

- The dataset indicates that the three most prominent specialties among doctors are:
  - Dentist
  - Gynaecologist
  - Pediatrician

![Screenshot 2023-08-09 233739](https://github.com/puneetpahadia-da/Doctor_Fee_Prediction_with_Web_Application/assets/97096168/0234c914-cf76-4da4-8556-b6362cab4710)

 <br>

## Web Application 💻

The project includes an interactive web application developed with Flask. The application allows users to input values for `speciality_of_doctor`, `degree_type`, `year_of_experience`, `Location`, `city`, `dp_score`, and `npv_` to obtain a predicted consultation fee for doctors. The machine learning model, stored as `model.pkl`, is integrated into the web application.

![Web Application](https://github.com/puneetpahadia-da/Doctor_Fee_Prediction_with_Web_Application/assets/97096168/0d241b18-c909-45af-84af-0822abe2d8e7)

### Directory Structure for Web Application 📂

- `app.py`: Flask application handling user inputs and serving the web page.
- `model.pkl`: Trained machine learning model for predicting consultation fees.
- `templates/`: Directory containing the HTML template for the interactive web application.
  - `index.html`: HTML template allowing users to input attributes and get predicted fees.

## Presentation 📢

- `Doctor Fee Prediction.pdf`: Presentation showcasing project details and insights.

- `README.md`: Overview of the project, its structure, and usage instructions.

## Usage 🚀

1. Review the data extraction process and preprocessing steps in the `Python Files` directory.
2. Understand the machine learning model creation in the `Python Files/ML_Models.ipynb` directory.
3. Explore the raw and cleaned data in the `DATA` directory.
4. Run the web application using the code provided in the `Web Application` directory (`Web Application/app.py`).
5. Input the required attributes on the web page to receive a predicted consultation fee.

## 🏥 Challenges and Learnings

1. **Feature Engineering:** Handled complex features, especially those with diverse and numerous categories. 

2. **Model Selection:**  Explored different ML models to identify the Best models.

3. **Hyperparameter Tunning:**  Hyperparameter tuning was time-consuming due to limited time for model development

4. **Model Deployment:**  Explored model deployment options.

 
## 🏥 Conclusion

1. **Healthcare Accessibility:** By giving patients an idea of potential costs, it helps them seek appropriate medical care without the barrier of uncertainty about fees.

2. **Transparency and Trust:**  Clear fee estimates foster trust and confidence in medical services, enhancing the doctor-patient relationship.

3. **Efficiency for Providers:** With fee estimates readily available, administrative processes become smoother, leading to improved overall service efficiency.

## Acknowledgments 🙏

We extend our appreciation to the mentors and faculty members for their guidance and support throughout the project.
