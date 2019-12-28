# User service

## Features: 
- Add alias Register
- Remove
- Edit
- Profile pic   

## /user method POST
- name: string
- college: string
- Branch : string
- Gender: male/female ( Dropdown )
- DOB: Calender and time picker
- phone: string with phone validation
- email: string with email validation
- current addr: string max-length
- permanent addr: string max-length with radio button to choose current as permanent addr
- profile pic: file type
- Return id: string   

## /user method: PUT
- (PUT for edit)
- body- {field: newValue}
- {field1: value1, field2: newVal2}
- Return true boolean    
 
## /user method: DELETE
- request: params id


## View routes:
- /users - list of all users
- /user/register - registration form
