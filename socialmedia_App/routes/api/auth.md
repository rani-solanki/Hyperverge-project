<!-- user authrigation  -->
### first require the defencies 
    auth middleware
    bcrypt,
    user model,
    jwt,
    config,
    check, validationResult

### authriogation 
<!-- router.get -->

* passing the token in headers for checking the token is valid or not.
* if token is not in headers will throw the error token is available. 
* if yoken is valid, it will give user information User.findById id from the dbs.
* if it is not valid then it will throw the error user  <!-- msg: 'Token is invalid'  -->


<!-- user login  -->

### user validation 
* check the validation result passing by email and passward.
* if not valid will throw the validation error.

### User 
* find the user by Email {User.findById({email})}
* if the user is not there then will thorow the error { msg: "Invalid Credentials"}

### bcrypt.compare
* Next will compare the passward. 
### Token 
* if it is matching then it will. 
* after user signin, getting the Token passing the the payload and jwtsecrete.
* otherwise it will throw the sever error.











