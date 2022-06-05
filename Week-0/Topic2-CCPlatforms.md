# Week 0 Topic 2/3: Competitive Coding Platforms

There are a variety of platforms that you can use to practise questions and take part in contests.

We will look at some of the popular and reliable ones:

## Codeforces

**Codeforces** is one of the most popular website for competitive programming for its active community, clean and minimalist UI and interesting problem statements.

**Problems** are the basic questions that are asked during a contest. They consists of a problem statement followed by input constraints and finally sample test cases. Here is an [example](https://codeforces.com/problemset/problem/4/A) problem.

**Contests** consist of multiple problems ranging anywhere from 5 to 8 problems (mostly) in a generally increasing sense of difficulty, with each problem being assigned a certain number of points in direct correlation with it's difficulty level.

As time passes during a contest, each problem loses points at the rate of **n/250** points per minute where **n** is the original value of that problem.

So for instance, if a problem was worth 500 points then as time passes the total scorable points per problem decrease at a constant rate, something like:

| Time elapsed | Total scorable points |
| :---: | :---: |
| 0:00 | 500 |
| 0:01 | 498 |
| 0:02 | 496 |
| 0:03 | 490 |

Your rank is determined by the cumulative sum of the points of all problems you have solved.

When you submited a solution to a task, it is generally run against test cases which were prepared by the contest author. These are called **pre-tests** and they are run during the contests. Passing pre-tests does **not** gurantee the corectness of your solution as there are **system tests** that your code will be run against after the contest has finished. Only upon passing system tests will you be awarded points for that task.
Note that **there is a penalty for wrong submissions** However, there is no penalty for a submission that fails the first test case. 

Each submission of yours will contain a verdict indicating how successful it was and you can find a small summary of the verdicts here

1. Accepted (AC):<br>All tests cases passed and points are awarded.
2. Wrong Answer (WA):<br>Your solution produced the wrong answer on a certain test case and hence was not accepted. There is generally no partial marking on Codeforces so **0** points will be awareded for a WA.
3. Runtime Error (RTE):<br>Your code failed during runtime due to an error such as division by 0 or accessing an out of bounds element on an array.
4. Time Limit Exceeded (TLE):<br>Your code did not produce the correct answer within the time constraints set by the problem statement. You will need to optimise your code for it to pass.
5. Memory Limit Exceeded (MLE):<br>Just like the TLE, your solution tries to use more memory than the constraints set by the question.
6. Compilation Error (CE):<br>Your code failed to compile on the judging system. Make sure there are no syntax errors and you have chosen the right language for compilation when you submitted your solution.
7. Pretests Passed:<br>As mentioned above, your code has passed **only** the pretests for the given task. Points will only be awarded once your code also passes the system tests which you **must** note are generally more rigorous and can cause your program to fail if it is not efficient enough.
8. Hacked:<br>If your solution was hacked, it means that someone was able to come up with a test case that was able to break the logic of your solution. To be eligible to hack someone, you must **lock** your solution which is possible only after you have successfully solved it during the contest. Note that locking a problem means that if someone else hacks your solution, you **will not** be able to resubmit another solution.


**Rating System:** One may consider three major divisions in Codeforces in which contests take place:

1. Div 3: Rated for < 1600 rating participants
2. Div 2: Rated for < 2100 rating participants
3. Div 1: Rated for >= 2100 rating participants

**Tiers:** There are 10 tiers associated with each rating range with the lowest being newbie(grey) and highest being legendary grandmaster (red).

[How to use CodeForces](https://codeforces.com/blog/entry/99660)  

# Atcoder

AtCoder provides one of the best platforms for beginners to familiarize themselves with competitive programming. There are three main types of official contests on AtCoder:

1. AtCoder Beginner Contest (ABC): This is mainly targeted at those who are new to competitive programming. The problems are usually easy and educational. Anyone with basic knowledge of implementation, brute-force and simple math is guaranteed to solve at least 3 problems in ABCs. 

2. AtCoder Regular Contest (ARC): This is comparable to a Codeforces Div 2 Round, but the questions generally on the harder side.

3. AtCoder Grand Contest (AGC): One of the hardest types of contests on any platform out there, the problem difficulty scales very high with every task you solve.

**Contests and how they work**:

ABCs are usually held every weekend and they consist of 6 problems which are to be solved in a time limit of 100 minutes. It is rated for participants in the range 0 – 1999.
<br>
The problems are generally arranged in an increasing order of difficulty and hence grant an increasing number of points (100 for Task A, 200 for Task B and so on).When you solve a problem, you get the score assigned to it.<br>
However, you would incur a penalty for every incorrect submission (no deduction from score). The penalties are computed as (the time you spend to get your current score) + (5 minutes) \* (the number of incorrect attempts).<br>
Competitors are ranked first by total scores, then by penalties. The verdicts a submission may get are quite similar to the ones on Codeforces.

**Rating system**: In each contest, you get performance. This value represents how well you've performed in a contest. Your rating is computed as the weighted average (recent contests have more weights) of performances. After 10 rated contests, you can assume that your rating is close to your real strength.

# CodeChef

CodeChef is another popular platform. CodeChef hosts three kinds of contests:

1. The Long Challenge: These contests go on for 10 days, giving you enough time to think about a problem, try different ways approaches, etc. If you’re usually slow at solving problems but strong in concepts, this is ideal for you.
2. Cook Off: These are similar to most contests on Codeforces, spanning 2.5 hours, usually with about 5 – 7 problems to solve.
3. Lunchtime: This is similar to the Cook Off challenge, where you have 3 hours time to solve 5 – 7 problems.

CodeChef has **three** rating divisions, and based on your rating, you are categorized into Division 1 or Division 2 or Division 3. Division 1 is rated for participants with rating >= 2000 and division 2 for participants with rating < 2000 and >= 1600 and division 3 for participants with rating < 1600.

## Practise Problems

Here are a few problems for you to get started with, they're really simple and should help you understand how to submit code on the online platforms and practise basic coding skills:

**Codeforces:**

1. https://codeforces.com/problemset/problem/999/C
2. https://codeforces.com/problemset/problem/6/B
3. https://codeforces.com/problemset/problem/71/A
4. https://codeforces.com/problemset/problem/158/A
5. https://codeforces.com/problemset/problem/231/A

**AtCoder:**

2. https://atcoder.jp/contests/abc125/tasks/abc125_a
1. https://atcoder.jp/contests/abc127/tasks/abc127_a
1. https://atcoder.jp/contests/abc124/tasks/abc124_a
1. https://atcoder.jp/contests/abc126/tasks/abc126_a

**CodeChef:**

1. https://www.codechef.com/problems/CHEFBOTTLE
2. https://www.codechef.com/problems/START01
3. https://www.codechef.com/problems/HS08TEST
4. https://www.codechef.com/problems/WATERREQ
5. https://www.codechef.com/problems/INTEST
