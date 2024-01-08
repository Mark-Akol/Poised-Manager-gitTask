### Poised-Manager-gitTask
#### With regards to : Compulsory Task I (Instructions)
#### Objective: Design and implement a database named PoisePMS to manage project information, assuming:

One project per structural engineer, project manager, architect, and customer.
Deliverables:

1. Entity-Relationship Diagram (ERD): Visually depict the relationships between tables.
2. Dependency Diagrams: Specify data dependencies within each table.
3. Database Creation Script: Show the code used to create the tables in your chosen platform.
4. Sample Data Insertion: Showcase the addition of at least two rows for each table with screenshots or code snippets.

### Challenge:

#### Design and implement the PoisePMS database, fulfilling the listed requirements with clear and comprehensive documentation. Demonstrate data insertion for each table within your chosen database platform.

#### With regards to : Compulsory Task II (Instructions)

#### To enhance the Capstone Project, embark on the following steps:

Copy and paste the code that you wrote for the last Capstone Project in the previous level of this Bootcamp 
into the Dropbox folder for this Capstone Project.

Modify your code so that it:

	- Reads and writes data about projects and people associated with projects from your database instead of 
	  text files. Your program should not use any text files.
	- Capture information about new projects and add these to the database.
	- Update information about existing projects.
	- Finalise existing projects. When a project is finalised the following should happen:

		* An invoice should be generated for the client. This invoice should contain the customer’s 
		  contact details and the total amount that the customer must still pay. This amount is calculated 
		  by subtracting the total amount paid to date from the total fee for the project. If the customer 
		  has already paid the full fee, an invoice should not be generated.
		* The project should be marked as “finalised” and the completion date should be added.
		
	- Finds all projects that still need to be completed from the database.
	- Finds all projects that are past the due date from the database.
	- Find and select a project by entering either the project number or project name.
	
Besides meeting the above criteria, you should also do the following:

	- Include exception handling. Use try-catch blocks wherever appropriate.
	- Remove all errors from your code. Take extra care to detect and remove all logical and runtime errors.
	- Adequately refactor your code.
	- Document your code. Adhere to the style guide found here.
	- Use Javadoc to generate API documentation from documentation comment for your program. 
	- Follow the guidelines here to create a Readme file for this project.
