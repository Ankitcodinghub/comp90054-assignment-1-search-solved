# comp90054-assignment-1-search-solved
**TO GET THIS SOLUTION VISIT:** [COMP90054 Assignment 1 Search Solved](https://www.ankitcodinghub.com/product/comp90054-ai-planning-for-autonomy-assignment-1-search-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120112&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP90054 Assignment 1 Search Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
You must read fully and carefully the assignment specification and instructions detailed in this file. You are NOT to modify this file in any way.

Course Weight: 10%

Assignment type:: Individual

ILOs covered: 1, 2, and 3

Submission method: via git tagging (see Submission Instructions below for instructions)

The aim of this assignment is to get you acquainted with AI search techniques and how to derive heuristics in Pacman, as well as to understand the Python-based Pacman infrastructure.

Your task

You must build and submit your solution using the sample code we provide you in this repository, which is different from the original UC

Berlkley code base. If you want to provide a report with your submission (e.g., reflections, acknowledgments, etc.), please do so in file

REPORT.md.

Please remember to complete the STUDENT.md file with your individual submission details (so we can identify you when it comes time to submit).

You should only work and modify files search.py and searchAgents.py in doing your solution. Do not change the other Python files in this distribution.

Your code must not have carry any personal information, like your student number or your name. That info should go in the

STUDENT.md file, as per instructions above. If you use an IDE that inserts your name, student number, or username, you should disable that.

Assignment 1 FAQ is available to answer common questions you might have about the Assignment 1 on ED at https://edstem.org/au/courses/6410/discussion/543003

Getting started on GitHub – this video explains how to clone, git add, commit and push while developing your solution for this assignment: https://www.loom.com/share/ae7e93ab8bec40be96b638c49081e3d9

You should code your implementations only at the locations in the template code indicated by ***YOUR CODE HERE*** in files search.py and searchAgents.py, please do not change code at any other locations or in any other files.

Implement the Enforced Hill Climbing algorithm discussed in lectures, using Manhattan Distance as the heuristic, by inserting your code into the template indicated by comment ***YOUR CODE HERE FOR TASK 1***, you can view the location at this link: search.py#L129.

Note that you don’t have to implement Manhattan Distance, as this has already been implemented for you in the template code, although you will need to call the heuristic from inside your search. You should be able to test the algorithm using the following command:

python pacman.py -l mediumMaze -p SearchAgent -a fn=ehc,heuristic=manhattanHeuristic

Other layouts are available in the layouts directory, and you can easily create you own!

This part involves solving a more complicated problem. Just like in Q7 of the Berkerley Pacman framework, you will be required to create an agent that will eat all of the food (dots) in a maze. Before doing so, however, the agent must eat a Capsule that is present in the maze. Your code should ensure that no food is eaten before the Capsule. You can assume that there is always exactly one Capsule in the maze, and that there will always be at least one path from Pacman’s starting point to the capsule that doesn’t pass through any food.

You should be able to test your program by running the following code (in one line):

python pacman.py -l capsuleSearch -p CapsuleSearchAgent -a fn=astar,prob=CapsuleSearchProblem,heuristic=capsuleProblemHeuristic

—- | ———– | ———– | | &lt; 210 | 2 | &lt; 2185 | 2 | 4 | | &gt; 210 | 1.75 | &gt; 2185 | 1.75 | 3.5 | | &gt; 213 | 1.5 | &gt; 3516 | 1.5 | 3 | | &gt; 644 | 1.25 | &gt;

4558 | 1.25 | 2.5 | | &gt; 853 | 1 | &gt; 5542 | 1 | 2 |

Jump Point Search (JPS) is a very effective search for a grid problem with sparse number of obstacles. The original JPS (which can be found here) is designed with the capability of moving in diagonal. Implement the orthogonal version of JPS, using Manhattan Distance as the heuristic, by inserting your code into the template indicated by comment ***YOUR CODE HERE FOR TASK 3***, you can view the location at this link: search.py#L140.

Note that you don’t have to implement Manhattan Distance, as this has already been implemented for you in the template code, although you will need to call the heuristic from inside your search. You should be able to test the algorithm using the following command:

python pacman.py -l mediumMaze -p SearchAgent -a fn=jps,heuristic=manhattanHeuristic

Other layouts are available in the layouts directory, and you can easily create you own!

hints: – The JPS algorithm in the paper describes a grid that most of the cells have 8 neighbors and agent can move in diagonal. In order to convert it to in orthogonal only. You will have to replace Line 8-11 in Algorithm 2 with your own ideas to check future forced neighbors in vertical (which potential make the current node a jump point).

To help have a better understanding of the orthogonal JPS, we have created a video to explain how it works.

Marking criteria

Commit early, commit often: single or few commits with all the solution or big chucks of it, is not good practice.

Use meaningful commit messages: as a comment in your code, the message should clearly summarize what the commit is about.

Messages like “fix”, “work”, “commit”, “changes” are poor and do not help us understand what was done.

Use atomic commits: avoid commits doing many things; let alone one commit solving many questions of the project. Each commit should be about one (little but interesting) thing.

Checking your submission

Run the following command to run sanity checks using our test files:

python ./autograder.py –test-directory=test_cases_assignment1

It is important that you are able to run the autograder and have these tests pass, otherwise, our marking scripts will NOT work on your submission.

NOTE: You should not change any files other than search.py and searchAgents.py. You should not import any additional libraries into your code. This risks being incompatible with our marking scripts.

Submission Instructions

This repository serves as a start code for you to carry out your solution for Project 1 – Search from the set of UC Pacman Projects and the marked questions.

To submit your assignment you must complete the following three steps:

1. Complete the STUDENT.md file with your details of the submission.

2. Check that your solution runs on Python 3.6 and that your source code does not include personal information, like your student number or name.

3. Tag the commit version you want to be graded with tag submission.

Note that a tag is NOT a branch, so do not just create a branch called “submission” as that will not amount to tagging.

4. Fill the Assignment 1 Certification Form.

Please view the following to learn how to Tag your commit version you want to be graded:

How to create a Tag using the Command Line: https://www.loom.com/share/17ec72b954454bc89bbe1dbb0bd2874f

Another way to create a Tag using the User Interface: https://www.loom.com/share/3cd39e97919e4b688d9841613aba6973

Important information

Corrections: From time to time, students or staff find errors (e.g., typos, unclear instructions, etc.) in the assignment specification. In that case, corrected version of this file will be produced, announced, and distributed for you to commit and push into your repository. Because of that, you are NOT to modify this file in any way to avoid conflicts.

About this repo: You must ALWAYS keep your fork private and never share it with anybody in or outside the course, except your teammates, even after the course is completed. You are not allowed to make another repository copy outside the provided GitHub Classroom without the written permission of the teaching staff. Please respect the authors request:

Please do not distribute or post solutions to any of the projects.

Please remember to follow all the submission steps as per assignment specification.

COMP90054 Code of Honour

We expect every UoM student taking this course to adhere to it Code of Honour under which every learner-student should:

Submit their own original work.

Do not share answers with others.

Report suspected violations.

Engage in any other activities that will dishonestly improve their results or dishonestly improve or damage the results of others.

Unethical behaviour is extremely serious and consequences are painful for everyone. We expect enrolled students/learners to take full ownership of your work and respect the work of teachers and other students.

I hope you enjoy the assignment and learn from it, and if you still have doubts about the assignment and/or this specification do not hesitate asking in the ED discussion Forum and we will try to address it as quickly as we can!

GOOD LUCK and HAPPY PACMAN!

Acknowledgements
