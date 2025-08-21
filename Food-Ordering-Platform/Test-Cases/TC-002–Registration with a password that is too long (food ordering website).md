#  Test Case: TC-002 – Registration with a password that is too long (food ordering website)

##  Desciption
Checking if user can register successfully while entering password longer than 50 characters.

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
| 3    | Enter proper data for email and phone number fields  | All required fields are correctly filled                       |
| 4    | In password field input text longer than 50 characters  | User gets message that password is too long |
| 5    | Click sign in button   | User doesn't get registered  |


---

##  Test data

| Field        | Value                   |
|--------------|-------------------------|
| Email        | john.doe@example.com     |
| Password     | Lorem ipsum dolor sit amet, consectetur adipiscing elit                |
| Phone        | 553876454               |

---

##  Expected result
User can't register with password longer than 50 characters. 

---

##  Test type
- Functional test
- Negative scenario

---

##  Status
**Fail**

---

##  Comments
- It is worth repeating the test with password that is too short. 
