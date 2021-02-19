# SQL-Query-Creator
Python GUI based SQL query creator for importing vehicles into SQL database in FiveM. 

# Usage
In terminal run pyinstaller.exe --onefile --windowed main.py

Once open:
- Select a vehicle from the dropdown menu, if the desired vehicle does not exist, input the model hash into the text field
- Input license plate into the text field
- Input the users license into the text field
   Optional
   - Check turbo box if desired
   - Change primary, secondary and pearl colours (leave for standard black)
- Press submit button
- Run SQL Query in database and refresh owned_vehicles table
 
# Future Changes
- Change vehicle allocation and retrieval of model to use dictionary and for loops
