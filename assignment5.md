# Assignment 5 
## SQL Query: 
SELECT *

FROM murder_2015_final m15

JOIN murder_2016_prelim m16
  
  ON m15.city = m16.city
 
 AND m15.state = m16.state;

 <img width="1365" height="694" alt="Screenshot 2026-02-25 at 9 08 32 PM" src="https://github.com/user-attachments/assets/bc62fb3b-0d8e-4c34-ab5a-48a70f3d0a93" />
From this table, the data on 2015 murders from murder_2015_final is more accurate than murder_2016_prelim. The data from murder_2015_final contains full-year official totals from the FBI Uniform Crime Reports. Just by spot-checking some of the numbers, I found that murder_2016_prelim's 2015 numbers were from local sources and not final counts. 
In murder_2015_final, it was reported that Chicago had 478 murders, but murder_2016_prelim reported 378. Coverage of FBI data from the Boston Globe confirmed that Chicago had 478 murders in 2015 and not 378. Similarly, data from MPD reported that Washington, D.C., had 162 murders in 2015, not 105. 
The data from murder_2015_final includes full-year totals and matches other news sources that also pull from the FBI Uniform Crime Reports. The data from murder_2016_prelim only includes year-to-date data and is not comparable across cities, meaning it undercounts full-year totals. 
