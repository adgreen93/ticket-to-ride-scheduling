== README

![trst](public/ticketlogo.png)

This project is a web app for companies and employers to track attendance and pay for their employees. The finished product will enable users(Employees), to log in, input their hours for the week, and save them. Employers (Admins) are able to view the hours of all employees, as well as their Status(Full Time, Part Time, Per Diem, Contract Work), and their Salary. 

User auth is made with Devise, and there are three main models - Employees, Employers (Admins), Company(which owns both), and the Schedule model that users update.

You can create a new Company, or seed the database with the companies already in place. Upon creating new users/admins, you can add them to the Company. 

This project was inspired off of Kronos, the workplace management app, as well as the work study scheduling tool used by my school. I wanted to make something a little more modern and effective - so here it is!

![trst](public/ticket1.png)
![trst](public/ticket2.png)
![trst](public/ticket3.png)
