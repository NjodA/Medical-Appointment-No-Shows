# Medical Appointment No Shows
Why do 30% of patients miss their scheduled appointments?


![smiling-people-sitting-chairs-waiting-doctor-s-appointment-time-hospital-men-women-physician-s-smiling-people-128822167](https://user-images.githubusercontent.com/43109841/136189062-f12e5ee9-263d-4e89-b880-7d490a880175.jpeg)


## Brief 
Many patients schedule medical appointments that they do not show up to, thus usually more patients could have been placed in the qeue instead of the no-show patients, but this is not possible because whether a patient is a no-show or a show is determined too late. Wouldn't it be amazing to determine early enough whether the patient is attending or not, that appointments are scheduled with more patients. In this project data associated with the appointments scheduled in a medical center will be analysed. Particulary the variables that affect the attendance of the patients will be identified.

## Dataset Description
The Investigate a Dataset project! The dataset collects information from more than 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. The Project Medical Appointments No Shows is investigating Medical Appointment No Shows dataset which contains historical data for more than 110K appointments made across different medical facilities in Brazil for more than 60k patients, for each record there are 14 Variables, metadata related to appointments date, patients gender, age, medical condition, social support coverage and facilities and 1 TARGET variable "Wither the patient attended the appointment or not. (Based on a kaggle dataset)

## Project Target
What is the explanation for a person making a doctor appointment, receives all the instructions and no-show. Who to blame?

## Data Definition
•	PatientId: Identification of a patient that is unique for each person.

•	AppointmentID: Identification of each appointment.

•	Gender: Male or Female.

•	AppointmentDay: The day of the actual appointment, when they have to visit the doctor.

•	ScheduledDay: The day someone called or registered the appointment, this is before appointment of course.

•	Age: How old is the patient.

•	Neighborhood: Where the appointment takes place.

•	Scholarship: 1 or 0. (this is a program in Brazil to support poor people with their cost of living)

•	Hipertension: Whether a patient is hypertensive or not (True or False).

•	Diabetes: Whether a patient is diabetic or not (True or False).

•	Alcoholism: Whether a patient drinks alcohol or not (True or False).

•	Handcap: Whether a patient has a handicap or not (True or False).

•	SMS_received: 1 or more messages sent to the patient.

•	No-show: "Yes" or "No" ("No" means they showed up on their appointments while "Yes" means they didn't!).


## Questions for Analysis
This analysis aims to outline some possible reasons for patient no-showing at the scheduled appointments, as well as get insights about the Brazilian public health system. To accomplish this, we will first try to understand the data and the context on which they were collected. Then we will exploratory data analysis.

•	What is the percentage of patients who show up on their appointments vs. who not? " Classification> Logistic Regression Model”

•	Is one gender more committed to medical schedules than another? “ Classification> Logistic Regression Model”

•	Where do most appointments take place? “ Classification> Logistic Regression Model”

•	Are patients who received SMS messages reminding them of the appointment likely to attend? “ Classification> Logistic Regression Model”

•	What is the percentage of patients diagnosed with diabetes, hypertension, alcoholism and disability? “ Regression > Linear Regression Model “

•	Is drinking alcohol a cause of missing appointments? “ Classification> Logistic Regression Model”

•	Is the duration between registration and appointment affect the ability to show up? “ Classification> Logistic Regression Model”

•	Do older patients more committed to medical schedules than others? “ Classification> Logistic Regression Model”


## Tools 
•	Pandas: a library offers data structures and operations for manipulating numerical tables and time series.

•	Numpy: a library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices.

•	Matplotlib: a plotting library for the Python programming language and its numerical mathematics extension NumPy.

•	Seaborn: a data visualization library built on top of matplotlib and closely integrated with pandas data structures in Python.

## Data Cleaning 
Data cleaning is the process of detecting and correcting (or removing) corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data. 
Data cleansing may be performed interactively with data wrangling tools, or as batch processing through scripting.

•	Edit the "No-show" column to be in positive form instead of negativity.

•	Edit the "ScheduledDay", and "AppointmentDay" columns datatype to be Datetime.

•	Edit the "PatientId", and "AppointmentID" columns datatype to be String.

•	Delete row with negative age value.


