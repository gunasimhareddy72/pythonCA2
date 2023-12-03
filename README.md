# Hospital Management System

The hospital management system is a web application built using python, flask, sqliteDB, HTML, CSS and Javascript. 
This application offers various functionalities like patient registration, managing doctors availability and registration and manage doctor appoitments. 
## Contributors
| Name      | Student ID  |
| ----------- | ----------- |
| Neelam Premkumar      | 20000202       |
| vajja mahendra    | 10639742        |
| Guna Simha Reddy     | 10628714        |

## **Getting Started**

1. Install requirements
   ```sh
   pip install flask
   pip install flask_restful
   ```
2. Create a Database file with name 'database.db' in root directory. 
3. Run app
   ```sh
   python app.py
   ```

## Configure

```json
{
  "database": "database.db",
  "port": 5000,
  "host": "127.0.0.1"
}
```
## documentation
Below link will open the Postman collection to try the services that this application consumes. 
[Click here to view documentation](https://documenter.getpostman.com/view/457459/hospitalmanagementsystem/2HQup9)


## Responsibility of each individual contributor

#### Neelam Premkumar (20000202)
* Responsible for creating initial schemas for the doctors, patient and appointment table. 
* Created all the API services required for patient module. This includes GET patient service to display list of all patients, POST patient service to register the patient and PUT patient service to update the patient data. 
* Created required javascript functions that are required for user interaction with doctors page. It includes calling an 
API to get the list of doctors, Showing modal if user clicks on delete doctor button and deleting the selected doctors 
by calling delete doctor API service. Also showing modal with selected doctor details populated on input field. User can update this values as required and clicking on save, it call update doctors API service with updated data. 
* Responsible for handling user interaction using javascript for patients page. It includes calling an 
API to get the list of patients on load of page, Showing modal with selected doctor details populated on input field. User can update this values as required and clicking on save, it call update doctors API service with updated data. Showing modal if user clicks on delete patient button and deleting the selected patient by calling delete patient API service. 
* Responsible for adding Vendor CSS like bootstrap and also adding custom CSS styling for the application.

#### vajja mahendra (10639742)
* Responsible for creating GET service for home page whih returns the count of patient doctors and appointments.
* Created all the API services required for appointment module. This includes GET Appointment service to display list of all appointments, POST Appointment service to register the new appointment and PUT Appointment service to update the appointment data. 
* Created all the API services required for patient module. This includes GET patient service to display list of all patients, POST patient service to register the patient and PUT patient service to update the patient data. 
* Created required javascript functions that are required for user interaction with doctors page. It includes calling an 
API to get the list of doctors, Showing modal if user clicks on delete doctor button and deleting the selected doctors 
by calling delete doctor API service. Also showing modal with selected doctor details populated on input field. User can update this values as required and clicking on save, it call update doctors API service with updated data. 
* Created required javascript functions that are required for user interaction with home page. It includes calling an 
API to get the count of doctors, patient and appointments. Also includes navigating to respective pages when clicks on button on home page. 
*  Added config.JS file with app the required application configurations. 


## screenshot

<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/1.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/2.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/3.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/4.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/5.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/6.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/7.png" height="300"></a>





