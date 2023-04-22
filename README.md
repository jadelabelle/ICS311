# ICS311

Instructions to run the code:

1. Make sure that Python and the mysql.connector package are installed on your computer.
2. Set up a MySQL database and create the tables and insert statements provided in the code. Replace "PASSWORD" in the code with your database password.
3. Copy the code and paste it into a text editor of your choice.
4. Replace "PASSWORD" in the code with your database password.
5. Save the file with a ".py" extension.
6. Open your command prompt or terminal and navigate to the directory where the file is saved.
7. Type "python filename.py" (replace "filename" with the name of your file) and press enter to run the code.
8. Follow the prompts in Report 3 to input a destination ID and view the data.
9. Explanation of how the reports work:

Report 1: This report selects data from the Trailer and Dest tables and prints it in a formatted table. It shows the Trailer ID, Trailer Size, Utilization, and Destination Name for each trailer in the database.

Report 2: This report selects data from the Package, Trailer, and Dest tables and prints it in a formatted table. It shows the Package ID, Package Weight, Trailer Size, and Destination Name for each package in the database.

Report 3: This report prompts the user to input a destination ID and selects data from the Dest and Trailer tables where the given destination ID matches. It then prints the data in a formatted table. It shows the Destination Name, Trailer ID, Trailer Size, and Utilization for each trailer that is going to the specified destination. If no data is found for the given destination ID, it displays a message indicating that no data was found.
