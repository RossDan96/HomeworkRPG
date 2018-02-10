# Homework Trek RPG
**A Weird Time Management Tool by Daniel Ross**

Homework/PDA Extension that hooks into Google Calendar and creates events for assignments with completion percentage goals
It’s ideally a time management system

#### Trek
##### Description
The overall, longest term progress tracker with Character growth as a motivation.
##### Variables
-Lowest EXP(RedLine) = Lvl 12
-Highest EXP = lvl 21.
```
Property of Wizards of the Coast
Experience Points	Level	Proficiency Bonus
0	1	+2
300	2	+2
900	3	+2
2,700	4	+2
6,500	5	+3
14,000	6	+3
23,000	7	+3
34,000	8	+3
48,000	9	+4
64,000	10	+4
85,000	11	+4
100,000	12	+4
120,000	13	+5
140,000	14	+5
165,000	15	+5
195,000	16	+5
225,000	17	+6
265,000	18	+6
305,000	19	+6
355,000 20  +7
410,000
```
-Level up screen is a Crystal Ball which scrolls through the classes”Previous and Next”
-You select your character race when you start
-Make web based on the 6 skill points you can make the overall education timeline into a quest

#### Term/Quarter
##### Description
A Length of time in which one set of courses takes place. (Ex: *"Fall 2017 was the worst term ever."*)
##### Variables
-EXP Range based on credits and GPA
-Courses
-Credit Total

#### Course Class
##### Description
A Quantity of EXP in the Trek that is based on grade percentage.
##### Variables
-When is the Course
-Point Limit
-Course Credit
-Tuition Total
-Minimum percent grade to get a C (int Percent_RedLine)
-Minimum point grade to get a C (double Point_RedLine)
-The closer to 100% the more EXP you get (make this a non linear relationship so 100% is a lot of EXP)

#### Assingment Class
##### Description
A Quantity of EXP in a Course that is based on grade percentage.
##### Variables
- Start date
- Due Date
- Course
- Point Total
- Grade Percentage
- Give every assignment a dollar value by referencing the assignments percentage of a School credits cost and how much closer to C red line getting 100% of the points. >Worth up to X dollars. Where X is (Tuition Total)*(Point Total/Point_Redline)

