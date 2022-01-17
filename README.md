**<h1>PyCity Schools District Analysis</h1>**


<h2>Overview</h2>


<p>School boards are tasked with difficult jobs. They must make important decisions based on information presented to them. These decisions can vary from athletics to budgets and much more. Delivering the correct information is imperative. In the Pycity School District it could impact over a dozen schools and thousands of students. Currently, budget is top of mind for the PyCity School Board. Each school participates in standardized testing. These tests provide consistent questions for student’s as to be able to compare the districts performance more fairly. The information gathered is analyzed to see how different variables can affect a student's performance. In conjunction with other data provided we will be able to see if students are excelling in their environments or struggling. If potential academic dishonesty is proven the values must be omitted to uphold the integrity of the system. Thomas High School, in the Pycity School District, there has been proven academic dishonesty within the 9th grade. Reading and math scores have been omitted and replaced with NaNs. The analysis below will explain how the omission of the 9th grade scores from THS have impacted the data.
  
<h2>Results and Analysis</h2>
<h4>How the district summary was affected:</h4>
<p>Omitting the 9th grade reading and math scores minimally impacted the overall district summary.  There are a total of 39,170 students in the schools combined. Thomas High School made up 1,635 of these students. 

![DistrictSummary](https://github.com/SarahMason2015/School_District_Analysis/blob/d508311ed73176cd5f5e053d3c1107a55841cd45/Pics/DistrictSum.png)

<h4>How the school was summary affected:</h4>
<p>On an individual level Thomas High School suffered heavily. Each one of the scores declined, which lowered the overall passing percentage by over 25 percentage points. 

![SchoolSummary](https://github.com/SarahMason2015/School_District_Analysis/blob/d508311ed73176cd5f5e053d3c1107a55841cd45/Pics/SchoolSum.png)

<h4>THS performance as a whole:</h4>
<p>Thomas High School, before omissions, had the second highest Overall Passing Percentage. After, they have fallen into the 8th position, placing themselves as the lowest rated charter school.  

![Ranking](https://github.com/SarahMason2015/School_District_Analysis/blob/d508311ed73176cd5f5e053d3c1107a55841cd45/Pics/Ranking.png)

<h3>How does replacing the ninth-grade scores affect the following:</h3>

>- Math and reading scores by grade- The averages for 10th – 12th grades stay the same and the 9th grade is Null, essentially zero. Therefor, yes there is a substantial change because there are null values for an entire grade.
  
>- Scores by school spending- In order to get a more accurate picture, we need to look at the per student budget. From the top to the bottom there is a $77 difference. When factoring in the omission, the difference is so small it could be considered a rounding error.

![perkidcost](https://github.com/SarahMason2015/School_District_Analysis/blob/61260fd0b615b7c0de52b95106fdc2e6b8126025/Pics/PerkidCost.png)
  
>- Scores by school size-Size does matter. With the omission of the 9th graders, there is a significant change within the Medium Sized Schools. Since THS falls within this category, that would be the logical explanation.  On a larger scale, you can see the Charter Schools average just over 1500 students, whereas the District Schools average over 3800. Although there are outliers, it is evident that having more students, lowers the overall scores. 

![school size](https://github.com/SarahMason2015/School_District_Analysis/blob/61260fd0b615b7c0de52b95106fdc2e6b8126025/Pics/SchoolSize.png)
  
>- Scores by school type – Whether or not the test scores were omitted, the difference between District and Charter Schools would not change. There is no doubt Charter School outperform District Schools by a landslide. The different for THS, is that when scores are omitted, they are now more in line with District Schools with averages. This is unfortunately subpar. 

![school type](https://github.com/SarahMason2015/School_District_Analysis/blob/c93ea203ce249fbc2bed39cb50abf94b43c80a15/Pics/Type.png)

<h2>Summary</h2>
  
<p>Presented above are two sets of data. Before and after the omission of the 9th grade reading and math scores from Thomas High School. In order to better understand how much and in what way the data was affected we had to break down the data. This has allowed us to see the difference in reading and math scores individually and together. It will also as allow us to see what changes occurred before and after the omission of data. 
  
<p>The district summary and per student budget had no significant changes. Unfortunately, when you begin to look at the data on a school level, that is where you see the biggest changes. As we were able to see above, the individual school summary declined in both reading and math causing the overall percentage to decline drastically. Taking this into account, THS ranking for overall percentage in the district also dropped from 2nd to 8th. Although they are still ranked above the district schools, the different between 7th, and 8th is still substantial.
  
  <p> In conclusion, if a single data set is omitted the impact can vary. When combined with a larger dataset there is a minimal impact. However, on its own, as we’ve seen with Thomas High School the results were huge. Not only did scores decline drastically, but these numbers could ultimately impact potential school funding and potential charter status.  




