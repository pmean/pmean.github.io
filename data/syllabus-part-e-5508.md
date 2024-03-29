---
title: "MEDB 5508, Introduction to SQL, Syllabus, Part E"
---

### Specific Information about this class

#### Required and Recommended Materials	
+ There is NO required textbook for this class. A recommended textbook is Learning SQL- Master SQL Fundamentals, By Alan Beaulieu Publisher: O'Reilly Media. Dr. Simon and Suman Sahil have copies of this book and students may review by appointment. Online tutorials include [w3schools](https://www.w3schools.com/sql/) (this may be used as a step by step tutorial or you as a reference to learn more about a specific SQL command), [SQL Tutorial](http://www.sqltutorial.org/) (this site organizes the SQL commands into groups for easy review).

#### Course Expectations, Course Policies, Requirements and Standards for Student Coursework and Student Behavior
+ You are expected to write and run your own programs in this class. You cannot ask someone else to write your programs. You are welcome and encouraged to adapt programs that have been written by your teachers in this class. You cannot adapt programs written by other students or by outsiders.
+ If a program that you wrote does not run correctly, you are welcome to show that program to your teachers, to other students, or to outsiders and ask for help. You may fix your programs based on this advice, but you cannot ask anyone other than your teachers to rewrite your programs themselves.
+ You alone must write any comments in the discussion boards. You can comment on or quote others in the discussion board as long as this is clearly indicated.
+ You cannot seek assistance from other students or outsiders for any quizzes or tests. If you are confused by a question or do not know the answer, you are welcome to discuss this with your teachers+ You are expected to do your homework independently. You can seek help from your instructors, from colleagues, or from the Internet to help decode an error message that you don't understand. You can adapt code that you find on the Internet. We recommend that you acknowledge the source for that code in the comments of your program, but this is not required.

#### Evaluation and Grading
+ Students will be required to post messages on the Canvas discussion boards, take brief quizzes on Canvas, and submit homework assignments in PDF format on Canvas. Your work is due on the specified date. We need to keep the class on the same time schedule for a variety of reasons. If illness, family issues, work responsibilities, or other commitments prevent you from completing on time, please contact me before the due date. Late submission without prior notice will receive a one point deduction. If you find yourself repeatedly falling behind on quizzes and assignments, it would be good to set up a videoconfernce with one or both of us to discuss this.
+ This course is grade Credit/No Credit (Pass/Fail). Students who complete at least 80% of the regular coursework and sucessfully complete the final project will receive credit for the course.

#### Final Exam
+ The final exam needs online to be completed prior to the last day of classes.

### Description of Course Topics, Assignments, Requirements and Assignment deadlines

```{r, echo=FALSE}
f0 <- "https://raw.githubusercontent.com/pmean/"
f1 <- "introduction-to-sql/master/modules/5508-0"
f2 <- "-objectives.md"
tx <- NULL
for (i in 1:8) {
  fn <- paste0(f0, f1, i, f2)
  tx <- append(tx, readLines(fn, warn=FALSE)[-(1:3)])
  tx <- append(tx, " ")
}
tx <- paste0(tx, collapse="\n")
```

`r tx`