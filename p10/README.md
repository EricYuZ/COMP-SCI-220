# Project 10 (P10): Looking at Stars and Planets


## Corrections and clarifications:

* None yet.

**Find any issues?** Report to us:

- Chaithanya Naik Mude <cmude@wisc.edu>
- Kincannon Wilson <kgwilson2@wisc.edu>
- Yuheng Wu <wu459@wisc.edu>
- Jane Zhang <zhang2752@wisc.edu>


## Instructions:

This project will focus on **file handling**, **namedtuples**, **data cleaning** and **error handling**. To start, download [`p10.ipynb`](https://git.doit.wisc.edu/cdis/cs/courses/cs220/cs220-f22-projects/-/tree/main/p10/p10.ipynb), [`p10_test.py`](https://git.doit.wisc.edu/cdis/cs/courses/cs220/cs220-f22-projects/-/tree/main/p10/p10_test.py), and [`data.zip`](https://git.doit.wisc.edu/cdis/cs/courses/cs220/cs220-f22-projects/-/tree/main/p10/data.zip).

After downloading `data.zip`, make sure to extract it (using [Mac directions](http://osxdaily.com/2017/11/05/how-open-zip-file-mac/) or [Windows directions](https://support.microsoft.com/en-us/help/4028088/windows-zip-and-unzip-files)). After extracting, you should see a folder called `data`, which has the following files in it:

* .DS_Store
* .ipynb_checkpoints
* mapping_1.json
* mapping_2.json
* mapping_3.json
* mapping_4.json
* mapping_5.json
* planets_1.csv
* planets_2.csv
* planets_3.csv
* planets_4.csv
* planets_5.csv
* stars_1.csv
* stars_2.csv
* stars_3.csv
* stars_4.csv
* stars_5.csv

You may delete `data.zip` after extracting these files from it.

**Important**: You **must** make sure that your file structure looks like this:

```
+-- p10.ipynb
+-- p10_test.py
+-- data
|   +-- .DS_Store
|   +-- .ipynb_checkpoints
|   +-- mapping_1.json
|   +-- mapping_2.json
|   +-- mapping_3.json
|   +-- mapping_4.json
|   +-- mapping_5.json
|   +-- planets_1.csv
|   +-- planets_2.csv
|   +-- planets_3.csv
|   +-- planets_4.csv
|   +-- planets_5.csv
|   +-- stars_1.csv
|   +-- stars_2.csv
|   +-- stars_3.csv
|   +-- stars_4.csv
|   +-- stars_5.csv
```

Otherwise, your code may pass on **your computer**, but **fail** on the testing computer.

You will work on `p10.ipynb` and hand it in. You should follow the provided directions for each question. Questions have **specific** directions on what **to do** and what **not to do**.

------------------------------

## IMPORTANT Submission instructions:
- Review the [Grading Rubric](https://git.doit.wisc.edu/cdis/cs/courses/cs220/cs220-f22-projects/-/tree/main/p10/rubric.md), to ensure that you don't lose points during code review.
- You must **save your notebook file** before you run the cell containing **export**.
- Login to [Gradescope](https://www.gradescope.com/) and upload the zip file into the p10 assignment.
- If you completed the project with a **partner**, make sure to **add their name** by clicking "Add Group Member"
in Gradescope when uploading the p10 zip file.
       
   <img src="images/add_group_member.png" width="400">

   **Warning:** You will have to add your partner on Gradescope even if you have filled out this information in your `p10.ipynb` notebook.
   
- It is **your responsibility** to make sure that your project clears auto-grader tests on the Gradescope test system. Otter test results should be available in a few minutes after your submission. You should be able to see both PASS / FAIL results for the 10 test cases and your total score, which is accessible via Gradescope Dashboard (as in the image below):
       
    <img src="images/gradescope.png" width="400">
- **Important:** After you submit, you **need to verify** that your code is visible on Gradescope. If you displayed the output of a large variable (such as `planets_list`) anywhere in your notebook, **we will not be able to view or grade your submission**. Make sure you don't have any large outputs in any of your cells, and verify after submission that your code can be viewed.
- If you feel you have been incorrectly graded on a particular question during manual review, then you can find more about the Regrade Request process [here](https://piazza.com/class/l7f7vr5x63n7l1/post/320).
