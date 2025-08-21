#  Test Case: TC-001 – Registration of new user (food ordering website)

##  Desciption
Checking if user can register successfully using the correct details.

---

##  Preconditions
- User is not logged in
- Registration page is available 

---

##  Steps

| Step | Action                                             | Expected result                                                |
|------|----------------------------------------------------|----------------------------------------------------------------|
| 1    | Go to food ordering website                        | Home page is showing                                           |
| 2    | Click on Sign in and then choose Sign up           | User gets redirected to registration page                      |
| 3    | Enter proper data (email, password, phone number)  | All required fields are correctly filled                       |
| 4    | Click Sign Up button                               | The message "Registration completed successfully" is displayed |


---

##  Test data

| Field        | Value                   |
|--------------|-------------------------|
| Email        | john.doe@google.com     |
| Password     | 12345678                |
| Phone        | 553876453               |

---

##  Expected result
User gets successfuly registered and redirected to user profile page. 

---

##  Test type
- Functional test
- Positive scenario

---

##  Status
**To Do**

---

##  Comments
- It is worth repeating the test with different email domains (ex. outlook, wp, onet).
- Add negative test with incorrect email format.