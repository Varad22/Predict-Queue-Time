# Predict-Queue-Wait-Time in a Hospital

Waiting in long queues at hospitals can be frustrating, especially when you're already feeling unwell. Our project aims to alleviate this frustration by providing approximate queue wait times based on live data, allowing patients to plan their visits accordingly. Here's how our web app works:

## Workflow in the Hospital

1. **Entry**
2. **Registration Desk**
3. **Billing Counter**
4. **Waiting Area**
5. **Doctor's Cabin**
6. **Pharmacy**
7. **Exit**

## Features

### 1. Doctor's Availability

- Users can check the timetable, working hours, qualifications, and OPD details of every doctor from the comfort of their homes.
- This feature helps users determine if the doctor's schedule aligns with their own, allowing for better planning of hospital visits.

### 2. Planning a Visit

- Users can enter the day and time they wish to visit a specific doctor.
- The app provides an approximate total journey time from entering the hospital to leaving, helping users plan their schedules effectively.

### 3. Visit to Hospital and Prediction of Queue Wait Time

- Upon arrival at the hospital, users receive a one-time RFID card at the registration desk.
- The RFID card is scanned at various stages (registration desk, billing counter, doctor's cabin) to track the patient's progress.
- Our app utilizes this data to predict the queue wait time for each patient, reducing frustration and uncertainty.

### 4. Services Provided

- During consultations, if additional tests are recommended, users can view the cost and duration of these tests in advance.
- This feature empowers patients to make informed decisions about their healthcare.

## How to Use

1. Clone the repository to your local machine.

2. Navigate to the project directory.

3. Create a virtual environment.

4. Activate the virtual environment:
- On Windows:
  ```
  .\env\Scripts\activate
  ```
- On macOS and Linux:
  ```
  source env/bin/activate
  ```

5. Move the `app.py` file, `templates` folder, and `static` folder to the virtual environment created.

6. Run the Flask application.
