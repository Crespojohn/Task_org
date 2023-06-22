Task_org is a project I am starting that will help orginize reoccuring assignments and tasks easily. This application will be terminal based and should be low level, allowing me to add projects and tasks that are due easily. It should have a saveable log of assignments that are completed and missed, and have a to-do list that will show what is due next. 

//                               Task_org.exe                                 //

      (-T)      (-D)         (-C)          (-M)           (-A)         (-S)
  To-do List  Due Work  Completed work  Missed Work  Add assignment  Schedule
      (-U)
      Undo
//                                                                            //

Assignments.csv
"<Class Due>,<assignment name>,<date due>,<Reoccuring flag>"

To-do List-
This function should read a .csv file and check what is Done and what is not finished and then display items that are not finished that have been added

Due work- 
This function will show work that had been added and is due, only showing upcoming work due

Completed work-
This function will show all work that has been completed this quarter

Missed work-
Shows work that has not been submitted passed the due date

Add assignment-
Adds an assignment to the assignment.csv file using cmd line argument

Schedule-
Shows the work due based on the class/group, shows an orginized table of each class and their assignements

Undo-
Will Reload old Assignments.csv to undo any mistake made

