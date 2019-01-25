This is a test task for DotNET.\r
1- Fork this repository to your own github account\r
2- Adjust connection string to a sql express database (ProjectName.mdf) in the app_data directory\r
3- All your code should be under Areas>>ProjectName\r
4- Provide a good code structure: Models | Controllers\r
5- Create the following Models: A store can have multiple products\r
\tProduct:\r
	\tProductName\r
	\tPrice\r
	\tStock\r
	\tIsActive\r
\tStore:\r
	\tAddress\r
	\tName\r
6- migrate the models to databse using Code first database migration\r
7- Create APIs for:\r
	\tList/Add/Edit/Delete Products\r
8- Create your tests for the apis using postman\r
