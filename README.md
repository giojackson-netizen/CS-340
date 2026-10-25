# CS 340 Portfolio Reflection
**Giovanni Jackson**

## Writing Maintainable, Readable, and Adaptable Programs

I write programs by breaking the work into smaller parts, using clear names, and adding comments that explain what the code is doing. In Project One, I worked on a CRUD Python module that handled the database operations. In Project Two, I reused that module to connect the dashboard to MongoDB. Having the database operations in a separate module made it easier to troubleshoot because I could check the connection and queries separately from the dashboard layout and buttons.

The advantage of this approach is that I can update one part without having to rewrite the entire program. I could also reuse the structure of this module for another project by changing the database, collection, and validation rules. This connects to something I have been playing around with: making my own biomed tracker. A similar module could help manage equipment records, repair history, and parts information. Working in a hospital has shown me how important it is to keep that information organized and easy to find.

## Approaching Problems as a Computer Scientist

I approach a problem by figuring out what the user needs and then breaking it down into steps I can build and test. For Grazioso Salvare, I needed to connect to the animal database, filter animals based on rescue requirements, display the results in a table, and show information through a chart and map. I worked through those pieces individually so I could identify where something was going wrong. When I had trouble with authentication and displaying the dashboard, I had to check the connection settings and how the application was running.

Compared with assignments focused on one function or algorithm, this project required me to connect several components into one application for a specific client. It reminded me of troubleshooting hospital equipment because an issue can come from different parts of a system. I have to narrow down the cause instead of changing everything at once. For future database projects, I would start by asking the client what information they need, how they plan to search for it, and what tasks take the most time. Then I would plan the data structure, test queries with sample records, and check that the results match the client’s requirements.

## The Purpose and Impact of Computer Science

Computer scientists solve problems by building systems that help people use information and complete tasks more effectively. The work matters because a program needs to be useful to the person relying on it. For Grazioso Salvare, the dashboard helps users narrow down animal records based on rescue criteria instead of manually searching through the entire database. The table, chart, and map make the information easier to review and help users identify animals for further evaluation.

I see a similar need in my hospital experience. Being able to quickly find equipment information, repair history, or needed parts can help technicians spend less time searching and more time addressing the issue. That is part of what interests me about building my own biomed tracker. This project helped me understand how a database and an interface can work together to support a real workflow, and it gave me an approach I can continue developing for future projects.
