## How to add a new python notebook to the DS8 Jupyter Hub for my connector class

### ASSUMPTIONS:

- **Required:** I've got an account on the DS8 jupyter hub -  http://datahub.berkeley.edu. 
  - To test this, I open that url in a browser and make sure I can log in.
  - **Who do I contact if I cannot?**
  - **What do I do if my student does not have access to the jupyter hub? Who do I contact**
  
- **Optional:** I've got a github account.
    - My github account has the right (write) persmissions to my http://github.com/data-8 connector repository, im my case: https://github.com/data-8/geospatial-connector
    - **Who do I contact to get permission to add files to my connector repostitory?**
    


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

8. I update the url below to point to the folder with my assigment, for example: 
  * https://data8.berkeley.edu/hub/interact?repo=geospatial-connector&path=drafts1/geoparsing
  * **Note: not working on datahub.berkeley.edu as of Jan 22,2017 - only working on data8.berkeley.edu**

9. And then I run the whole notebook again to make sure it didn't mess up.


### TO BE ADDED

- How I create the instructor version of the notebook with the answers and the student version of the exercise from the instructor version using Chris's script.

### QUESTIONS

- How do I archive my Sp2016 repo so I can just have my Sp2017 files?

### COMMENTS

- Everything it github connector repo is public access. So, don't add your answer keys unless you want to share. Put those in bCourses.



