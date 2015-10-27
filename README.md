# CMPS290S-Winter16: distributed storage systems and programming models
| key | value | 
|-----|-------|
|When: | Tuesdays and Thursdays at 1PM. |
|Where: | ?? |
|Who: | Peter Alvaro |
|Prerequisites: | Systems background |

# Description

This graduate seminar will explore distributed systems research, both current and historical, with a particular focus on storage systems and programming models.

Due to fundamental uncertainty in their executions arising from asynchronous communication and partial failure, distributed systems present unique challenges to programmers and users.  Moreover, distributed systems are increasingly ubiquitous: nearly all non-trivial systems are now physically distributed.  It is no longer possible to relegate responsibility for managing the complexity of distributed systems to a group of expert library or infrastructure writers: all programmers must now be distributed programmers. This is both a crisis and an opportunity.

A great deal of theoretical work in distributed systems establishes important impossibility results, including the famous FLP result, the CAP Theorem, the two generals problem and the impossibility of establishing common knowledge via protocol.  These results tell us what we *cannot* achieve in a distributed system, or more constructively, they tell us about the properties we must trade off for the properties we require when designing or using large-scale systems.  But what *can* we achieve?  The history of applied distributed systems work is largely the history of infrastructures -- storage systems as well as programming models -- that attempt to manage the complexity with abstractions.  

This course focuses on these systems, models and languages.  We will cover the following topics:
 
 * Consistency models
 * Fault-tolerant design
 * Issues related to programmability
 * 
 
# Readings

This course is a research seminar: we will focus primarily on reading and discussion conference papers.  We will read 1-2 papers (typically 2) per session; for each paper, you will provide a brief summary (about 1 page).  The summary should answer some or all of the following questions:

 * What problem does the paper solve?  Is is important?
 * How does it solve the problem? 
 * What alternative approaches are there? Are they adequately discussed in the reading?
 * What research questions does the paper raise?
 * 
 
# Presentations

All students will be expected to present at least two research papers to the class.  The presentation format is open: students will not be required to prepare slides (though doing so may help to organize the subject matter).  If you do use slides, they should be original (created by you), and external material such as figures should be properly attributed.  If you choose not to present slides, use the whiteboard well.


# Final Project

Students must submit a final project related to distributed storage systems and/or programming models.  Projects can be of one of two kinds:

 * Research projects, which present novel research that could (eventually) lead to a conference or workshop publication.  I strongly encourage you to do a project of this kind; after all, research is what we are here to do.  Systems research is challenging and quarters are short, so students may work in teams of up to three people.  Note however that the number of contributors will be considered when the projects are graded.  A team of three can and should take on a substantially more ambitious problem than a team of two or one.
 * Survey papers, which attempt to provide a complete picture of work in a narrow area.  Survey papers may only have one author.  Needless to say, they should not cover material already covered in class.
 
Re-submitting a paper already submitted in any form to a class from a previous semester is not allowed.  Submitting a paper concurrently to another class is allowed only with pre-approval from the instructor.  In such cases, as with group papers, I expect the work to be exceptionally strong.



