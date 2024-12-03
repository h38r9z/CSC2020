java c
Module Title: 
Coding for Medical Scientists 
Module Code: 
CSC2020 
Module credits 
15 
% of Module Mark 
60% 
1. Required Task You will   be   provided with a   data file containing   electrophysiology   experiments   carried   out   as   part of a neuroscience practical class.    During this experiment, students evoked paired   synaptic   responses from   hippocampal   brain slices and then applied various   cocktails   of   drugs   to   monitor   how these   responses were changed   by the drugs.
Your task   is to write a   Matlab function to analyse these data   and write   a   short   report   on   your   findings.
More details on the experiment carried out   and   what   to   analyse   can   be   found   on   the   module   ELE   page.
Materials provided (on the ELE page): 
•         One   dataStruct.mat   file,   which   is   a   struct   with   10   fields.   Each   field   contains   a   replicate of the experiment.
•         An   Excel   file   called   notebook.xlsx   which   contains   information   about   when   each   drug cocktail was applied to the slice   in   each   experiment.
•         A file containing   important   information about the experimental details which you   will   need to carryout your analysis and some additional information about how to process   the   data
The report:
The   main   body   of the   text   should   not   exceed   2   page   of A4. As   guidance this   is   equivalent   to   about   1000 words.
It should   be formatted   as follows:
•                                 Font:   Calibri   (body)   11pt
•                                 Line spacing:   1.15
•                               Margins:   ‘Normal’ for   a Word   document:   2.54cm   all   sides   (top,   bottom,   left   and   right)
The   page   count   does not include   any   figures   or   tables   and   associated   legends.   Nor   does   it   include the code appendix   (see   below).
Each figure and table, with associated   legend, should   be   placed on a separate page   at the   end   of the document.
The text   should   be   appropriately formatted to   make   it   easily   readable –   i.e.   break   up text   by   including subheadings and avoiding   long   paragraphs.
Your   report should contain the following:
•          a very short   introduction,   setting   out   what   is   in   the   report.   Probably   no   more   than   a   paragraph or two.
•         a description of the data analysis   methods   and   explanation   of the   code.
•         a   results section containing:
o   A   multi-panel figure showing details of a single example experiment.
a.       You    should    include    example    traces    in    each    of    the    4    conditions    (i.e.   control and the 3   drug   conditions).
b.       A time course plot of a single experiment (e.g. a   plot   of time vs 1st   fEPSP   amplitude)
c.         As   an   example   of   the   sort   of   thing   required,   see   Fig   1A   from   Brown    Randall 2005 (link).
o   A   figure   summarising the   average   peak   amplitude   of the   1st    response   in the 4   conditions across all 10 of the experimental   replicates
o   An appropriate statistical analysis to determine the   effects   of the various   drug   treatments on the   peak amplitude of the   1st   response.
•         a   brief summary conclusion.   NB for the   purposes of this   report, it   is   NOT   important   to   know what the various drugs do   ata   pharmacological   level –   your   conclusions   should   simply summarise the   results.
•         an   appendix   containing   the   ‘published   code’   (see   attached   file   for   details   on   how   to   do   this).
How   to   publish
code.   pdf The function :
The function should:
•          have one input argument: the filename
•          have at    least    one output    argument:    a    table   array    containing    the    results    of    the   analyses    of    all    the    experiments.   The    table   array    should    contain    fields    with    the   following   information   in them   (at a   minimum):
o   the   filename   of   each   recording   (you   can   find   this   information   in   each   field   of   dataStruct)
o   the   average   peak   amplitude   of   the   1st   fEPSP   in   each   of   the   3   drug   conditions   and   in the   baseline condition.The   precise   way   in   which   this   table   is   arranged   is   up   to   you   but   it   sh代 写CSC2020 Coding for Medical  ScientistsR
代做程序编程语言ould   be   sensibly   organised with obvious but simple field names, so that it is clear what the   output from   the function   is.
•          Be   self-contained:   i.e.   if you   write   additional functions to   make   this   run,   they   should   be   included   as   local subfunctions within the same   m-file.
•          Be well-annotated with comments,   including a   brief ‘help’ description   explaining   how   the function should   be   used   (i.e. explaining what the   inputs and   outputs   are).
Use of Generative AI: 
This assessment falls   under the category of AI-supported, which   means   that   ethical   and
responsible   use of Generative AI tools   in the development   of this   assessment   is   supported.            This   may   include   using Generative AI tools to summarise   literature,   improve the   structure   of   your work or quality of   English   language. It is not permitted to use Generative AI to help with writing any of your code or doing any of the data analysis (including generating figures, tables or other outputs). Please see the   module specific   Generative   AI   Statement template   in the Assessment section   (you can find   it also   at   the   end   of this   document)   of   the   module   ELE   page for   more   details. Please keep a record of the tools, prompts and outputs used so you can produce these if necessary at aviva voce examination and demonstrate how you have built on this content to ensure your work is original. 
Submission 
For    the    coursework    on    this      module    you      must      submit both    your report and the .m file containing your code. The report should   be   in   either   MS   Word   (.doc   or   .docx)   or   .pdf format.   Please   ensure   that   your   name   DOES   NOT   appear   anywhere   in   the   document,   but   that   your   personal   ID   number   is   included.
The   naming of your   report file   must follow the format   below:   ID   number_ModuleCode_assessment   name_AC year
E.g. 91000000_CSC2020_report1_2022-23
The .m file and the report should be combined in a single .ZIP file and submitted to ELE by   the stated deadline.   For   instructions on   how   to submit,   please   see the   Medical   Sciences
Sharepoint
(https://www.exeter.ac.uk/students/infopoints/yourinfopointservices/assessments/) If you submit your work   late,   but are within one   hour of the   deadline,   a   penalty   of   5% will   be      deducted from your   mark (0%   if   below the   passmark).   For any work submitted   more than an   hour   late your   mark will   be capped at 40% (after   24   hours from   the   deadline   a   score   of   zero will   be   awarded). This is unless you   have valid   mitigation   (please visit thePersonal  Pastoral support ELE pagefor   more information.)
In submitting this you are declaring the work is your   own   independent   piece   of   work,   not         produced   in   collusion with   a fellow student or   plagiarized from   a fellow   student,   or   a web site, or a textbook, or any   other   information   source.   You   must   demonstrate   good   referencing   practise and ensure you   have sufficiently   paraphrased all   sources   of            information. 
Failure to do so   may   result   in   being   referred to   an academic   misconduct   panel which   has   the   power to grant   penalties   based   on specific criteria.   For   more details   please   revisit   the
Academic Honesty and Plagiarisminformation on   ELE.
3.Acquired skills 
•          Importing and analysing   data   in   Matlab
•         Statistical   analysis
•          Data   interpretation
•          Data   presentation
•          Report writing
4. Sources of support 
•          Matlab   help function,   notes and   reference   book.
• Assessment   documentation
•         Computer   lab   practical   classes
•          International students   and those   who   have   English   as   a   second   language   can   make   use   of   theEnglish Language Skills Development programme. This   programme   provides face-to-      face workshops and courses as well as one-to-one   assignment   writing tutorials   and   an
extensive   range of online   resources via theirGuided Independent Learning site. Find out
more   by   browsing the timetables:
https://www.exeter.ac.uk/into/englishlanguage/howtoparticipate/timetablessupport/ 
or   emailinginsessional@exeter.ac.uk 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
