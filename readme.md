# Specifications 

### Registration form 
- name
- email
- mobile 
- password
- gender

### Login form 
- email
- password 


### Activation form
- code

### Welcome page 
- welcome user and display user details 


1. After user got registered, his/her data got stored in DB.
2. User can't log in until he/she activates his/her account.
3. Send activation code via (email & sms). (*)
4. after user got activated, send welcome sms & welcome email (with pdf attachment has user details)

(*)
###### Email contains  
- url user can click to activate account
- activation code (text)
- QA code has activation code
###### SMS contains  
 - Activation code


## Requirements:
0. Please create development branch and work on it.  
1. Create html pages as mentioned above. 
2. Dockerize your application. 
3. Data needs to be stored in Mysql. 
4. You can use any libraries.
5. Good luck ;)
