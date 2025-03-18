java c
FIT5147 Data Exploration and Visualisation 
Semester 1, 2025 
Programming Exercise 1: Tableau (5%) 
Please carefully   review all the   requirements   below to ensure   you   have   a   good   understanding   of what   is   required for your assessment.
1. Instructions Brief 
2. Assessment Resources 
3. Assessment Criteria 
4. How to Submit 
5.       Word Count  Penalties 
1. Instructions  Brief 
In this assignment you are   required to   read   in   some   data   and   explore   and visualise   it   using   Tableau   Public/Desktop, then also submit a   brief   report showing   your   findings   and   the visualisations you   used. It is an individual assignment and worth 5% of your total mark for FIT5147. 
Relevant learning outcomes for FIT5147: 
1.   Perform. exploratory data analysis   using a   range   of   visualisation   tools;
6.   Implement   interactive data visualisations   using   R and other tools
THE DATA: The data set   used   in this assignment   is   based   on the AusStage online   resource.   It   is “a   data      set of   live   Events with dramatic and   performance   content   covering   all   of Australia   and   New   Zealand   plus   many additional   International   links”   (AusStage,   n.d.) and   is   regularly   updated.   While the   data we are   using was collected   in   February   2025,   it   includes   both   recent   events      as well as ones   from   previous   centuries.
We   introduced this dataset   in the Week   1 Workshop.   For this   assignment,   use   the   provided   PE1 dataset to   produce your Tableau visualisations and visual   analysis.      It   is   based   on   that found   in AusStage   but   has   been slightly   modified.
To enhance your   understanding of the context   and   metadata, you   can   check   the   data   source   link.   Using the various   interactive tools for the data   source   of the full   dataset   may   help enrich your visual analysis: https://www.ausstage.edu.au/pages/learn/search-ausstage .   If   you discuss or   replicate the visualisations or   metadata   provided   by   AusStage,   be   sure   to reference these correctly   in your   report1.
Please   note that the event and   performance   names   relate to   real Australian   performance   art   and culture. Some   names   may   have some explicit   terms.
For this   PE1 assignment, the   resulting   data describes when   and where   events   occurred   in   the state of Victoria.   In this activity   we   will   explore the   use   of   a   few   attributes: 
Column 
Description 
Event Name 
The title or name of an Event. 
Event Identifier 
A unique number identifying an Event in AusStage. 
First Date Year 
The year of the Event's first public presentation, including previews 
First Date 
The year (and day or month if known) of the Event's first public presentation, including previews 
Last Date 
The year (and day or month if known) of the Event's final public presentation. 
Venue Name 
The name of the Venue where an event happens. 
Venue Identifier 
A unique number identifying the Venue where an event happens. 
Suburb 
The suburb or local district where the Event happens. 
State 
The Australian state or territory where the Event happens. 
Country 
The country where the Event happens. 
Primary Genre 
The kind of Event, as defined by its main mode of performance. 
Organisations 
The name of the organisation/s associated with an Event. 
Contributor Count 
Number of contributing people recorded in AusStage for this Event. 
Resources Count 
Number of related resources recorded in AusStage for this Event 
Longitude 
Geographical Location (longitude) of the Venue 
Latitude 
Geographical Location    (latitude) of the Venue 
Table   1:   Fields of the “AusStage_S12025PE1”   data set
In this data there are some irregularities or errors that were part of the original data. One of the   requirements of this assignment   is for you to find   (using data visualisation),   describe and   handle them. This   modified dataset can   be found on   Moodle   in   the   Assessments   section   under the   Programming   Exercise   1   heading.
References: 
AusStage.   (n.d.). AusStage: About. AusStage.   Retrieved   February   27,   2025, from
http://www.ausstage.edu.au/pages/learn/about 
VISUAL ANALYSIS QUESTIONS TO BE ADDRESSED 
Using the data and visual analytics,   you   will   need   to   answer the   following   questions:
1A.                   What are the most common event names? 
To answer this question, discuss   how you   are   going   to   identify,   measure   and   visualise   what are the   most common   events.
1B.                   How many events started each year over the last 25 years? 
To answer this question, discuss   how you   are   going   to   identify,   measure   and   visualise   the   number of events started   each   year.
1C.                      How many events were run or performed by each organisation? To answer this question,   treat each   Organisations   value   as   a   single   organisation,   even      if   it   includes   different groups.   Discuss   how you are going to   measure and   visualise   the   number of events for   each   organisation.
1D.                   How many organisations started events each year over the last 25 years? 
To answer this question, discuss   how you   are   going   to   identify,   measure   and   visualise   the   number of events started   each   year.
1E. How long did each event run for? 
To answer this question, discuss   how you   are   going   to   identify,   measure   and   visualise   the   number of years each   event   ran   in.
2.                            Based on the visualisations and findings for 1A-E, is it possible for you to now 
explain who (i.e., Organisation) ran or performed what events over the last 25 years? 
For this question, you   need to discuss whether   your   visual   analytics   for   1A-E   have enabled you to answer this question   or   not.   Be   sure to   explain   how   you   came   to   that   conclusion.
ASSESSMENT TASK 
The task   has two components: data exploration using Tableau,   and   a   short written report. Data Exploration using Tableau: 
The steps you are   expected to   complete:
1.         Load the dataset   in Tableau   Public/Desktop
2.       Use data   visualisation in Tableau to check for and find at least two aforementioned irregularities   in the dataset.   Each type of   irregularity   may occur   multiple   times   in   the   data. These   irregularities   are   not   related to   missing   data.<代 写FIT5147 Data Exploration and Visualisation Semester 1, 2025Python
代做程序编程语言br>3.       Amend the data to correct these   errors using any tool of your choice (e.g.,   Excel, Python,   R, Tableau) and justify your choice of correction   based   on   the   irregularity.
4. Use Tableau to create at least one visualisation per question (not   more   than   2   per   question) to conduct your visual analysis and   answer the   above   question.
Remember to select appropriate visual variables to   suit the   data   and   your   chosen   visualisation.
5.       Polish   up your visualisations   for   presentation,   e.g.,      add   a   suitable   title,   correctly   label   your axis,   make sure   labels and values   are   not truncated,   include   a   legend.   Ensure the font, font size and colour   are   suitable   and   legible   for   your   report.
6.       Write a   report that presents and describes your   data   exploration   process   and   visual   analysis. See   below for   details.
This exploration   must   be submitted as a   Tableau   workbook   file   (*twb   suffix).
Note:   Indications of   missing data   like UNKNOWN/unknown, NULL/null, N/A, tba values should   not   be   regarded as   irregularities for this assignment.      If Tableau   has any   issues automatically   recognising any date or time   information, then   this   is   not   to   be   regarded   as   an   irregularity for Step   2   but can   be corrected   by you   in   Tableau. 
Written Report 
Once you   have finished your data exploration, write   a   report   that   contains   the   following   information:
1.       Data   loading,   checking   and   cleaning   (i.e.,   Steps   1   to   3)
o    A   brief explanation   (maximum of one paragraph per error)   and   an
accompanying image of each of the errors or   irregularities   that   you   have   found, showing   how you found them using Tableau, and explaining  justifying how you   resolved them. The   image   must show a relevant visualisation,   not just the data or   a table. 
2.       Data   Exploration   and   Presentation   (i.e.,   Steps   4   and   5)
o    Explanation of what insights you   have   found   out   through   the   visual   analysis   in   order to answer the questions. This   should   include:
■       Your answer to the   question,   based   on your   visualisation(s).   Include   relevant visualisations   in   1 or   2 figures   per question.
.       Description of your   visualisation(s)   and   how   they   relate   to   the   data   and question   (i.e. why   it   is an appropriate visualisation   choice)
.       Justification   of   your   visualisation(s) and   choice   of   visual   variables
.       Any further   insights, or   issues that you   have   identified   from   the   data   or visualisation(s) while answering the   question.
The   report should   also:
●            Be submitted   as   a PDF file 
●          Be no more than 5 pages in   length,   including   figures,   with   a   minimum   font   size   of   10   (title   page and any table of   contents   are   excluded from   the   page   limit)
●          Be properly structured with   headings,   subheadings,   figure   captions   (in-text      referencing of captions),   page   numbers, and   references   (where appropriate)
●          Have high quality images of your visualisations   with   clearly   readable   and   legible   text/labels   (presume that   it   is   read as   part of an A4   document   with   no   zooming).
●          You   must   use   proper academic referencing for   all   reports   in this   unit.   This   should   follow either the APA or   IEEE    structure   as   recommended   by   the   Faculty.   Use   the library referencing guide for support.
●          Not   include   any   code   snippets except for   key   Calculated   Fields   in   Tableau.
● No Generative AI software   or   system   may   be   used   to   complete   this   assessment   task. This includes using any software that paraphrases, translates or rewrites your text. 
2. Assessment Resources 
● AusStage_S12025PE1.csv (Available   on   Moodle)
3. Assessment Criteria 
The following outlines the criteria which you   will   be   assessed   against. The   focus   of   the marker will   be on what you   have   included   in your   report,   but your   submitted Tableau Workbook   may   be examined   if there are any concerns   with   the   academic   integrity   of   your   work.
●          Demonstrated   ability to   check   and   clean   data   and   read   into   Tableau   [1%]
●          Demonstrated   ability to   appropriately   visualise   data   for   data   exploration   using   Tableau   [2%]
●          Demonstrated   ability to   see   trends/patterns   in   data   [1%]
●            Quality   of   report   [1%]
4. How to Submit 
Once you   have completed your work, take the following   steps to   submit   your   work.
1.         Save your   report   as a   .pdf file.
2.       Name your file   using   the   following   structure PE1_Surname_StudentID 
3.       Save your Tableau   workbook   as   a   .twb   file.
4.       Compress the   .twb workbook file   into   a   .zip   file   so   it   can   be   submitted   to   Moodle.   DO   NOT   include your   report   in your zip file, only your Tableau   workbook.
5.       Name your   zip file   using   the   following   structure PE1_Surname_StudentID 
6.       Click the Add Submission button   on   Moodle   to   submit   and   upload   your   report   and   workbook
Please note that your assignment MUST show a status of "Submitted for grading" before it can be marked. Any submission left in draft mode will not be marked. We recommend always double checking your submission has been completed and that you have uploaded the correct files. Penalties will apply to any submission which needs amendment after the deadline. 
5. Word Count  Late Penalty 
The   report   must not be more than 5 pages of graded   material   including figures   (min. font   size   10).   Up to   2 additional   pages   may   be   used   if you wish,   but   restricted to:
● 1   page   prior to   the   report   as   a   title   page   with   a   table   of   content.
●         1   page after the   report only for   references.
1   mark   (out of the total of 5)   will   be   deducted   if the   report   does   not   meet   these   requirements.As   per   Monash   policy: All   late submissions will   receive a   penalty   of 5%   per   day   (0.25   marks   per day out of a   total   of   5   marks)   late   inclusive,   including   weekends.   Work   submitted   more   than seven days after the   due   date   will   not   be   marked.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
