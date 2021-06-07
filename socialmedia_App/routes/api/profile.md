### first require the defencies 
    user model,
    profile model,
    request,
    auth middleware,
    config,
    check, validationResult

<!-- get the current profile  -->

### router.get/me

* hit get the api passing the token
* get the profile following the Profile.findOne({ user: req.user.id }).populate('user', ['name', 'avatar']);

* if profile is there then it will display the in json form.
* if profile is not there then it will throw the error {"there is no profile"}

<!-- create the profile  -->
### router.post/

### validation 
* check validation result passing the the status and skills.
* if valudation is true then will create the profile object. 

### passing the require information.
<!-- * intialsing the  -->
* const {company website,location,status,skills,bio,githubusername,youtube,facebook,instagram  linkedin,twitter, }
* store the all information in onject and update the object.
* after update the object have to insert the object in dbs.
* 
* if there is no user profile, it will thorow the error.



<!-- get the all profile -->

### router.get/

* get the all profoiles by Profile.find() and populate the user avatar

### router.get/user_id 

* Display the profile by passing the user id in params.
    <!-- Profile.params.user_id -->
* if profile is not there then display the error using the ( err.kind === Object )
"there is no profile"









