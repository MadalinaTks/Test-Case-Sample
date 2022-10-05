Bellow are some Test Case Sampels that I wrote while working on previous learning projects

------------------------------------
# Test Case Sample 1

**Title**
User uses incorrect credentials

**Description**
Check if the login works when user uses incorrect credentials

**Steps to follow**

1. Go to www.emag.ro/login 
2. Add an incorrect user name&pass 
3. Press Login button

**Expected result**
User is not able to log in and an error is displayed


-------------------------------

# Test Case Sample 2

**Title**
Login should not work without credentials

**Description**
Check if the login works without credentials

**Steps to follow**

1. Go to www.emag.ro/login 
2. Don’t add any user name&pass
3. Click Login button

**Expected results**
1. User is not loged in
2. Error message is displayed : "Please use credentials to log in"

----------------------------------------------
# Test Case Sample 3

**Title**
Remember Me checkbox is working with correct credentials

**Description**
Check if Remember Me works when user uses correct credentials

**Steps to follow**

1. Go to www.emag.ro/login  
2. Add  user name&pass 
3. Click Remember Me checkbox
4. Click Login button 
5. Click log out 
6. Go to Log in page 
7. Observe if credentials automaticaly appear without typing it in the fields

**Expected results**
1. User is logged in
2. User is logged out
3. Credentials are displayed


**Test Data**
User: test
/ Pass: test123

-----------------------------------------------------


