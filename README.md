# CS128: Assignment 5: Pitch Analysis
#### License: https://github.com/dpatt27/CCL-Analysis/blob/main/LICENSE
#### Presentation Link: https://docs.google.com/presentation/d/1d4uZwj1udZdOhrvFpFKEV5gTg-lNHqxg-vz_-1lbCKA/edit#slide=id.p
## Author: Griffin Brown, Daniel Patterson
## Idea behind the project
With such an open ended project, we wished to write a code that provided insightful data analysis to something that we hold very close: baseball. The importance of statistics has increased as the technology in the sport has advanced, which allows us to use the data captured to provide a deeper look into the numbers. The data that I used came from the Trackman Data from the 2023 California Collegiate League (CCL), and contains every pitch's type (Fastball, Changeup, Curveball, Cutter, Sinker, Slider) and its attributes (spin rate, relative speed, horizontal and vertical break, and extension). What our code does is allow the user to input a desired pith to be analyzed. After inputting, our code will output (in descending order) the average relative speed for each team in the league. Then, the user will be asked to input two pitch attributes into the terminal, and will be outputted with the 20 best pitches thrown of the previous pitch type based on those two attributes. Each pitch is ranked by taking how many standard deviations above the mean each pitch is for the given attributes, and adds them together. 
## Utilization of our Project
In the baseball world, code like this is very useful for the team statisticians and scouts. This code could be used by them to analyze what pitchers are doing in regards to the metrics of their pitch repertoire. The output of our code has almost direct correlation to success. The top pitches for nearly every pitch type were thrown by pitchers who had success. With our code we are able to easily identify pitchers with outlying qualities for scouts to put on their draft board. 
Another potential usage could be for the coaching staff and front office. In the game of baseball, the higher the velocity a pitcher is able to throw pitches at, the better the pitch will be, especially in regards to the fastball. If front offices were able to identify players who were free agents or players looking to be traded that could increase their teams average pitch velocity, that may be very advantageous to creating a well-equiped pitching staff. There is always room for 'specialty' arms in the bullpen. Guys who were designed to face a select few batters, who have known weaknesses. The more guys that a front office is able to sign that have this unique ability, the better off the team could be.
### Citations
Initially we wrote different methods for each pitch. We inputted those methods into chat and asked to “make it generic so the user would input the pitch”
Python Dataframe: How to check specific columns for elements: https://stackoverflow.com/questions/65667918/python-dataframe-how-to-check-specific-columns-for-elements
How to calculate mean and standard deviation using pd on an excel.
Lines 31-34 in pitch_analysis_runner.py
How to assertEquals an Excel Matrix in python using pd
Line 36 in pitch_analysis_runner_tests.py
