﻿﻿Trend IOTA - Product Catalog Web Application
Group: IOTA
Course: CYB206-25W-001 - Web Application Security (Winter 2025 - 001)
Project Submission Date: February 19, 2025

20250219
1000

Project Created, Prototype defined.

1025

Asp.NET project started

Product Details - Trend IOTA Bags

Project Overview
This project is a web application built using ASP.NET Core 8.0 that showcases a product catalog for our fictional brand, Trend IOTA. Trend IOTA specializes in high-quality ladies' bags, offering a collection of five different models with detailed attributes.
The application implements CRUD (Create, Read, Update, Delete) operations, enabling users to manage product information efficiently. Additionally, it features authentication with individual user accounts, ensuring secure access to product management functionalities.
The project is hosted on GitHub and follows best practices in MVC (Model-View-Controller) architecture.

Product Details - Trend IOTA Bags
Our product catalog features the following five models of Trend IOTA bags:
1. IOTA Elegance Tote
	ID: 001
	Price: $120
	Material: Genuine Leather
	Color Options: Black, Brown, Navy
	Dimensions: 14" x 10" x 6"
2. IOTA Chic Crossbody
	ID: 002
	Price: $85
	Material: Vegan Leather
	Color Options: Red, Beige, Grey
	Dimensions: 10" x 8" x 3"
3. IOTA Urban Backpack
	ID: 003
	Price: $150
	Material: Water-resistant Nylon
	Color Options: Black, Olive Green, Burgundy
	Dimensions: 16" x 12" x 5"
4. IOTA Luxe Handbag
	ID: 004
	Price: $200
	Material: Italian Suede
	Color Options: Navy, Mustard Yellow, Emerald Green
	Dimensions: 12" x 9" x 4"
5. IOTA Everyday Satchel
	ID: 005
	Price: $110
	Material: Premium Canvas
	Color Options: White, Black, Denim Blue
	Dimensions: 13" x 9.5" x 5"

	Features of the Application
	1. Authentication & Security

1040
	Secure individual user accounts using ASP.NET Identity.
	HTTPS configuration for encrypted connections.
1100
	Testing: Encountered an issue with user authentication failing due to incorrect database migrations (Time: 10:45). 	Fixed by applying dotnet ef migrations add InitialCreate followed by dotnet ef database update.
	2. Product Catalog (CRUD Operations)
1130
	Users can Create, Read, Update, and Delete bag models.
	Displays detailed product information including price, material, colors, and dimensions.
1200
	Testing: Initial data retrieval failed due to an incorrect model binding 
1230
	Resolved by correcting the entity relationships in the database context.
	3. Navigation & Pages
1300
	Home Page: Features the fictional company Trend IOTA.
	Product Catalog Page: Displays all bag models with their attributes.
	About Us Page: Provides company details, location, and team members.
1345
	Testing: Navigation links were not functioning correctly (Time: 13:45). Fixed by updating the 	app.UseRouting() configuration in Startup.cs.
	4. Database Implementation
1430
	Uses Entity Framework Core for managing the product database.
	Stores user authentication and product data securely.
1500
	Testing: Database seeding caused duplicate entries. Fixed by checking for existing records before 	inserting new ones .

	Repository & Documentation
	External README.md: Includes project details and product catalog.
	Internal README.txt: Contains logs and timestamps of development progress.
	Additional Documentation: Flowcharts and comments are included in the code.

	Contributors
	Team IOTA Members: Ishika Narendrabhai Prajapati, Deepak Deepak, Kenan Karateke

	GitHub repository: 

Ishika Prajapati DEV
2025-03-05

20:30
- Initialized the development repository (TrendIOTA-DEV).
21:00
- Cloned the repository locally and configured the environment.
21:30
- Set up ASP.NET Core 8.0 project structure.
22:00
- Configured initial project dependencies and database setup.
22:30
- Implemented authentication using ASP.NET Identity.

2025-03-06

09:00
- Started working on CRUD operations for product catalog.
10:30
- Implemented Create and Read functionalities.
12:00
- Completed Update and Delete functionalities.
14:00
- Debugged and fixed issues related to database migrations.
16:00
- Conducted initial testing of authentication and CRUD operations.
18:30
- Finalized database structure and entity relationships.

2025-03-07

09:00 
- Performed final testing and fixed UI navigation issues.
11:00
- Updated README file with development details.
14:00
- Prepared for repository submission.
16:30
- Pushed final changes to GitHub and confirmed deployment readiness.

Kenan Karateke TEST
2025-03-06-14-50-00

Verified all functionalities; system stable, no errors.

2025-03-06-15-20-00

Added images to the project directory for product pages and branding.

2025-03-06-15-50-00

Worked with TESTER to create and integrate the SeedData file.

2025-03-06-16-30-00

Seeded the database with initial records (users, roles, product details).

2025-03-06-16-45-00

Started developing the About Us page.

2025-03-06-17-00-00

Integrated MVC components (controllers, views, models).

2025-03-06-17-30-00

Completed content writing for the About Us page.

2025-03-06-17-45-00

Replaced navbar text title with a logo for branding.

2025-03-06-18-12-00

Added the TrendIota logo to the About Us page.

2025-03-06-18-30-00

Finalized README.md with setup and development guidelines.

2025-03-06-18-50-00

Updated README.txt with additional setup details.

2025-03-06-19-30-00

Fixed minor typos in documentation.

2025-03-06-23-40-00

Merged latest updates from Dev to Main branch.

2025-03-06-23-52-00

Cleaned, built, and ran the project successfully.

2025-03-07-09-50-00

Cleaned and built TrendIota project (Debug Any CPU); build successful.

2025-03-07 09-59-00

Launched and tested application post-build.

2025-03-07-00-51-00

Implemented role-based access control (RBAC) in Program.cs.

2025-03-07- 13-15-00

Tested RBAC implementation; authentication/authorization working.

2025-03-07-13-32-00

Updated Purse Controller for RBAC permissions.

2025-03-07-13-47-00

Verified RBAC functionality in Purse Controller.

2025-03-07-14-21-00

Restricted Create, Edit, Delete options for users in Purse Directory Index View.

2025-03-07-14-38-00

Tested role-based UI restrictions; changes successfully applied.

2025-03-07-14-54-00

Full functionality test completed; no major issues detected.

2025-03-07-02-57-00

Configured user credentials and roles:

Admin: Full access.

Standard Users: Limited permissions.

Guest (Read-Only): View-only access.

 Admin User
 Username:kenan@trendIota.ca
 Password:Admin@1234

 Guest Users
 Username: Ishika@trendIota.ca
 Password: User@1234

 Username: Test@trendIota.ca
 Password: User@5678