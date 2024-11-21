java cMATH36031 Project 2 - deadline 22nd November 2024, time 1100hrs.
In this project, the dynamics between a fox and a rabbit will be investigated, by solving
differential equations modelling their positions at different times. The initial configuration
is shown in Figure 1, where the fox starts chasing the rabbit while the rabbit tries to escape
from its predator and moves towards its burrow instantaneously. The fox, initially located1
at (300, −550), pursues the rabbit with the initial speed sf0 = 15m/s in one of the following
two possible ways:
Warehouse
R(0,0)
B(600,600)
NW(200,0)
SW(200,−400)
F(300,−550)
Figure 1: Coordinates (in metres) of the fox (F), the rabbit (R) and its burrow (B) and the
two corners (SW,NW) of the warehouse.
❼ if the rabbit is in sight, the fox’s attack path points directly towards the rabbit (the
direction of the velocity vector of the fox is exact from the fox to the rabbit);
❼ if the view of the rabbit is blocked by the corner SW of an impenetrable warehouse
(assuming that the warehouse is extended indefinitely to the east), then the fox runs
1The subscripts f and r denote the fox and rabbit respectively. The units of the coordinates are metres.
1
directly towards this corner. If the rabbit is still not in sight when the corner is reached,
then the fox moves parallel to the NW-SW perimeter of the warehouse until it sees the
rabbit.
The rabbit, initially located at the origin (0, 0), runs towards its burrow at (600, 600) in
a straight line with initial speed sr0 = 11m/s.
Question 1: Constant speeds.. Assuming that both the fox and the rabbit run with
constant speeds sf0 = 15m/s and sr0 = 11m/s respectively, determine whether the rabbit
can be captured before it reaches its burrow. The rabbit is considered to be captured by the
fox, if the distance between them is smaller than or equal to 0.1 meter.
Question 2: Diminishing speeds. Let us consider a more realistic scenario, when
the hungry fox meets the tired rabbit. Because neither the fox nor the rabbit are in their
best conditions, their chasing/escaping speeds diminish in time, according to the amount of
distance (starting from the time they find each other and start running) they have travelled
so far. More precisely, their speeds at time t are given by
sf (t) = sf0e
−µf df (t)
, sr(t) = sr0e
−µrdr(t)
,
where sf0 = 15m/s and sr0 = 11m/s are the same initial speeds as above, µf = 0.0002m−1
and µr = 0.0008m−1 are the rates of the diminishing speeds, df (t) and dr(t) are the distance
they have travelled up to time t(> 0). Determine whether the rabbit can be captured before
it reaches its burrow. (You may assume that this diminishing speed starts from t = 0).
Outputs required You are required to submit a report (maximum 8 pages including
any appendices) in pdf form via the Turnitin submission box on Blackboard. Additionally
you need to submit your m-files or mlx-files used for the MATLAB codes via the Blackboard
Submission Box also on Blackboard. As part of the required output, in your report give
(i) the time T and the location of the fox when either the rabbit is captured or the rabbit
escapes to the burrow; (ii) the distance travelled by the fox in time T . Additionally provide
a plot showing the paths taken by both animals.
Additional information and guidelines
1. All coding must be done in MATLAB.
2. Treat both the fox and the rabbit as points, without worrying about their finite sizes
(as in most models).
3. The questions can be answered with different approaches, but you ne代 写MATH36031、Python
代做程序编程语言ed to use the
built-in ODE solver ode45 discussed during the lectures.
4. Avoid using hard-coded numbers. Any number in your code should either be given as
initial condition, or be derived from these conditions.
5. Keep to the page length not exceeding eight A4 pages, and there is no need for a title
page or abstract for a relative short report like this. Font sizes should be no smaller
than 11 point, and page margins no smaller than 2cm.
2
6. List the complete code of the whole function at the end of each question, or in an
appendix. Make your source code more readable, by keeping the indentation and
stylistic features, and can be copied from your submitted. Your published results
should be reproducable from the code attached.
7. Have a look at the generic rubric about how your report will be marked, and also the
intended learning outcomes about what you are expected to achieve in the end.
8. Avoid copying (too many) sentences directly from the project description, and try to
restate the problem with your own words or examples if possible.
9. You may use your report in the future as evidences of written work, so take it seriously.
10. Your target audience is a fellow student on your course: explain the questions so that
the report can be understood without this project description and your approach could
be implemented in another computer language like Python. The report should indicate
to the reader how well you understand the problem and the approach you took. Your
goal will be to communicate your solutions to another person rather than to show
you’ve completed the assignment.
11. Balance the explanation of the approach and the comments in the code. Avoid under commenting and over-commenting.
12. Aim for precision and clarity of writing.
13. Since there is no final exam, you are advised to spend at least 15 hours on each project,
with additional self-study if you are less experience with computer programming. Re member for a 10 credit module like this one, you are expect to spend 100 = 10 Ö 10
hours in total (including lectures, labs, self-study and coursework).
14. Please do not put any personal information on the report, only your student ID number.
15. The submission for each project will be open two weeks before the deadline. Only
your last submission will be marked, and anything submitted after the deadline will
be treated late and any penalty will be applied by the Teaching and Learning Office
in June according to the Undergraduate Student Handbook.
16. Whilst this project can be done without the use of any artificial intelligence (AI)
software tools, if you use any AI tools or software to help you with your
project, you must mention this in the report. Please study the guidelines
at
https://manchester-uk.libanswers.com/teaching-and-learning/faq/264824
on how to do this correctly.
The content and accuracy of the report will be your responsibility alone,
and any factually incorrect statements or mathematically incorrect content
will be penalised.
3
17. Your attention is also drawn to to the University’s Academic Malpractice Policy, see
https://documents.manchester.ac.uk/display.aspx?DocID=639. See also the guide lines on the use of AI via the course on Academic Integrity at:
https://www.education.library.manchester.ac.uk/mle/academic-integrity/
18. We are obliged to report cases of suspected academic malpractice, and people may
be subject to an additional oral assessment on the content of the report and codes
submitted.
4

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
