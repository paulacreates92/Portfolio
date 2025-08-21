# Test Scenario E2E: E2E-001 - Placing an order as a logged-in user

---

## Test purpose

Verify that the logged-in user can complete the full food ordering process – from selecting a restaurant to confirming payment.

---

## Preconditions
- User has an active profile
- User doesn't have any pending orders
- Restaurant is available and open
- Mobile app is downloaded and running

---

## Steps

| Step | Action                           |
|------|----------------------------------|
| 1    | Open mobile user app             |
| 2    | Sign in with correct credentials |
| 3    | Set your location                |
| 4    | Choose restaurant which is open  |
| 5    | Select two food items and add them to cart |
| 6    | Go to cart and click on "Confirm Order" |
| 7    | Choose dining option as "Take away" |
| 8    | Choose payment option: card  |
| 9    | Enter card details  |
| 10   | Confirm your order  |
| 11   | Watch order confirmation screen |
| 12   | Go to order history to verify if the order is there  |
 
---

## Expected Result

- User gets successfuly signed in 
- Location is set correctly
- Food items added to cart are visible and have correct prices
- After clicking "Confirm Order", user can choose dining option and payment method
- After placing an order, user gets a success message that his order was placed correctly
- User can see his order in the Order History page

---

## Test data
| Field | Value   |
|-------|---------|
| Sign in data | john.doe@google.com / 12345678  |
| Dining option | Take Away  |
| Payment   | test card: '4246 1111 0011 0101', 06/29, 976  |

---

## Environment

- **System** Android 15
- **Aplication** FoodApp 1.8.0
- **Network** Wi-Fi 

---

## Comments

- Scenario can be expanded to track order status on restaurant app 

---

## Test type
- E2E
- Functional test
- Smoke test (for basic user flow)  

---

## Test Status
**To Do**
