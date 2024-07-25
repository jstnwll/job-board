# Computer Programming I <br> Group Project: Local Jobs Board
Justin WIllemsen<br>
Danielle Purpura<br>
Summer 2024


# About
  This program is a jobs board designed for both employers seeking employees and job seekers in need of employment. Existing job search platforms, such as Indeed and LinkedIn, often present an overwhelming number of results while searching, many of which are spammy or not in the desired location, even after filtering. This program addresses this issue by focusing on smaller communities and regions. This version is structured around Alaska. 


# Main Menu
![image](https://github.com/user-attachments/assets/14289d7e-6101-4503-9b74-f29adae0afd5)

The program opens with the main menu, providing two primary options. Go to the employer menu or the job seeker menu.


# Employer Menu
![image](https://github.com/user-attachments/assets/135535c2-0b08-4f32-aec4-cc80002c9988)

Employers have two options. Post a new position or remove an existing job after it has been filled. 


# Add New Position
![image](https://github.com/user-attachments/assets/95ed808e-1a64-444e-994c-13faa98d0c0f)

Positions consist of:<br>

Title<br>
Company<br>
Location<br>
Salary<br>
Education Requirements<br>
Experience Level<br>
Job Description<br><br>

These values are stored in a vector, using a struct.


# Remove Position
![image](https://github.com/user-attachments/assets/af5c750c-4080-409a-8ef3-3959e48e3504)

A job ID is automatically generated after entry. This ID is used when listing and selecting positions for removal. 


# Job Seeker Menu
![image](https://github.com/user-attachments/assets/9e951ed7-5e69-4964-9aa9-ecdec50e4599)

Job seekers can view all available jobs or filter by each category, except for job description.


# View Jobs
![image](https://github.com/user-attachments/assets/b5a2460d-5f65-4849-a7ce-7fbe9d5ef785)

Jobs display all available information in ID order.
