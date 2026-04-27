# SNHU-CS340

Portfolio artifacts for CS 340 Client/Server Development.

## Project Two Artifacts

This repository includes my Project Two dashboard notebook, CRUD Python module, and README documentation for CS 340.

## Reflection

### How do you write programs that are maintainable, readable, and adaptable?

I write maintainable, readable, and adaptable programs by keeping the code organized, using clear names, and separating different responsibilities into different files or sections. In this course, the CRUD Python module from Project One helped make the Project Two dashboard easier to manage because the database operations were kept separate from the dashboard code. Instead of placing all of the MongoDB connection logic directly inside the dashboard, the dashboard could use the CRUD module to interact with the database.

The advantage of working this way is that the code becomes easier to update and reuse. If something needs to change with the database connection or the CRUD operations, I can update the module instead of rewriting the entire dashboard. In the future, this CRUD Python module could be adapted for another database-driven application, another dashboard, or a backend tool that needs to create, read, update, or delete records from MongoDB.

### How do you approach a problem as a computer scientist?

I approach a problem as a computer scientist by first trying to understand the client’s needs and then breaking the problem into smaller technical steps. For the Grazioso Salvare project, I had to look at what the client wanted from the animal shelter data and then figure out how to turn those needs into database queries, dashboard filters, a data table, and a map. This helped me think about the project as a full system instead of only focusing on one small piece of code.

This project was different from some previous assignments because it felt more like building a tool for a real client. The database, Python module, dashboard layout, filtering options, and visual elements all had to work together. In the future, I would use the same kind of approach by reviewing the client’s goals, studying the available data, designing useful database queries, and building an interface that helps the client use the data more effectively.

### What do computer scientists do, and why does it matter?

Computer scientists solve problems by designing systems that organize, process, and present information in useful ways. This matters because companies often have large amounts of data, but that data is not very helpful unless it can be searched, filtered, and understood. In this project, the dashboard could help Grazioso Salvare identify dogs that match specific rescue-training profiles more efficiently.

A project like this could help a company save time, reduce manual searching, and make better decisions. For an organization like Grazioso Salvare, the dashboard supports their work by making animal shelter data easier to use. Instead of sorting through records manually, users can filter the data and quickly view the animals that best match their needs.

## AI Acknowledgment

I used ChatGPT to help review the assignment requirements, organize my reflection responses, and improve the clarity of my writing. I reviewed and edited the final content before adding it to my GitHub README.
