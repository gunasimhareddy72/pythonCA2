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

##### vajja mahendra (10639742)
[1] Responsible for creating GET service for home page whih returns the count of patient doctors and appointments.
[2] Created all the API services required for appointment module. This includes GET Appointment service to display list of all appointments, POST Appointment service to register the new appointment and PUT Appointment service to update the appointment data. 
[2] Created all the API services required for patient module. This includes GET patient service to display list of all patients, POST patient service to register the patient and PUT patient service to update the patient data. 
[3] Created required javascript functions that are required for user interaction with doctors page. It includes calling an 
API to get the list of doctors, Showing modal if user clicks on delete doctor button and deleting the selected doctors 
by calling delete doctor API service. Also showing modal with selected doctor details populated on input field. User can update this values as required and clicking on save, it call update doctors API service with updated data. 
[4] Created required javascript functions that are required for user interaction with home page. It includes calling an 
API to get the count of doctors, patient and appointments. Also includes navigating to respective pages when clicks on button on home page. 
[5]  Added config.JS file with app the required application configurations. 


## screenshot

<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/1.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/2.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/3.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/4.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/5.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/6.png" height="300"></a>
<a href="../../" target="_blank"><img src="https://raw.githubusercontent.com/tushariscoolster/HospitalManagementSystem/master/7.png" height="300"></a>



## Contributing

Open an issue first to discuss potential changes/additions. If you have questions with the guide, feel free to leave them as issues in the repository. If you find a typo, create a pull request. The idea is to keep the content up to date and use github’s native feature to help tell the story with issues and PR’s, which are all searchable via google. Why? Because odds are if you have a question, someone else does too! You can learn more here at about how to contribute.

*By contributing to this repository you are agreeing to make your content available subject to the license of this repository.*

### Process
    1. Discuss the changes in a GitHub issue.
    2. Open a Pull Request, reference the issue, and explain the change and why it adds value.
    3. The Pull Request will be evaluated and either merged or declined.

## License

 Use this guide. Attributions are appreciated._

### Copyright

Copyright (c) 2014-2015 [Tushar Borole](http://www.tusharborole.com)

### (The MIT License)
Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

##Last but not least
This is made in India with love and passion  ʕ´•ᴥ•`ʔ

<a href="../../" target="_blank"><img src="http://lonamowers-hrd.appspot.com/images/made_india.jpg" height="200"></a>

