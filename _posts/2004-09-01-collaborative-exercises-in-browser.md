---
layout: post
title: Students collaborating with AI on diagram-based exercises in the browser
---

## Students collaborating with AI on diagrams in the browser

circa 2003 - 2007

These were "reactive learning environments", where students would work on a problem in a diagram in the browser, and a server-side reasoning component would collaborate with them. The AI didn't just mark the students' work, but could make its own changes to the diagram while the student was working. 

Whenever the student did something to the diagram, this was sent to the server as a change to a document. The server would then reply with actions that it wanted to perform -- which could include advice, animating explanations on the diagram, and making its own changes to the diagram. This was before the days of AJAX support in browsers, so I like to think this was somewhat ahead of its time.

Students and AI think rather differently. Particularly, an AI's working is often at far too fine a level of detail to be useful to a student. So we modelled the question twice. There was an AI model that was being driven behind the scenes, and the diagram that represented how the student was being asked to think about the problem. This diagram was used as context to "prune" the AI's explanations -- effectively translating between the AI's mental model and the student's mental model.

The fist problem we created was for electronics. Later we wrote cooperative exercises for mathematical proofs -- both formal ones modelled by a theorem prover, and wordy ones modelled by a little propositional logic engine.

#### Relevant papers

* W Billingsley and P Robinson 2007 <br />
  **Student proof exercises using MathsTiles and Isabelle/HOL in an intelligent book** <br />
  *Journal of Automated Reasoning* 39 (2), 181-218 <br />
  <span class="publink"><i class="fa fa-file-text"></i> <a href="http://www.academia.edu/attachments/30479103/download_file">PDF</a></span> 

* W Billingsley and P Robinson 2005 <br />
  **Towards an intelligent online textbook for discrete mathematics** <br />
  *Proceedings of the International Conference on Active Media Technology*, 291-296.<br />
  <span class="publink"><i class="fa fa-file-text"></i> <a href="http://www.academia.edu/attachments/30479105/download_file">PDF</a></span> 

* W Billingsley, P Robinson, M Ashdown and C Hanson 2004 <br />
  **Intelligent Tutoring and Supervised Problem Solving in the Browser**. <br />
  *Proceedings of the IADIS International Conference WWW/Internet*. 806-811 <br />
  <span class="publink"><i class="fa fa-file-text"></i> <a href="http://www.academia.edu/attachments/30479108/download_file">PDF</a></span>

* J Billingsley, W Billingsley 2004 <br />
  **The animation of simulations and tutorial clients for online teaching** <br />
  *Proceedings of the 15th Australasian Conference for the Australasian Association for Engineering Education*, 532-540<br />

* W Billingsley 2007 <br />
  **The Intelligent Book: technologies for intelligent and adaptive textbooks, focussing on Discrete Mathematics** <br />
  PhD Thesis, University of Cambridge. Available as technical report UCAM-CL-TR-719 (2008)<br />
  <span class="publink"><i class="fa fa-file-text"></i> <a href="http://www.academia.edu/attachments/31052164/download_file">PDF</a></span>
