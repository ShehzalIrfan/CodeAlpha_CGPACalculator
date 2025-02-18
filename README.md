# CodeAlpha_CGPACalculator
The CGPA Calculator is a C++ program that computes a student's Cumulative Grade Point Average (CGPA) based on their course grades and credit hours. It allows users to input multiple courses, assign grades, and specify credit hours. The program then calculates the total grade points, total credits, and displays the final CGPA along with detailed course information.
Features: Accepts user input for multiple courses. Validates grade and credit hour inputs. Calculates total credits and total grade points. Computes and displays CGPA. Shows a formatted table of course details. Uses colored console output for better readability (Windows only)
How to Use? Compile and run the program using a C++ compiler (e.g., g++ on MinGW for Windows). Enter the number of courses. For each course: Enter the course name. Provide the grade (A+, A, A-, B+, B, B-, C+, C, C-, D+, D, F). Enter the credit hours (1-5). 
The program will calculate and display: Individual course details. Total credit hours. Total grade points. Final CGPA
Compilation & Execution: To compile the program using g++: g++ cgpa_calculator.cpp -o cgpa_calculator.exe Run the executable:./cgpa_calculator.exe
Limitations: Currently supports only Windows due to console color settings. Grades and credit hours are manually input, with no file-based input/output. No support for additional grading scales.
