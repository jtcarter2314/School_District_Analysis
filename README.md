# School_District_Analysis
### Overview of Project

# The schoolboard has notified that data from the students_complete.csv has academic dishonesty. Reading and math grades for Thomas High School ninth graders appear to have been altered. The task is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. After that, they want to repeat the school district analysis with the new dataset.

## Results

# It seems from the results that if you compare the results before and after excluding the dataset from ninth graders from Thomas High school, it seems to have altered the % passing math, % passing reading, and % overall passing. 

- The original district summary results below shows that the averages were overall higher before it was effected by the ninth graders of THS being taken out of the data. 


# PyCitySchool District Summary (Original)	
Total Schools	  Total Students	  Total Budget	    Average Math Score	Average Reading Score	  % Passing Math	% Passing Reading	  % Overall Passing
0	      15	        39,170	      $24,649,428.00	      79.0	                  81.9	               75	               86	                65

# PyCitySchool District Summary (non 9th grader grades THS)
Total Schools	Total Students	Total Budget	  Average Math Score	  Average Reading Score	  % Passing Math	  % Passing Reading	    % Overall Passing
0	      15	        39,170	  $24,649,428.00      	78.9	              81.9	                73.9	          84.7	                       64.1

- Similar results happened with the school summary.
- Passing math, read and overall grades drastically dropped when the grades were dropped from the dataset. It looked to seem more impactful in this analysts of the data. 

# School Summary (Original)
                             Students   Total Student Budget  Per School Budget Avg Math     Avg Read   % Pass Math  % Pass Read  % Overall Pass   Spending Range
Thomas High School	Charter   	1635	   $1,043,130.00	      $638.00	          83.418349	  83.848930	  93.272171	  97.308869	    90.948012	      $630-644

# School Summary (non 9th grader grades THS) 

Thomas High School	Charter	    1635	   $1,043,130.00	      $638.00	          83.350937	  83.896082	   66.911315	69.663609	    65.076453        $630-644
