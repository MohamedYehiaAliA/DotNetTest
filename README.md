This is a test task for DotNET.
1- For this repository to your own github account
2- Adjust connection string to a sql express database (ProjectName.mdf) in the app_data directory
3- All your code should be under Areas>>ProjectName
4- Provide a good code structure: Models | Controllers
5- Create the following Models: A store can have multiple products
	Product:
		ProductName
		Price
		Stock
		IsActive
	Store:
		Address
		Name
6- migrate the models to databse using Code first database migration
7- Create APIs for:
	List/Add/Edit/Delete Products
8- Create your tests for the apis using postman
