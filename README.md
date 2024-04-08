# Data_management_system
Simple data management system using ruby

We have to manage hierarchy data. Here is the hierarchy : 
1. Account - {id, name} - Can be multiple Accounts
2. Network - {id, name, account_id} - Belongs to an Account.
3. School - {id, name, network_id} - Belongs to Network
4. UserType - {id, name} - Same UserType can exist in multiple schools
5. Users - {id, email, usertype} - User will have UserType & Belongs to a single School.

We stored information in a file. On Restarting the server, it has to have already saved info.

Also added CRUD operation for all of the entities.

Ruby version - 2.7.2
