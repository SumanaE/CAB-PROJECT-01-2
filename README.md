# TCNJ Vehicle Fleet 
The goal of our model is to give our users a simple and easy way to view the impact of TCNJ's vehicle fleet on the environment. It will also provide administrators with a straightforward way to view the impact of each individual change on the fleet itself.

## Table of Contents
** **
- Our Team
- Features
- Updates
- Installation and Usage

## Our Team
-- --
|Name|Email|Major|
|------|-----|-------|      
|Maxwell Luz | luzm1@tcnj.edu|Computer Science
|John Donegan |  donegaj2@tcnj.edu|Accounting
|Sumana Endreddy | endreds1@tcnj.edu|Computer Science
|Alexandra Merritt | merrita4@tcnj.edu| Accounting
|Brian Petrovic | petrovb1@tcnj.edu| Accounting
|Harkiran Arora | arorah2@tcnj.edu| Accounting
|Haadi Malik | malikh5@tcnj.edu| Computer Science

## Features
-- --
- View statistics regarding percentage of electric cars and emmissions
- Compare different vehicles to view the better option
- Admin privileges
    - Add a new vehicle to the fleet
    - Remove a vehicle from the fleet
    - Replace a vehicle from the fleet

## Updates
-- --
- January 31: Project topic selection
    - **~Janurary 31: Stage I due**
- February 2: Created a rough draft regarding the project specifications
- February 5: Finished the project proposal rough draft and submitted it
    - **February 6: Stage IIa due**
- February 13: Used instructor feedback to edit the project proposal
- February 15: Finished revising the project proposal and submitted the final copy
    - **February 16: Stage IIb due**
- February 23: Started developing the ER Diagram needed to begin conceptualizing the database
- February 26-27: Used the knowledge presented in class to start fixing the original ER
- March 3: With help from Dr. DeGood, we updated our ER Diagram and schema
- March 6: Talked with our group and started developing the Mid-Semester Project Presentation and the **planned** User Inteface model/diagram
- March 8: Created the Mid-Semester Project Report and started filling it out
- March 9: Finished and submitted Stage III and the Mid-Semester Project Report and Presentation
    - **March 9: Stage III due**
    - **March 10: Mid-Semester Project Report and Presentation due**
- March 12: Used presentation feedback and edited our User Interface model
- March 14: Attempted to start normalizing our ER Diagram to BC-NF, this endeavor would take a long time
- March 17: Started defining the different views (virtual tables) required
- March 20: Finished the different views and started to develop a set of queries that could fulfill our transaction requirements 
- March 25: With much assistance from Dr. DeGood, the ER Diagram was normalized to BC-NF and the set of queries was finished
    - **March 27: Stage IV due**
- March 29-April 5: Started/continued writing and executing SQL commands to create tables and insert data
    - **April 6: Stage Va due**
- April 10-13: Implemented a simple User Interface in it's most basic form, with text boxes
- April 19: Experimented with the interface and query interaction to get our first query working
- April 25: Finished adding the rest of the queries to the interface
    - **April 25: Stage Vb due**
- April 28: Added drop downs to replace the text boxes to ensure valid inputs, even if the inputs returned null
- April 30: Made visual modifications to the HTML and CSS of the interface
    - **May 1: Stage VI due (CSC315)**
- May 3: Added the feature allowing the user to compare the costs of two different vehicles
- May 4: Started to wrap up changes and finished the Final Project Report and Presentation
    - **May 5: Stage VI-Final Project Presentation due (CSC315/ACC311)**
    - **May 6: Stage VII-Final Project Report due**
    - **May 6: Stage VIII due**
- Nothing yet
- 
## How to Install and Use
- clone the repository
- you must first perform this one time installation
```
# install python pip and psycopg2 packages
sudo pacman -Syu
sudo pacman -S python-pip python-psycopg2

# install flask
pip install flask
```
To run the Flask application, simply execute:

```
export FLASK_APP=app.py
flask run
# then browse to http://127.0.0.1:5000/
```

- Now you are ready to use the application. 
- Use the dropdown menus to select different parameters for the queries.
- Results will be displayed in a seperate table
