# SkillSearch
A web app to search skilled people within university or college campus. 

WebApp Front-end: Used a combination of Bootstap CDN and HTML 5 / CSS 5.

WebApp Back-end: Used the Python based Flask framework, with pyhton support classes and MongoDB Database. 

Location of Source codes- Check the "Final Version Iteration_1" folder for full source code developed as part of Iteration 1.


Pre-requisites: 
1. A Running MongoDB instance in your machine.
If you are not familiar how to do this, refer this stackoverflow link => https://stackoverflow.com/questions/20796714/how-do-i-start-mongo-db-from-windows

2. A basic Command Prommpt(in case of Windows) or Terminal(Linux users). If you are not planning to use any of these, you need a Python IDE like PyCharm. Thats where this app is being developed and tested. 

Pre-Run Instructions:
1. Make sure there is an active MongoDB instance. 

2. Navigate to the project src/ folder in shell. 
If you are using PyCharm IDE, Load the project files and Make src/ folder as root folder(Right click -> MakeDirectoryas >).

Run Instructions / App Flow:
1. Execute the command(without quotes) 'python app.py' 
You should the local instance address on which app is running. Something like http://127.0.0.1:4995/

2. Click on that link or manually copy-paste the address in browser.  

3. Once you see the App main page, You can click Register. (since you have an account yet)

4. Complete Registration form and submit. You should see a "Registered Successfully" message. 

5. From there click either 'Add Skills' or 'Search People'

6. 'Add Skills' will redirect you to a page, where you can choose a pre-defined set of skills or choose a custome skill and 'Submit'

7. 'Search People' will redirect you to a page, where you can submit a skill name and get a list of people skilled on that. 

8. Once you done, you can click logout.

Unit-test Run:
python -m unittest test.py
python -m unittest test_ui.py

Inputs and Outputs: (Acceptance criteria for Iteration 1)
