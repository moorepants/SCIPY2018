Instructions
============

https://scipy2018.scipy.org/ehome/299527/648140/

Title
=====

Resonance: Learning Mechanical Vibrations Through Computational Thinking

The Short Description
=====================

*The brief description which will appear in the online program and give
attendees a basic sense of your talk. This should be around 100 words or less.*

I will describe a pilot project at the University of California, Davis on the
redesign of an upper level mechanical vibrations engineering course where
students now learn the relevant concepts via computational thinking and
computational experimentation. We utilize interactive computing with the
Jupyter platform and a custom Python library instead of focusing on the
analytical mathematical methods used over the past century. I will cover the
course design, principles of teaching and learning with computational thinking
(focusing on API design and the use of symbolics), software/hardware
infrastructure, assessment practices, and lessons learned.

The Long Description
====================

*Your placement in the program will be based on reviews of your detailed
description. This should be a roughly 500 word detailed outline of your
presentation. This outline should concisely describe software of interest to
the SciPy community, tools or techniques for more effective computing, or how
scientific Python was applied to solve a research problem. A traditional
background/motivation, methods, results, and conclusion structure is encouraged
but not required. Links to project websites, source code repositories, figures,
full papers, and evidence of public speaking ability are encouraged.*

The topic of "mechanical vibrations" has a long history in mechanical
engineering curricula, codified almost 100 years ago with J. P. Den Hartog's
seminal text on the subject. Mechanical vibrations has typically been taught
with most of the focus on reasoning via the analytic study of linear ordinary
differential equations that arise from Newton's Laws of Motion. And for the
last 30 years, computation has more often than not complemented the analytics
usually as addenda in a variety of textbooks.

We decided to implement a number of changes focused around computational
thinking being the primary conceptual reasoning tool in the course. We
hypothesize this improves learning and provides modern practical skills to the
students. The primary goals were to:

- motivate the learning via real vibration problems,
- increase the amount of exposure to vibration design,
- increase the likelihood that students will put computation on equal footing
  as other common engineering problem solving tools when finished with at
  Bachelor's degree, and
- remove the need for students to purchase a costly printed oversized
  traditional textbook.

To meet these goals, we made these changes to the course:

- Ordered the material delivery such that students first learn to analyze data
  from real systems, then learn to model and simulate those systems, and close
  with students learning design by example.
- De-emphasis and removal of the analytic study of ordinary differential
  equations and replacement with both data analysis and simulation based
  methods for learning vibrational concepts.
- Replace most in-class "board lecturing" with active computational exercises.
- Development of tightly scoped, open access, interactive text that accompanies
  the course using Jupyter notebooks.
- Development of a Python software package designed specifically for ease of
  learning vibrational concepts that assumes no prior Python knowledge and
  scaffolds the exposure to new computation methods as the course progresses.
- Removal of exams and the introduction of open ended problems in weekly
  homeworks and a comprehensive course project.

I will cover each of these and show how Python is essential in executing the
changes. The introduced methods will be presented in a general context so that
other educators can make use of them in other STEM domains. Finally, I will
close with reflections on what the next steps are in course and curricula
design.

Relevant Links
--------------

- Course Website: https://moorepants.github.io/eng122
- Resonance Book Draft: https://moorepants.github.io/resonance
- Resonance Software and Book Source: https://github.com/moorepants/resonance

Evidence of Public Speaking
---------------------------

I have given 30+ talks at a variety of academic conferences, given talks and
tutorials and prior SciPy and PyCon conferences, and teach six courses to 200+
students each year in my day job.
