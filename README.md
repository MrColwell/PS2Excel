# PS2Excel

Current Version: TeacherCoursesV2g.exe (June 14, 2016)

Andrew Colwell (Saint John High School)

##### On the right of this screen, click the 'Clone or Download' button, and save the ZIP folder
##### Extract and save the files in the Zip folder in an easy to locate place on your computer (Desktop is good)

You must get data from PowerScheduler first.
  1. In PowerScheduler, go to: Reports, Master Schedule List (don't change options), Submit
  2. Manually select and copy all the data below the headings, and save into a simple text file. (Notepad)
  3. Double click on TeacherCoursesVxx.exe
  4. You will be prompted to open a file. Open the text file you previously saved.

The program will create an Excel spreadsheet in the same directory with the same name as the text file.
The new file will be an ".xlsx' file ready to be opened in Excel.

The courses now appear as:
Nutr Hlth Living 120(1:29)(A)  <==>  Course name(Section:Enrolled in section)(Day)

Will be added in future:
- [ ] Courses over multiple blocks (Coop only shows in first period scheduled, you should manually fill in other periods)
- [ ] Google Chrome preferred to select data, MS IE not working properly yet

Known Bugs/Conflicts/Issues:
  * You need to have Windows update: KB2999226 (Part of Zip file; you may need admin rights to run it)
  * You need to select data with Google Chrome (as of May2016) (Data in notepad should be tab separated)
  * Multiple Days in PowerScheduler are put into same block on semester 1 spreadsheet
    - yes, its sketchy, but very few schools run multiple days
    - if you run a single day, in the Excel spreadsheet, press Ctrl+H, Find: (A) and replace with nothing 

Fixed issues:
- [x] Section number added to Course 
- [x] Number enrolled in class to be added to display
- [x] Multiple Days supported (as of V2f)
- [x] Count per period to be added at bottom of spreadsheet
- [x] Count of classes per teacher on left (Co-op only counted as one course)

