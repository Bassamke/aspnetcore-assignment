# ASP .Net Core Developer Assignment: Queue Management System

The assignment involves the creation of a Queue Management System using ASP.NET Core. Please use the following libraries/tools and the stated versions:

- ASP.NET Core 5+
- PostgreSQL 11+
- FastReport.Net
- Npgsql 6.0.0+

## Queue Management System

Create a simple Queue Management System with the following pages:

1. Check-In page. This page should allow customers to select the kind of service they're receiving and should support kiosk mode with the following in mind:
   - Use descriptive text.
   - Buttons should be large enough.
   - Ability to print tickets. Design the ticket using FastReport.Net.
2. Waiting page. This page should simply display the called customer's ticket number and the service point they should head to.
3. Service point. This page should allow the service provider to:
   - Authenticate and select their service point.
   - Get next number.
   - Recall number.
   - Mark number as no show.
   - Mark number as finished.
   - Transfer number.
   - View their queue.
4. Admin dashboard. This page should have the following:
   - Ability to configure service points.
   - Ability to configure service providers.
   - Ability to generate an analytical report, using **FastReport.Net**, displaying the following information:
     - Number of customers served.
     - Average waiting time per service point/provider.
     - Average service time per service point/provider.

## Database modelling

- Use PostgreSQL as the database of choice.
- Ensure that the database tables are properly mapped to your project's POCO models.
- **DO NOT** use existing ORMs i.e. Entity Framework for modelling. Instead, write your own CRUD methods.

## How to work on the assignment

- Clone this repository.
- Start working on the assignment.
- Ensure to do periodic commits with meaningful commit messages.
- Once you are done, push your final results.
- If you don't want to create a public repository please invite (@hanmaktechltd) to your working repository.
- Please include a brief description of how to run your solution and also include a copy of the database schema.
- If you have any questions contact us (<hr@hanmak.co.ke>)
