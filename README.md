# https-github.com-bcaffo-courses

Course Title

Statistical Inference

Course Instructor(s)

The primary instructor of this class is Brian Caffo.

Brian is a professor at Johns Hopkins Biostatistics and co-directs the SMART working group.

This class is co-taught by Roger Peng and Jeff Leek. In addition, Sean Kross and Nick Carchedi have been helping greatly.

Course Description

In this class students will learn the fundamentals of statistical inference. Students will receive a broad overview of the goals, assumptions and modes of performing statistical inference. Students will be able to perform inferential tasks in highly targeted settings and will be able to use the skills developed as a roadmap for more complex inferential challenges.

Course Content

The course is taught via 13 lectures

Introduction
Probability
Conditional Probability
Expectations
Variance
Common Distributions
Asymptotics
T confidence intervals
Hypothesis testing
P-values
Power
Multiple Testing
Resampling
YouTube Videos

If you'd prefer to watch the videos on YouTube, you can do that here:

https://www.youtube.com/playlist?list=PLpl-gQkQivXiBmGyzLrUjzsblmQsLtkzJ

Course Book

There's now a (sort of) book for the class. It's a different sort of book published on LeanPub. If you purchase the book on LeanPub, you'll get all editions in the future for free. You pick the price on the site. You can get it here:

https://leanpub.com/LittleInferenceBook

However, you can also just read a web page rendering of the book here: https://leanpub.com/LittleInferenceBook/read

In addition, the book is on github if you want to render it yourself using pandoc https://github.com/bcaffo/LittleInferenceBook

Github repository

The most up to date information on the course lecture notes will always be in the Github repository

(https://github.com/DataScienceSpecialization/courses/tree/master/06_StatisticalInference)

Please issue pull requests so that we may improve the materials. Notice that Brian's forked github repo is sometimes out of sync with the Data Science Specialization repo managed by the other instructors. Make sure to check in Brian's master repo for the most up to date material.

If you would just like the full set of lecture pdfs, grab them here

If you would just like the full set of Rmd files for the lecture code, get it here.

Quizzes

There are four quizzes.
You must earn a grade of at least 80% to pass a quiz.
You may attempt each quiz up to 3 times in 8 hours.
The score from your most successful attempt will count toward your final grade.
The quizzes will cover the material from that week. The quizzes don't always exactly correspond to the material for that week. However, the material is always covered before the quiz is due. Here's the rough makeup

Quiz 1 covers lectures 1 - 4
Quiz 2 covers lectures 5 - 7
Quiz 3 covers lectures 8 - 10
Quiz 4 covers lectures 8 - 13
Thus, Quiz 3 and 4 cover a lot of overlapping material.

Course Project

The Course Project is an opportunity to demonstrate the skills you have learned during the course. It is graded through peer assessment.

Grading policy

You must score at least 80% on all assignments (Quizzes & Project) to pass the course.

Your final grade will be calculated as follows:

Quiz 1 = 15%
Quiz 2 = 15%
Quiz 3 = 15%
Quiz 4 = 15%
Course project = 40%
Homework

There is some optional homework that can be accessed here. More information can be found in the navbar homework tab. These exercises are optional and perhaps a little more difficult than the quizzes. They also may not exactly correspond to the quiz and lecture schedules.

Differences of opinion

Keep in mind that currently data analysis is as much art as it is science - so we may have a difference of opinion - and that is ok! Please refrain from angry, sarcastic, or abusive comments on the message boards. Our goal is to create a supportive community that helps the learning of all students, from the most advanced to those who are just seeing this material for the first time.

Plagiarism

Johns Hopkins University defines plagiarism as "...taking for one's own use the words, ideas, concepts or data of another without proper attribution. Plagiarism includes both direct use or paraphrasing of the words, thoughts, or concepts of another without proper attribution." We take plagiarism very seriously, as does Johns Hopkins University.

We recognize that many students may not have a clear understanding of what plagiarism is or why it is wrong. Please see the following guide for more information on plagiarism:

http://www.jhsph.edu/academics/degree-programs/master-of-public-health/current-students/JHSPH-StudentReferencing_handbook.pdf

It is critically important that you give people/sources credit when you use their words or ideas. If you do not give proper credit -- particularly when quoting directly from a source -- you violate the trust of your fellow students.

The Coursera Honor code includes an explicit statement about plagiarism:

I will register for only one account. My answers to homework, quizzes and exams will be my own work (except for assignments that explicitly permit collaboration). I will not make solutions to homework, quizzes or exams available to anyone else. This includes both solutions written by me, as well as any official solutions provided by the course staff. I will not engage in any other activities that will dishonestly improve my results or dishonestly improve/hurt the results of others.

Reporting plagiarism on course projects

One of the criteria in the project rubric focuses on plagiarism. Keep in mind that some components of the projects will be very similar across terms and so answers that appear similar may be honest coincidences. However, we would appreciate if you do a basic check for obvious plagiarism and report it during your peer assessment phase.

It is currently very difficult to prove or disprove a charge of plagiarism in the MOOC peer assessment setting. We are not in a position to evaluate whether or not a submission actually constitutes plagiarism, and we will not be able to entertain appeals or to alter any grades that have been assigned through the peer evaluation system.

But if you take the time to report suspected plagiarism, this will help us to understand the extent of the problem and work with Coursera to address critical issues with the current system.

I'm glad that you decided to take Statistical Inference, part of the Data Science Specialization from Johns Hopkins Biostatistics! This course presents the fundamentals of statistical inference that you will need throughout the rest of the Data Science track. We believe that the key word in Data Science is "science".

This Specialization is focused on providing you with three things: (1) an introduction to the key ideas behind working with data in a scientific way that will produce new and reproducible insight, (2) an introduction to the tools that will allow you to execute on a data analytic strategy, from raw data in a database to a completed report with interactive graphics, and (3) on giving you plenty of hands-on practice so you can learn the techniques for yourself. This course represents the most fundamental and foundational component of the series. Using only a bare minimum of mathematics, we attempt to give students the fundamentals of using statistics to draw inferences about populations.

We are excited about the opportunity to attempt to scale Data Science education. We intend for the courses to be self-contained, fast-paced, and interactive.

A couple of first week housekeeping items. First, make sure that you've had R Programming and the Data Scientist's Toolbox before taking this class. At a minimum you must know: very basic git and basic R.

An important aspect of this class is to peruse the materials in the github repository. All of the most up to date material can be found here

https://github.com/bcaffo/courses/tree/master/06_StatisticalInference

You should clone this repository as your first step in this class and make sure to fetch updates periodically. (Please send pull requests too!) It is one of the most essential components of the Specialization that you start to use Git frequently. We're practicing what we preach as well by using the tools in the series to create the series, especially git.

You can clone the whole repo with (http)

git clone https://github.com/bcaffo/courses.git

or (ssh)

git clone git@github.com:bcaffo/courses.git

The lectures are in the index.Rmd lecture files. In Data Products, we'll cover how to create these sorts of slides. However, for the time being, you should be able to open them in R Studio and look at their contents. You will see all of the R code to recreate the lectures. Going through the R code is the best way to familiarize yourself with the lecture materials.

If you'd prefer to watch the videos on YouTube, the current version of the class is here: https://www.youtube.com/playlist?list=PLpl-gQkQivXiBmGyzLrUjzsblmQsLtkzJ

If you'd like to keep up with the instructors, I'm @bcaffo on twitter, Roger is @rdpeng and Jeff is @jtleek. The Department of Biostat here is @jhubiostat.
