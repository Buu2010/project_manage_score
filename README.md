# project_manage_score

## This project is for teachers to manage grades of students

### Before you continue, ensure you meet the following requiments:
#### * You have installed Python in computer
#### * You have a basic understanding of library Numpy and Pandas in Python

##### TASK 1 : THIS FUNCTION ALLOW USER INPUT FILE'S NAME. IF FILE EXISTED, PRINT A NOTIFICATION "SUCCESSFULLY OPENED". IF NORT REQUEST INPUT FILE'S NAME AGAIN

##### TASK2 : THIS FUNCTION ANALYSIS THE DATA OF THE FILE:
###### * PRINT THE NOTIFICATION: HOW MANY LINE DATA INVALID AND HOW MANY LINE DATA VALID

##### TASK3 THIS FUNCTION GRADE EXEM OF EACH STUDENT IN CLASS AND STATISTICAL THE HIGHEST, THE LOWSET, THE RANGE, THE MEAN, THE AVERAGE OF THE CLASS'S SCORE

##### TASK4 THIS FUNCTION CREATE A FILE CONTENT THE RESULT GRADE SCORE OF CLASS. 

# IF YOU WANT TO GRADE SCORE OF CLASS AND SAVE AS A FILE, YOU NEED:
## * CALL THE FUNCTION: Load_file() 
## * CALL THE FUNCTION Analysis_file(arg) WITH ARGUMENT IS THE RETURN OF FUNCTION Load_file()
## * CALL FUNCTION Test_work(arg1) WITH THE ARGUMENT IS THE RETURN OF FUNCTION Load_file()
## * CALL FUNCTION Save_resuL(arg!,arg2) WITH ARGUMENT ARE THE RETURN OF FUNCTIONS Load_file()  AND Test_work(arg1)
### EXAMPLE:
file=Load_file()
Analysis_file(file)
Save_result(file,Test_work(file))
file.close()
