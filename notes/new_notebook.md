## How to add a new python notebook to the DS8 Jupyter Hub for my connector class

*Patty Frontiera (pfrontiera@berkeley.edu),  last updated 01/23/2017*

This document describes one possible workflow for this process. See the [DS8 Connector-Instructors Workflow Wiki for another](https://github.com/data-8/connector-instructors/wiki/Workflow).


### ASSUMPTIONS:

- **Required:** I've got an account on the DS8 jupyter hub -  http://datahub.berkeley.edu. 
  - To test this, I open that url in a browser and make sure I can log in.
  - **If you or your student cannot login** see the [DS8 Contacts wiki](https://github.com/data-8/connector-instructors/wiki/Contacts).
  
- **Optional:** I've got a github account.
    - My github account has the right (write) persmissions to my http://github.com/data-8 connector repository, im my case: https://github.com/data-8/geospatial-connector
    - **If you have github questions**,  see the [DS8 Contacts wiki](https://github.com/data-8/connector-instructors/wiki/Contacts).
    


### CREATE NEW ASSIGMENT

I've got a new python notebook assignment for my students.

1. I login to my account on the DS8 jupyter hub.
2. I create a new notebook for my students or I upload one that I've created on my computer.
  * Once I'm logged in I can click on the `upload` button to upload files or `New > folder` to create a new folder for my assignment.

3. I upload any data files I need into the same jupyter folder (keeps things simple).
4. I run my notebook in the jupyter hub to make sure it works. 
  * **THIS STEP IS ESSENTIAL** as your local python environment may not be the same as that on the data8 jupyter hub.

5. I clear all outputs from my notebook to reduce the file size (Cell > All outputs > Clear).

6. I download my notebook if I have made any changes.


### ADD NEW ASSIGNMENT TO GITHUB

This step is not essential. You can download your notebook & data files and create a zipfile that you add to a bCourses assignment. 
If you do this, your students need to download it from bCourses and upload it to the DS8 jupyter hub. Using github makes 
the process of opening a new notebook in the jupyter hub as easy as opening a url. But it creates more work for you.

The process below is one of the easiest ways to add notebooks to your connector github repo but it is not the only way.


1. To add my assignment to github, I open my connector github repostitory site in my web browser, for me:
https://github.com/data-8/geospatial-connector

2. I create a new folder for my assignment, eg `hw1/readme.md` by clicking on the `Create new file` button and adding `hw1/`. 
  * That forward slash makes a folder, but the folder cannot be empty so I add a `readme.md` file.
3. I add a message to the readme.md file about the homework, e.g. `This is homework 1`.
4. I scroll down to add a one line commit message like `Created a new folder for HW1` and then click `Commit new file`.
5. In github, I click on the new folder to change to that directory.
6. Then, I upload my new assignment to this folder by clicking on "Upload files"
  * If the `upload files` or `create new file` button is not active then you do not have the correct permissions to your github repo.

7. I scroll down to add a one line commit message like `added homework data and notebook files` and then click `Commit new file`.

### OPEN GITHUB NOTEBOOK in THE JUPYTER HUB

8. Once I create my notebook I add it to bCourses as an assignment that links to the notebook. To create an `interact link` that allows my students to open the notebook on the class jupyter hub, I update the url below to point to the folder with my assigment. 

  * `http://datahub.berkeley.edu/user-redirect/interact?repo=<repo_name>&path=<path_name>`
  
  For example:
  * http://datahub.berkeley.edu/user-redirect/interact?repo=geospatial-connector&path=drafts1/geoparsing

9. And then I run the whole notebook again to make sure it didn't mess up.


### Tips

- Everything it github connector repo is public access. So, don't add your answer keys unless you want to share. Put those in bCourses.
- I recommend that you create a homework python notebook with the answers included. You can use then Chris Holgraf's script to strip out the answers and create a student version of the notebook. See this [connector-instructors github repo notebook] (https://github.com/data-8/connector-instructors/blob/master/examples/create_student_notebooks.ipynb).
- If you need to request a new python package be added to the DS8 jupyter hub, see the [DS8 Software Resources wiki](https://github.com/data-8/connector-instructors/wiki/Software-Resources). Allow two weeks and testing time.


### TBD

- How do I archive my Sp2016 repo so I can just have my Sp2017 files?




