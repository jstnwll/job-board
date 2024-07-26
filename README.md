# Computer Programming I <br> Group Project: Local Jobs Board
Justin Willemsen<br>
Danielle Purpura<br>
Summer 2024


# About
This program is a C++ in-terminal jobs board designed for both employers seeking employees and job seekers in need of employment. Existing job search platforms, such as Indeed and LinkedIn, often present an overwhelming number of results while searching, many of which are spammy or not in the desired location, even after filtering. This program addresses this issue by focusing on smaller communities and regions. This version is structured around Alaska. 


# Main Menu
![image](https://github.com/user-attachments/assets/b0fcb080-cfaa-4b4f-9399-e6abe2ccb10b)

The program opens with the main menu, providing two primary options. Go to the employer menu or the job seeker menu.


# Employer Menu
![image](https://github.com/user-attachments/assets/5e829371-a720-4ff6-a761-aea92f3a7191)

Employers have two options. Post a new position or remove an existing job after it has been filled. 


# Add New Position
![image](https://github.com/user-attachments/assets/b985f46a-8f7a-48b6-bc45-e5c75d069eb3)

Positions consist of: Title, Company, Location, Salary, Education Requirements, Experience Level, Job Description. These values are stored in a vector, using a struct, and simultaneously stored in an external file, “jobs.txt”.


# Remove Position
![image](https://github.com/user-attachments/assets/c3961ea6-ae87-4f42-8589-cd8106fb31c2)

A job ID is automatically generated after entry. This ID is used when listing and selecting positions for removal. 


# Job Seeker Menu
![image](https://github.com/user-attachments/assets/ce8502b3-ce65-438c-9403-00f4dbc0939d)

Job seekers can view all available jobs or filter by each category, except for job description.


# View Jobs
![image](https://github.com/user-attachments/assets/a5341555-a9c2-4489-b83c-5960d6b4244d)

Jobs display in ID order.
