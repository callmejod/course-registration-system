# C++ Course Registration System Using Topological Sort
This is a course registration system written completely in c++. The main algorithm used in the project is the Topological Sorting in order to traverse the graph that consists of the courses. The Topological Sort algorithm ensures that no course will be registered without its prerequisites.

The program reads all of the courses in the study plan from a text file called "courses_data.txt" and then calls the Topological Sort algorithm. After that, the program takes an input to perform one of the functionalities mentioned below

## Functionalities available in the system:
- Creating Users
- Signing In
- Registering Courses
- Removing Users
- Showing the entire plan that contains all the courses sorted in order (meaning that the prerequisites of each course comes before the course itself).
