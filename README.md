---
1. Create an external repository called JSON.
```
In GitHub I click on the New button on the right --> in the Repository name I prescribe JSON -->
leave the repository public --> check the box next to Add a README file
(so that the repository is not empty). I click on the button below Create repository
```
2. Clone the JSON repository to the local machine.
```bash
git clone <repository link> click on the required repository
on the right of the Code button and copy HTTPS)
```
3. Inside the local JSON, create a “new.json” file.
```bash
touch new.json
```
4. Add file under git.
```bash
git add new.json
```
5. Commit the file.
```bash
git commit -m "add new.json file"
```
6. Push the file to an external GitHub repository
```bash
git push
```
7. Edit the content of the “new.json” file - write information about yourself (name, age, number of pets,
 future desired salary). Everything is written in JSON format.
```bash
vim new.json # (edit mode (I) - write
```
```json
{
	"name": "VASILII",
	"lastName": "TIKHONOV",
	"age": 29,
	"pets": "none",
	"future salary": "2500$"

 
}	
 
```
To exit and save:
```bash
ESC
:wq
```
8. Push changes to an external repository.
```bash
git commit -am "change json" && git push
```
9. Create preferences.json file
```bash
touch preferences.json
```
10. Add information about your preferences to the preferences.json file (Favorite movie, favorite series, favorite food, favorite season,
 country you would like to visit) in JSON format.
```
vim preferences.json #(edit mode (i) - write
```
```json
{
    "Film" : "Who I am?",
    "TV series" : "Fear Factor",
    "Food" : "dumplings",
    "Season" : "summer",
    "Country" : "USA"
}
```
To exit and save:
```bash
ESC
:wq
```
11. Create a file sklls.json add information about the skills that will be studied on the course in JSON format
```bash
touch skills.json
vim skills.json # (editing mode (I) - prescribing
```
```json
{
    "Skills" : "Hard and soft skills"
}
 
```
To exit and save:
```bash
ESC
:wq
```
12. Send 2 files at once to an external repository.
```bash
git add . && git commit -m "preferences and skill" && git push
```
13.  On the web interface, create the bug_report.json file.
Add file/create new file
GitHub -> add file -> create new file -> bug_report.json
14. Modify the *bug_report.json* file on the web interface, add a bug report in JSON format.
GitHub -> bug_report.json -> edit this file
```json
{ 
         "Summary" : "In CTR (Click through ratio) ‘Total’ row calculation is wrong", 
         "Product" : "Example product", 
         "Version" : 1.0, 
         "Platform" : "PC", 
         "Version" : "Windows 2000", 
         "Status" : "NEW", 
         "Severity" : "Major", 
         "Priority" : "P1", 
         "Component" : "Publisher stats", 
         "Steps to reproduce" : 1, 
         "Expected result" : "In CTR (Click through ratio) ‘Total’ row calculation should work as expected"  
}
```
15. Make Commit changes (save) changes on the web interface.
```bash
GitHub -> commit changes
```
16. Synchronize external and local JSON repository
```bash
git pull # (in terminal)
