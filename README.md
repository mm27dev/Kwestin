### About Kwestin
A simple yet effective question database for students and teachers. Best used in online classes, where an overflow of questions can disrupt class quality and learning. Please note that Kwestin is in beta. Expect and report bugs to mm27dev. 

### Setup (READ) (For teachers only)
Setup process is relatively easy. To setup, create a new folder in your google drive that is viewable by all. Name it SharedDatabase. Next, inside the the folder create 2 blank notepad txt files, one called "PswdDatabase.txt" and another one called "QuestionDatabase.txt". Thats it! All you have to do is send the drive link to the students and open the colab from the ipynb file, which should also be sent to students. Students should run the first block of code to ask a question and the teacher will check the "questions.txt" file in the folder and compile responses to the questions which can ne clarified later

### Questions Deletions (For Teachers only)
If you need to delete all questions and restart with a clean slate, run the block of code underneath the comment that says " For teachers vvv". If this is your first time performing a deletion, you will be prompted to create a password for your security. Create it and rerun the block of code to delete the questions. Please note that deleted questions can not be recovered ( you will be prompted with a confirmation check before deletion). 
