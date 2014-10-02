#2. User Requirements Definition

##2.1. User groups definitions

| User group | Brief definition | Definition |
|--------|--------|---------|
| Administrator | Manager of the entire system | The administrator is the most powerful user in the system. The user can manage all users in the CampusSeek's network, performing check up and imposing ban on abusing users. Administrator can access all user's information except for personal login credentials |
| Student or Registered User | Student on the campus or anyone who want to register into the campus network | The student account provide basic access to system features, such as tracking friends, adding friends, setting status, editing personal profile, requesting help |
| Staff | Staff on the campus (include teacher)| The staff account basically carry over all student's account functionalities, plus the capability to obtain all student location and status (if the user is not hiding it) without having to add them as friend |
| Guest | People who are not part of the campus | The guest account is provided with very basic features, the user can only track his/her own location and navigate around the campus without being able to track anyone else |


##2.2. Use cases and primary actors

| Primary Actor                | Use Cases           |
| ---------------------------- | ------------------- |
| Administrator                | Add user            |
|                              | Delete user         |
|                              | Edit user           |
|                              | Ban user            |
|                              | Log in              |
|                              | Log out             |
|                              | Edit profile        |
|                              | See profile         |
|                              | Set status          |
|                              | See friend list     |
|                              | Search for people   |
|                              | **Add friend**      |
|                              | Track any           |
|                              | Navigate on map     |
|                              | Emergency           |
|                              | Change language     |
|                              |                     |
| Student or Registered User   | Log in              |
|                              | Log out             |
|                              | Edit profile        |
|                              | See profile         |
|                              | Set status          |
|                              | See friend list     |
|                              | Search for people   |
|                              | **Add friend**      |
|                              | **Track friend**    |
|                              | Navigate on map     |
|                              | Emergency           |
|                              | Change language     |
|                              |                     |
| Staff                        | Log in              |
|                              | Log out             |
|                              | Edit profile        |
|                              | See profile         |
|                              | Set status          |
|                              | See friend list     |
|                              | Search for people   |
|                              | **Add friend**      |
|                              | Track any           |
|                              | Navigate on map     |
|                              | Emergency           |
|                              | Change language     |
|                              |                     |
| Guest                        | Navigate on map     |
|                              | Change language     |

*For this assignment, only the bolded use cases have been written

##2.3. Use Case Diagram

![alt text](https://raw.githubusercontent.com/peace183/software_engineering_2014_template/master/final_project.png "Use Case Diagram")

##2.4. Main use cases

|                   |                                                                                                          |
| ----------------- | -------------------------------------------------------------------------------------------------------- |
| **Use case name** | Add friend                                                                                               |
| **Actors**        | Administrator, Student, Staff                                                                            |
| **Description**   | Administrator, Student and Staff can add new friend into their friend list                               |
| **Initial state** | 1. Users have signed up                                                                                  |
|                   | 2. Users have verified account                                                                           |
|                   | 3. Users log in                                                                                          |
|                   | 4. Users accessed the Friend List Page                                                                   |
| **Normal Flow**   | 1. Users search for new friend (by email, account name, Facebook account ...)                            |
|                   | 2. System will show the target                                                                           |
|                   | 3. Users click on target to view basic info                                                              |
|                   | 4. Users choose to add friend by sending request                                                         |
|                   | 5. System will inform that request is sent                                                               |
|                   | 6. System will inform users when request is confirmed                                                    |
| **End state**     | New friend is added to user's friend list                                                                |
| **Exception**     | 1. Friend can not be found                                                                               |
|                   | 2. System will inform that friend can not be found                                                       |
|                   | 3. System will ask user to input again friend's information for searching                                |
|                   | 4. System suggest friend that has the similar account name                                               |


|                   |                                                                                                                 |
| ----------------- | --------------------------------------------------------------------------------------------------------------- |
| **Use case name** | Track friend                                                                                                    |
| **Actors**        | Administrator, Student, Staff                                                                                   |
| **Description**   | Administrator, Student and Staff can track their friend's location inside the campus and will be guided there   |
| **Initial state** | 1. Users logged in                                                                                              |
|                   | 2. Users accessed friend list                                                                                   |
|                   | 3. Users choose friend to track                                                                                 |
| **Normal Flow**   | 1. Users choose friend in friend's list to track                                                                |
|                   | 2. System will show targeted friend basic info and his/her location in real-time                                |
|                   | 3. Users choose to be navigated there                                                                           |
|                   | 4. System will show the real-time navigation map to instruct users to their destination                         |
|                   | 5. System will inform users when reaching destination                                                           |
| **End state**     | Friend's location is informed and system navigate users to destination.                                         |
| **Exception**     | 1. Friend can not be found                                                                                      |
|                   | 2. System will inform that friend can not be found                                                              |
|                   | 3. System will ask user to input again friend's information for searching                                       |
|                   | 4. System suggest friend that has the similar account name                                                      |

