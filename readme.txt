						READ ME
Group Members:

1) Robin Jha
2) Tarif Riyad Rahman
3) Jacqueline Lane


Browser Used: Mozilla Firefox

How to run ?
i)To run the webpage type navbar_ver1.py (Home Page)
ii)Once the webpage appears you can start the navigation. There are different buttons such as “NEW RELEASES”, “MOST POPULAR”, etc. You can click on each of these buttons to navigate through the website
iii)You can also click on the “LOG-IN” button to log in. Once you click on the “LOG-IN” button, it brings the login page which says “Janet's Video Store—Login Page”. The login page consists of two slide panels which has two links. One of the link is for the existing user and the other is for creating new users. Clicking on these panel buttons will open/close the panels.
iv)Once you login there will be a prompt message saying that you have logged in as a customer or employee depending on your status and you will be redirected to the appropriate page. To test it we used two dummy accounts, both for the customer and the employee. The credentials are as follows:

   		Customer
		Username:b.hope
		Password:1

		Employee
		Username:tariftalks@gmail.com
		Password:1


v) The employee interface have a different layout than the customer interface. It also provides for functionality such as inserting new movie in the database, creating new employee etc.
vi) Bonus number 2 and 3 have been implemented. 
vii) The code has not been tested on any Berry Patch machines as it was not possible to configure Apache on any of the lab machines. 
viii) The configuration file for apache has been attached as well with the assignment to make setup easier
ix) The database file is assign3.sql which was the result of a dump operation of MySQL
x)The cust_id attribute of the creditcard and customer table is basically the unique account number of the customer.
xi) It should also be noted that all the id are generated using autonumber so even if a row is deleted the autonumber will not decrease by 1 therefore use the query 'ALTER TABLE theTableInQuestion AUTO_INCREMENT=<value>' to reset it back to its original state
