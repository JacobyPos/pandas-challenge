# pandas-challenge

Project - analyze school and student data to determine trends and further statistical analysis
Main file pulls and analyze school and student csv files and reports while running.

summary of analysis:
    analyzing the following to determine best learning environments:
        -charter schools vs public schools
        -school budget per students
        -grades 9, 10, 11, and 12
        -size of school

conclusions:
    -charter schools definitely have better overall passing rates than District schools
        -charter schools have an average of around 90% overall pass rate
        -public  schools have an average of around 54% overall pass rate
    -Schools with lower budgets tend to have a better overall passing rates.  I'd like to dig in to see if budget directly causes this, or if this is simply an observation of another cause.
        -  $0 < budget < $585 overall passing at 90%
        -$585 < budget < $630 overall passing at 81%
        -$630 < budget < $645 overall passing at 63%
        -$645 < budget < $680 overall passing at 54%
