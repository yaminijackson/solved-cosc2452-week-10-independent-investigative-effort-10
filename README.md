Download Link: https://assignmentchef.com/product/solved-cosc2452-week-10-independent-investigative-effort-10
<br>
<ol>

 <li>This week’s programming task will cover concepts required by Assignment 3. You should aim to get the help of your tutors and make further revisions.</li>

</ol>

<strong>Coding exercise steps (Hint: Need help? Ask your tutor via Canvas→Discussions→”IIE10″):</strong>

Complete the 01/Feb/2021 solution first as this extends upon that work. Next follow Canvas→<a href="https://rmit.instructure.com/courses/70691/modules">Modules→Week 10</a> where the topic of reading from files is covered. <strong>Your tutors will provide further explanations on these general topics and how they relate to this IIE during their weekly “tutor chats”</strong>. Please also follow the announcement ‘<a href="https://rmit.instructure.com/courses/70691/discussion_topics/1039805">How to debug large programs and get help on</a> <a href="https://rmit.instructure.com/courses/70691/discussion_topics/1039805">debugging…</a>’

In this week’s IIE, you will modify <u>your own adaptation</u> of the IIE09 student manager (which has to be different to the student manager) to incorporate file reading in two different ways (steps a and b below) and these must work with both types of interfaces.

<ol>

 <li>At the start of the program, it must silently load records from pre-configured CSV file (without prompting the user). You will need to create some data in an appropriate representation and store it in the file (you can do this using any plain text editor). You can assume that this file name does not change (e.g. students.csv). Tip: Think of where should this code be implemented in the structure we follow in A3 and IIE08+?</li>

 <li>Another way we will allow file loading is via an option on the screen (e.g .a button or a menu item). Here the user should be allowed to specify the file that they want to load. The data from this file must be loaded in addition to any data that is currently in the application. For example, the user might decide to manually open additional .csv files to load additional students. Implement this behaviour, keeping in mind the concepts of reducing duplication, increasing cohesion and reducing of coupling. Tip: Think of where should this code be implemented in the structure we follow in A3 and IIE08+?</li>

 <li>Modify your program so that the filename used in step ‘a’ can be specified/changed without modifying the code or asking the user via the user interface.</li>

</ol>

<em>[Side note: The concepts of packages, polymorphism, inheritance (parent-child/super class-sub class relationships), abstract classes, interfaces, etc. are not covered in Intro To Programming and therefore <u>must not be used</u> in assessments. Subsequent courses such as Programming 1, Further Programming, etc. will cover these in detail.]</em>