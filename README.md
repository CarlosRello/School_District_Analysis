# School_District_Analysis

## Overview of the school district analysis: 
When the school board notified Maria there might be evidence of academic dishonesty for reading and math grades on Thomas High School ninth graders, the logical approach to deal with these issue would be to remove the information from the Data until further information is reviewed. But since this would alter the numbers on the analysis (regarding the number of students and budget assigned to every student, there correct approach is to maintain the size of the data and just hold the info on the data that may be corrupted.
![Alt Text](https://github.com/CarlosRello/School_District_Analysis/blob/main/Resources/replace_to_NaN.png)
### How is the district summary affected?
The district summary is not affected considerably since the sample that’s been removed or is getting discarded is small considering the total amount of students 
![Alt Text](https://github.com/CarlosRello/School_District_Analysis/blob/main/Resources/District_summary_original.png)
![Alt Text](https://github.com/CarlosRello/School_District_Analysis/blob/main/Resources/District_summary2.png)
### How is the school summary affected?
It’s completely logical that the averages for Math reading and Overall in the Tomas High School are affected since the number of students that the average considers remain the same but the sample numbers are reduced by removing the number of students in whole ninth grade.
How does replacing the ninth-grade scores affect the following:
![Alt Text](https://github.com/CarlosRello/School_District_Analysis/blob/main/Resources/per_School_summary.png)
Replacing the data in the DataFrame for averages in Tomas HS gives a more accurate analysis due to the fact that there’s still not enough evidence to declare that how corrupted the information is, and until this is resolved the information should not affect the data that involves the complete school, overlooking this information and leave the data as it is and just remove the grades would involve a poor performance from that Charter School, with this information we can state without any doubt that the performance is District Schools is lower than the Charter.

