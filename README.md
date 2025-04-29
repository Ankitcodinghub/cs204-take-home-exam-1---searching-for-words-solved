# cs204-take-home-exam-1---searching-for-words-solved
**TO GET THIS SOLUTION VISIT:** [CS204 Take-Home Exam 1 – Searching for Words Solved](https://www.ankitcodinghub.com/product/cs204-advanced-programming-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109396&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS204 Take-Home Exam 1 – Searching for Words Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
DISCLAIMER:

Introduction

Inputs to Your Program

All the inputs in this THE are given to the program through the standard input (cin). Your program will start by reading a positive integer number, rows that indicates the number of rows in the matrix of characters; followed by “rows” number of lines which represent the actual matrix of characters (each input line/row is guaranteed to have the same number of characters, i.e., all matrix rows will have the same length, you don’t need to check for that).

Format of the Inputs

All the character inputs (and words) in this THE are uppercase English letters with no spaces, tabs or special characters. You can assume that this will be true for all the test cases that will be used, hence you do not need to do any extra check. Regarding the words, you can also assume that all the words that will be used in all the test cases will be of length greater than two (2).

Task of Searching

This section clarifies the algorithm you need to develop.

After reading the matrix and the words to search for, your program will search for each word (that it gets from the standard input) in the 2D vector that your program had constructed from the matrix.

This search can be done vertically, horizontally or diagonally (Note: anti-diagonal direction is not included for the search). It is also possible to go in the backward directions of these three directions as well.

The following illustration shows possible directions of search in the matrix:

You can also assume that a particular word will not occur in the matrix more than once, so you can safely stop the search regarding that word when the program finds it once.

Calculating the Score

Each word that your program can or cannot find in the matrix affects the score. Following are the rules of the game to calculate the score:

1. Words that lay horizontally or vertically increase the score by their number of letters (i.e., the word ‘MONEY’ would contribute 5 points).

2. Words that are found (vertically, horizontally, or diagonally) and are longer than 5 characters contribute 2 extra points to the overall score.

3. Words that lay diagonally increase the score by their number of letters multiplied by two (i.e., the word ‘BIKE’ would contribute 8 points (=4*2)).

4. For each word that cannot be found in the matrix, the total score will be deducted by

5.

Output of Your Program

Sample Runs

Below, we provide some sample runs of the program that you will develop along with an explanation for them. Your program should read the inputs as in the Input column and should print the final score as an integer value as in the Output column.

TC# Input Output Explanation

1 5

HJRLDGKU

AOYDOOOO

TRYTRUOA

OEGEZCDN

MRYTABLE

1

ATOM 4 5 represents the number of rows of the matrix, therefore it is followed by 5 lines of input. Then, 1 represents the number of words that will be searched for in the matrix, therefore it is followed by 1 line of input.

The output (score) is 4, as follows:

● The word ATOM is found vertically in the matrix as highlighted in the cell on the left. So, as per rule number 1 for calculating the score, the score is increased by the number of letters in the word ATOM. Thus, the final score is 4 as shown in the output column.

2 9

QJCMPVSOY FDOBORFEC

UANOTPTDZ

KLSLSCTND TXTMFJXGT

QERIOZJSW

LYUTYMIEE

BLCNDHDUG

TCTFGVYUB

2

STOP

CONSTRUCT 15 The output (score) is 15 (= 4+9+2), as follows:

● The word STOP can be found vertically (in reverse direction) as highlighted in the sample input.

● For the word CONSTRUCT (length = 9), it can be found vertically as highlighted in the sample input.

● And the last +2 points because the word CONSTRUCT is longer than 5 characters (according to rule # 2).

3 7

HRPIEQGVEOZKVEVUFU

LYOURYLAUEHLOZEYPB JTXNYIANINCLUDEHMB

CARJGZDLAFRBWPJZZV

QFQFKWEZNETTSOPHTN

HXEUGKDZGLGSQGLWRK

WOSCHOLARSHIPXFNQS

3

CAR

INCLUDE

SCHOLARSHIP 25 The output (score) is 25 (=3+7+11+2+2), as follows:

● The words CAR, INCLUDE, and SCHOLARSHIP can be found

horizontally. Therefore the score is the addition of their lengths

● +2 points are added for finding the word SCHOLARSHIP and +2 points are added for finding the word INCLUDE as they are longer than 5 characters (rule #2).

4 9

KEEPTFWSM

KYZCZISRS

BRKEYFAST

SNIJQWIRT

NECTIKLMH

WLRPEWLNT

YIAMAERCS

STWUDYNOY

KELMQZGAH

3

KEEP

ELITE

CREAM 14 The output (score) is 14 (=4+5+5) as, follows:

● The word ELITE can be found vertically. The word KEEP can be found horizontally.

● The word CREAM can be found horizontally (in reverse direction). Therefore the score is the addition of their lengths.

TC# Input Output Explanation

5 9

KEEPTFWSM

KYZCZISRS

BRKEYFAST

SNIJQWIRT

NECTIKLMH

WLRPEWLNT

YIAMAERCS

STWUDYNOY

KELMQZGAH

6

GOOGLE

KEEP

EMAIL

ELITE

CREAM

in the matrix, therefore the score is deducted by -5 for each one of them.

● Note: this is the same input matrix as the above test case, but there are extra three words to be searched for that happen not to be in the matrix.

6 5

SEARCH

DAPIJY

QTVAMK

NRAELQ

LGIFTZ

5

SAVE

SEARCH

AIM

LEARN

GIFT 31 The output (score) is 31(=4*2+(6+2)+3*2+5+4), as follows:

● The words SEARCH and GIFT can be found horizontally.

● The word LEARN can be found horizontally in reverse direction.

● The words SAVE and AIM can be found diagonally. Therefore, each one of them contributes to the overall score by their length multiplied by 2 (rule #3)

7 14

IJRFGRRSHLTEVC

YDWOTGRRUWFAGF

DIEJIGSETTSFLW

LWTNFPGGLBCFBJ

LBWGTPXKXKBXTK

WYRIZIPQKLZXDL

VGYZNGFRVMCBWW

QDVPDMRIYRLPMT

URCCQKTVCQXALH

LAEUBNPQTAGEZN

LJZSQMWLPLTSRA

QMZLUKHVVBIIMF

FCYZSLAAJLGYOK

DMOGJKTMMCAEPN

4

ESTABLISHMENT

IDENTIFICATION

GYM

RESULT 45 The output (score) is 45(= -5 + (14*2+2) + (3*2) + (6*2+2) ), as follows:

● The word GYM can be found diagonally in the reverse direction. Therefore it contributes to the score with 6 (=2*3), according to rule #3.

● The word IDENTIFICATION, can be found diagonally therefore it contributes to the score with 28 (=14*2), according to rule

#3. Also, it is longer than 5 characters. Therefore it contributes to the score with 2 extra points (rule #2).

● Same for the word RESULT, it can be found diagonally and is longer than 5 characters. Therefore it contributes to the score with 14 (=2*6+2)

● The word ESTABLISHMENT can not be found in the matrix.

Therefore, the score is deducted by 5 points.

Some Important Rules

Submit via SUCourse ONLY! Paper, e-mail or any other methods are not acceptable.

The internal clock of SUCourse might be a couple of minutes skewed, so make sure you do not leave the submission to the last minute. In the case of failing to submit your THE on time: “No successful submission on SUCourse on time = A grade of zero (0) directly.”

What and where to submit (PLEASE READ, IMPORTANT)

It’d be a good idea to write your name and last name in the program (as a comment line of course). Do not use any Turkish characters anywhere in your code (not even in comment parts). If your full name is “Duygu Karaoğlan Altop”, and if you want to write it as comment; then you must type it as follows:

// Duygu Karaoglan Altop

Since the grading process will be automatic, you are expected to strictly follow these guidelines. If you do not follow these guidelines, your grade will be zero (0). Any tiny change in the output format will result in your grade being zero (0), so please test your programs yourself, and against the sample runs that are available at the relevant assignment submission page on SUCourse.

In the CodeRunner, there are some visible and invisible (hidden) test cases. You will see your final grade (including hidden test cases) before submitting your code. There is no re-submission. You don’t have to complete your task in one time, you can continue from where you left last time but you should not press submit before finalizing it. Therefore, you should make sure that it’s your final solution version before you submit it. Also, we still do not suggest that you develop your solution on CodeRunner but rather on your IDE on your computer.

How to get help?

Good Luck!

Ahmed Salem, Duygu Karaoğlan Altop
