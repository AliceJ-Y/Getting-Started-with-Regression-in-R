# Getting-Started-with-Regression-in-R

This course introduces you to regression analysis, a commonly used statistical tool for examining how one factor (e.g., Exam Scores) relates to one or several other factors (e.g., Hours studied, Course attendance, Prior Proficiency, etc.). It will develop your theoretical understanding and practical skills for running regression models in R.

This course consists of two 2-hour sessions that integrate concept-focused discussions and practical R-based activities. By the end of the course, you will understand key regression concepts and be able to perform regression analysis in R.

Key Concepts Covered:

Variables (Dependent vs. Independent)
Linearity;
Residuals;
Coefficients (Intercepts vs. Slopes).

Key Practicals Include:

Model Fitting;
Checking Model Assumptions;
Visualising Fitted Models.

While this course is suitable for beginners, a basic understanding of R and statistical analyses is recommended. Participants should ensure R and necessary packages are installed prior to the course.

Installing R and Packages needed

Installing R and R Studio

For R On Noteable
Go to https://noteable.edina.ac.uk/login
Login with your EASE credentials
Select RStudio as a personal notebook server and press start
Go to File > New Project> Version Control > Git
Copy and Paste this repository URL https://github.com/DCS-training/RegressionAndMixedEffectsModelling as the Repository URL (The Project directory name will filled in automatically but you can change it if you want your folder in Notable to have a different name).
Decide where to locate the folder. By default, it will locate it in your home directory
Press Create Project Congratulations you have now pulled the content of the repository on your Notable server space.

Install R locally
Go to (https://www.r-project.org/)[https://www.r-project.org/]
Go to the download link
Choose your CRAN mirror nearer to your location (either Bristol or Imperial College London)
Download the correspondent version depending if you are using Windows Mac or Linux
For Windows click on install R for the first time. Then download R for Windows and follow the installation widget. If you get stuck follow this (video tutorial)[https://www.youtube.com/watch?v=GAGUDL-4aVw]
For Mac Download the most recent pkg file and follow the installation widget. If you get stuck follow this (video tutorial)[https://www.youtube.com/watch?v=EmZqlcKkJMM]

Once R is installed you can install R studio (R interface)
Go to (www.rstudio.com)[www.rstudio.com]
Go in download
Download the correspondent version depending on your Operating system and install it. If you get stuck check the videos linked above.

Install R packages and libraries

install.packages("tidyverse")

install.packages("effects")

install.packages("sjPlot")

library("tidyverse")

library("effects")

library("sjPlot")

Notes: "tidyverse" for cleaning and sorting out data; "effects" for creating tables and graphics that illustrate effects in linear models; "sjPlot" for plotting models.
