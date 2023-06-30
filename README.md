# webworkBDH
WeBWorK exercises for Blanchard, Devaney, and Hall's "Differential Equations" textbook. Used in 2022-23 at the University of St. Thomas in St. Paul, MN (USA). Everything authored by Thomas Höft. Used by ~130 students with two semesters of typo-finding, but there's certainly typos remaining...

Folders have textbook exercises & support files. The setDefs folder has assignment definitions for quick-and-dirty setup of a webwork course, and mirrors what I used in Spring 2023 -- see courseSchedule.pdf. The numerical methods exercises reference a webpage and sagemath cell maintained by me -- I make no guarantees that this will remain stable. See webworkBDH.pdf for a human-readable transcript of the exercises.

I used a fairly vanilla webwork AWS server, except for the following: 
to fix LaTeX hardcopy from barfing on unicode infinity, added
`\DeclareUnicodeCharacter{221E}{$\infty$}  
%%%  
to  
/opt/webwork/webwork2/conf/snippets/hardcopyPreamble.tex  
and  
/opt/webwork/webwork2/conf/snippets/hardcopyThemes/oneColumn/hardcopyPreamble.tex`  

Questions/comments/concerns contact hoft@stthomas.edu (Thomas Höft).
