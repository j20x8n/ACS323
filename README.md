java c
ACS323 Assignment 
Intelligent Systems 
Academic Year: 2024/2025 
Module:  ACS323
Title:  Intelligent Systems
Date Set:  Friday          06/12/2024       at   15:00
Date for Submission:  Monday 23/12/2024         at   23:59Task: Produce written solutions to all the assignment questions. Where numerical answers   are   required, show your full procedure, including details of the   fuzzy   rules   in   terms   of   grid-   tables, fuzzy membership functions, scaling factors, plots and diagrams. THERE IS NO LIMIT TO THE NUMBER OF PAGES YOU WISH TO SUBMIT. 
Notes: 
•          This work   is worth 40% of your overall   mark for this   module
•          PARTS A      B   carry equal   weighting   of 50 Marks   each
•          You are reminded that the   submitted work   must   be personal.PLEASE READ ALL OTHER ANSCILLARY MATERIAL CAREFULLY THAT SUPPORTS THIS ASSIGNMENT SHEET TO    ENSURE THAT YOU ARE SUBMITTING ALL WORK MATERIAL IN THE REQUIRED WAY: 
“guide notes for acs323 assignment 2024 2025.pdf” 
“instructions on how to provide acs323 assignment files 2024 2025.pdf”
PART A- FUZZY DECISION-MAKING Consider   the   process   relating   to   muscle   relaxation,   as   seen   in   your Laboratory Session PART A,   represented   by   the   following   Equations [PLEASE NOTE THE NEW VALUE RELATING TO THE    PREDOMINANT TIME-CONSTANT- CHANGE    IT    IN YOUR MATLAB-SIMULINK MODEL]:
where Y is   the   overall   output   of the   system   (muscle   relaxation), U is   the   input   to the   system   (amount of drug   infused).The main objective is to design a closed-loop control strategy which should   maintain   a steady   level   of   muscle   relaxation   (output ‘Y’)   by   manipulating   the   level   of   drug   infused   (input ‘U’),   given   a   reference target of muscle   relaxation (‘Ref’)- see   Figure A1- Use a reference target of 0.8 all throughout and a simulation time of 300 minutes:
a)      Write a two-page survey   (a   critic)   about   three   (3)   applications   of   fuzzy   logic   based   technologies       (choose       one       or       several         applications         areas:         control,          prediction,   classification,   fault   monitoring,   etc.)   for   real-world   problems   which   you   would   have   identified   from   the   open   literature   (include   full   details   of   all   references   hence   used-   these can be research papers,   general   articles,   and/or weblinks). [8 MARKS] 
b)       Design a   Fuzzy PI-type controller, as shown in Figure A1, via   a fuzzy   rule-base which   should   include 25 fuzzy rules with Gaussian Membership   Functions.[The candidate is expected to use: 1. the fuzzy 3D surface to tune the rules; 2. their knowledge of tuning the PID tuning factors, all in order to obtain the best possible outcome for the output response in terms of minimum overshoot, fast rise-time and fast settling-time; include simulations with disturbances]. [13 MARKS] 
c)       Transform   the   fuzzy   rule-base   designed   in   Part   A)b)   into   a   Fuzzy   PD-type   controller
which should also   include 25 fuzzy rules with Gaussian   Membership   Functions.[The candidate is expected to use: 1. the fuzzy 3D surface to tune the rules; 2. their knowledge of tuning the PID tuning factors, all in order to obtain the best possible outcome for the output response in terms of minimum steady-state error,       minimum overshoot, fast rise-time and fast settling-time; include simulations with disturbances].

Figure A1- Fuzzy-PI   Control   of   Muscle   Relaxation
[12 MARKS] 
d)       Using   the   closed-loop   data   from   Part   A)c)   derive   an   ANFIS   based   controller   for   the   process, which   is described   b代 写ACS323 Assignment Intelligent Systems 2024/2025Matlab
代做程序编程语言y   Equations (A.   1) and   (A.2),   to   achieve   a   similar   control   performance as that   in c). What would   be the advantages of such a   new   system? [12 MARKS] 
e)      Compare   the   controllers   in   Parts   A)b),   A)c),   and   A)d)   in   terms   of:   flexibility   in   the   structure   (controller type)   and   performance   (accuracy).   For the   latter   you   can   rely   on   one or more performance indices, e.g. Mean   Absolute Error (MAE), Mean Square Error   (MSE), and   Root-Mean   Square   Error (RMSE). [5 MARKS] 
PART B- FUZZY PREDICTIVE MODELLING On Black-Board, you will find one (1) file named “acs323assignmentdata.mat” (in the folder   “   Module   Assignment”)   relating   to   industrial   data.   This   data   set   should   reflect   a   system   with   four   (4)   inputs   (Input   1,   …   ,   Input   4)   and   one   (1)   output.   The   minimum   and   maximum   values   for all inputs and outputs in the provided data can be found using the “min” and “max” MATLAB   commands.
Upload this file onto your local drive   which   you   will   subsequently   use   to   carry-out   tasks   Parts
B)a)-B)e)   in   MATLAB.
Once you   have uploaded this file   in   MATLAB and double-clicked on   it,   it   will collapse   into   two   (2)   files:   one   file,   “acs323assignmentdata”,   contains   the   actual   quantitative   data,   and   the   second file,   “explanation”, provides details on the names   for each of   the   five (5) data   features.
a)       Use the ANFIS tool in   MATLAB to obtain a fuzzy TSK-type model, with 3 membership functions for each input. The fitness of the   model should   be   assessed   with   the   use   of   a   quantitative   index   (or   indices)   such   as   the   RMSE,   MSE   or   MAE   to   establish   the   validity   of   the    model.   You   can    use    one    performance    index    or    more    than   one   all   throughout.[The candidate will partition the data accordingly, select the most appropriate type of fuzzy MFs, output function and the number of learning epochs which will lead to the best outcome in the least-square sense]. [18 MARKS] 
b)       Using the model   derived in Part B)a) find the values of   the output for the following input   vectors:
Input   1 = 0.15;   Input 2   =   0.22;   Input   3   =   1;   Input 4   =   0.011;            Input   1 = 0.06;   Input 2   =   0.28;   Input   3   =   0.4;   Input 4   =   0.012; [4 MARKS] 
c)       Extend the fuzzy   modelling   exercise conducted   in   Part   B)a) to   include 4 membership functions for each input, then 5 membership functions for each input.   Here   also,   the   fitness   of   the   models   should   be   assessed   with   the   use   of   a   quantitative   index   (or   indices) such as the   RMSE,   MSE or MAE to establish the   validity   of the   models.[The candidate will partition the data accordingly, select the most appropriate type of fuzzy MFs, output function and the number of learning epochs which will lead to the best outcome]. [18 MARKS] 
d)       Using   the   models   derived   in   Part   B)c)   find   the   values   of   the   output   for   the   following   input vectors:
Input   1 = 0.15;   Input 2   =   0.22;   Input   3   =   1;   Input 4   =   0.011;
Input   1 = 0.06;   Input 2   = 0.28;   Input   3   =   0.4;   Input   4   =   0.012; [4 MARKS] e)      Compare   the   models   derived   in   Parts   B)a)   and   B)c)   and   draw   your   own   conclusions   with    respect    to    model    accuracy    and    generalisation    properties    as    far    as:    1.      Data   partitioning between training and testing; 2. The number of   fuzzy MFs,   are   concerned. [6 MARKS] 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
