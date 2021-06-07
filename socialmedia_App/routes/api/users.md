<!-- user signin -->
### first require the defencies 
    bcrypt,
    user model,
    Avatar,
    jwt,
    config,
    check, validationResult

### user validation

* enter the name,valid email and passward
* check if validation result is not true then it throw an validation error.

### New user
* find the user by email 
* if you is user is already exit then it will throw error.
* if user is not exit then user will signin.

### bcrypt.genSalt
by using the bcrypt.gensalt is generated salt for my passward which need to encypted 

### bcrypt.hash
hash is function will be genrate security passward followoing hash algorithum/.

### Token 

after user signin, getting the Token passing the the payload and jwtsecrete.

### server error 
if something went wrong in try condition then it will throw error 