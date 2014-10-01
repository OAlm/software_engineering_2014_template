### This will be the third chapter, describing Use cases

#User Group
* Teacher
* Student
* University staff -Coordinators


# Use cases and primary actors 

### Student
 1. Sign up
 2. Log in
 3. Edit profile
 4. Set status
 5. See friend list
 6. Search friend
 7. **Add friend**
 8. Check friend location
 9. **Track friend**

### Teachers

### University Staff - Coordinators


#Use case Diagram


# Main use cases 

|               |                                                                                                      |
|---------------|------------------------------------------------------------------------------------------------------|
| Use case name | Add friend            
| Actors        | Student, Teacher                                                                                     |
| Description   | Student and Teacher can  add new friend into their friend list.                                      |
| Initial state | 1. Users have signed up. 2. Users have verified account . 3. Users log in. 4. Users accessed the Friend List Page.                                                                                                      |
| Normal Flow   | 1. Users search for new friend (by email, account name, facebook account ...). 2. System will show the target. 3. Users click on target to view basic info. 4. Users choose to add friend by sending request. 5. System will inform that request is sent. 6. system will inform users when request is confirmed.                                    |
| End state     | New friend is added to user's friend list                                                            |
| Exception     | 1. Friend can not be found  1. System will inform that friend can not be found  2. System will ask user to input again friend's information for searching  3. System suggest friend that has the similar account name     |


|               |                                                                                                      |
|---------------|------------------------------------------------------------------------------------------------------|
| Use case name | Track friend          
| Actors        | Student, Teacher                                                                                     |
| Description   | Student and Teacher can know friend's location inside the campus and will routed there.              |
| Initial state | 1. Users logged in. 2. Users accessed friend list. 3. Users choose friend to track.                  |
| Normal Flow   | 1. Users choose friend in friend's list to track. 2. System will show targeted friend basic info and his/her location in real-time . 3. Users choose to be navigated there. 5. System will show the real-time navigation map to instruct users to their destination. 6. system will inform users when reaching destination.                         | | End state     | Friend's location is infomred and system navigate users to destination.                              |
| Exception     | 1. Friend can not be found  1. System will inform that friend can not be found  2. System will ask user to input again friend's information for searching  3. System suggest friend that has the similar account name     |


 






* Main use cases described more in detail, based on a template
  * a template: initial state, normal flow, end state
  * a template also tells how a use case can fail
  * in addition, you can describe alternative flows of the case
* Choose one of the use case templates and describe it as a flow chart
