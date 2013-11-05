---
layout: post
title: MathsTiles
---

## MathsTiles &mdash; scatterable structured mathematics

circa 2004


MathsTiles let you scatter pieces of mathematics across the page, and piece them together by plugging tiles into sockets. This let students write mathematics that looked more like what they would write on paper, but that behind-the-scenes had enough structure and syntax that it could be checked rigorously.

There were five key benefits we needed from this:

1. It didn't constrain *how* students worked on their mathematics, but let them litter the page with fragments they were playing with. That gave students a lot more freedom to get things wrong and tinker.

2. Although it was an applet (this was 2004), it was scriptable from JavaScript and could also send the changes students made to the server. This meant we could have the student and the server work cooperatively on the same diagram. Not bad, given this was before the term "AJAX" had been coined yet.

3. Tiles themselves were very simple to define in XML. This meant different questions could have different tiles -- for instance, we defined tiles for inductive proofs.

4. It was fairly trivial to translate the tile document into a format that could be checked using all sorts of different systems. In one set of exercises, we had students writing formal proofs using tiles, but being checked by the research-grade theorem prover Isabelle/HOL. But in another set of exercises, we had students constructing wordy arguments, being checked by a little propsitional logic checker we whipped up one Wednesday afternoon.

5. The sockets could be typed. (We used a colour-coding for the types.)


#### Relevant Papers

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

