---
layout: page
title: "Welcome to Ecological Modeling (BI382) at Colby College"
---

### Course description <small>[download this page as a .pdf](Syllabus.md)</small>
Ecological Modelling is a course that is designed to help students learn theory and methods in mathematical, computational, and statistical ecology. Collectively, these types quantitative approaches are central to the science of ecology for understanding, predicting, and making inferences about ecological patterns and processes. Both classic and contemporary topics will be covered, with an emphasis on using modern tools to analyze and present theory and data.

* Mathematical aspects of the course will cover traditional theory of simple analytical models.
* Computational aspects of the course will cover the implementation and analysis of more complex models
* Statistical aspects of the course will include learning methods of fitting models to data, evaluating competing models given data, and using models to make predictions.



### Learning outcomes
After taking this course as successful student should be:

1. **Versed in elementary mathematical ecology.** Ecological topics include single-species population models, structured population models, spatial models, two-species population models, and multi-species models. Analytical topics include equilibrium, stability, chaos, and stochasticity.
2. **Proficient in the use of the R programming language and environment to build, analyze, and present ecological models.** This includes understanding and use of R data structures, functional programming, libraries for simulation and analysis of ecological models, and dynamic reports/documents using R Notebooks.
3. **Familiar with methods of statistical inference.** This includes least squares and maximum likelihood estimators to fit models to data, and using information criteria for evaluate model fit.

### Professor information
Dr. Christopher M. Moore  
Email: cmmoore  
Office: Olin 216  
Office phone: 207-859-5746  

### Meetings for lectures and labs
Labs: M, 1—4:00 PM, in Olin 314  
Lectures: TR, 9:30—10:45 AM, in Miller 205

### Text
Required: *Population ecology: from first principles*, 2<sup>nd</sup> ed., 2013, by Vandermeer and Goldberg, Princeton University Press  
Optional: *A primer of ecology with R*, 2009, by Stevens, Springer

### Grading


### Attendance
Role will not be taken, but regular attendance is necessary for you to succeed in this course.

### Titles and names
Students are often curious about how to address their professors. I am comfortable with Dr. Moore, Professor Moore, or Chris. What’s most important to me is that we create a culture of mutual respect in the classroom. As a sign of respect to you I will, by default, address you by your first name. Should you have preferred way of being addressed (Mx. last name, nickname, etc.), I encourage your to communicate that to me.


### Academic integrity

Honesty, integrity, and personal responsibility are cornerstones of a Colby education and provide the foundation for scholarly inquiry, intellectual discourse, and an open and welcoming campus community. These values are articulated in the Colby Affirmation and are central to this course. You are expected to demonstrate academic honesty in all aspects of this course. If you are clear about course expectations, give credit to those whose work you rely on, and submit your best work, you are highly unlikely to commit an act of academic dishonesty.

Academic dishonesty includes, but is not limited to: violating clearly stated rules for taking an exam or completing homework; plagiarism (including material from sources without a citation and quotation marks around any borrowed words); claiming another’s work or a modification of another’s work as one’s own; buying or attempting to buy papers or projects for a course; fabricating information or citations; knowingly assisting others in acts of academic dishonesty; misrepresentations to faculty within the context of a course; and submitting the same work, including an essay that you wrote, in more than one course without the permission of the instructors.

Academic dishonesty is a serious offense against the college. Sanctions for academic dishonesty are assigned by an academic review board and may include failure on the assignment, failure in the course, or suspension or expulsion from the College.

### Athletic participation

While Colby College is supportive of athletic participation by its students, academics takes priority over athletics. Both NCAA and Colby rules prohibit missing class for practices. In the case of overlapping commitments between class and athletic competitions, the student must meet with the professor as soon as possible to discuss these overlaps. The student may request permission to miss class and make up the missed work; the instructor has final authority either to grant or to withhold permission

### Sexual misconduct/Title IX statement

Colby College prohibits and will not tolerate sexual misconduct or gender-based discrimination of any kind. Colby is legally obligated to investigate sexual misconduct (including, but not limited to sexual assault and sexual harassment).

If you wish to speak confidentially about an incident of sexual misconduct, please contact Colby Counseling Services (207-859-4490) or the Director of the Gender and Sexual Diversity Program, Emily Schusterbauer (207-859-4093).

Students should be aware that faculty members are considered responsible employees; as such, if you disclose an incident of sexual misconduct to a faculty member, they have an obligation to report it to Colby’s Title IX Coordinator. “Disclosure” may include communication in-person, via email/phone/text, or through class assignments.

To learn more about sexual misconduct or report an incident, visit [http://www.colby.edu/sexualviolence/](http://www.colby.edu/sexualviolence/){:target="_blank"}.

# *All models are wrong, but some are useful* 

{::comment} [//]: [//]: # Dropbox/Projects/dispersing.github.io/Teaching/IntroEco [//]: # pandoc Syllabus.md -f markdown -t html -o Syllabus.html [//]: # pandoc Syllabus.md --latex-engine=xelatex -o Syllabus.pdf [//]: # pandoc Syllabus.md -f markdown -o LaTeX/Syllabus.tex [//]: # pandoc Syllabus.md -f markdown -s -o LaTeX/Syllabus.tex -V geometry:margin=0.5in {:/comment}

Forward modeling: ![alt text](https://imgs.xkcd.com/comics/sustainable.png "Though 100 years is longer than a lot of our resources.")
Forward modeling: ![alt text](https://imgs.xkcd.com/comics/sustainable.png "Though 100 years is longer than a lot of our resources."){:height="50px"}
Forward modeling: ![alt text](https://imgs.xkcd.com/comics/sustainable.png "Though 100 years is longer than a lot of our resources."){:height="50px" width="50px"}

Inverse modeling: ![Inverse modeling](https://imgs.xkcd.com/comics/linear_regression.png "The 95% confidence interval suggests Rexthor's dog could also be a cat, or possibly a teapot.")