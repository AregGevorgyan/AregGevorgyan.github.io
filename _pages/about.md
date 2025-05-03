---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my personal page, you can find my contact information on the side bar and my CV at the top. My contact information is listed on the left, the fastest way to reach me is by email. Scroll down to learn more about me and my projects.

I am a first year undergraduate student at the University of Maryland, College Park pursuing a double degree in Mathematics and Computer Science. I am interested in both the theoretical aspects of research and the practical applications in industry. I am currently looking for opportunities for this summer, please reach out if you believe I am a fit for a position you may have available.

# Skills
## Programming Languages
- Python (5 years), C/C++ (2 years), Java (3 years), MATLAB (2 years), C# (1 year), JavaScript (2 years) LaTeX (3 years), GAS (x86) Assembly

## Software
- Pandas (4 years), NumPy (4 years), SciPy (4 years), PyTorch (2 years), Bash (1 year), Git (1 year), JAX (1 year)
## Soft Skills
- Leadership, Teamwork, Communication, Problem Solving
# About Me

I grew up in an immigrant family where education was highly valued and I saw firsthand how hard work and determination can change one’s life. Beyond changing one’s life, I am also inspired by how hard work and determination can also be used to change the lives of many others and bring value to others. It is my mission to change the world through projects, work, and research. Every day I strive to live the best and most impactful version of my life through my projects, work, and research. 

I have an intellectual passion in mathematics and computer science for both the beauty in their pure study and their applications in every corner of the world. My interest in mathematics started at an early age for all applications it brought, and lasted through the years for its beauty in abstraction. I later became fascinated with computer science for the power it gives in computing math and the wide ranging applications it has. My projects, research, and work, whether through result or through the process of developing them, rely on the interplay between computer science and mathematics. 

My primary interests currently center around machine learning and algorithms as they embody the reasons I like mathematics and computer science with theoretical research having a very short turnaround time to practical applications that are highly impactful. My academic and research work aims to explore these fields theoretically, while my projects and work aims to bring value to others with that experience.

# Education

University of Maryland, College Park, B.S. Computer Science, B.S. Mathematics

- August 2024 to expected May 2028

*Relevant Coursework*: Computer Systems, Probability Theory, Mathematical Statistics, Linear Algebra (proof based), Differential Equations (proof based), Multivariable Calculus (proof based), Discrete Mathematics.

I am currently a junior by credits and in the University Honors program where I explore how my studies play a role in a border context, such as societal impacts of artificial intelligence.

My involvements on campus include:

- Machine learning research project in the works for training efficient text embedding models

- Member of the competitive programing club where I apply algorithmic problem solving to implement maximally efficient C++ code to solve a problem

- Member of the Apex fund, a student run quantitative fund, where I am developing an open source financial model backtesting framework called Hindsight, found below

# Experience

Visual Reality Development Intern, Earth System Science Interdisciplinary Center, University of Maryland, College Park

- Utilized C#, Unity, Git, and Blender to develop a VR application to educate the public about types of lightning.

- My project was presented at the American Geophysical Union conference and won a best presentation award at the internship

# Projects

## [Hicruit.us](https://hicruit.us/)

Python

AI powered recruiting platform that automatically calls candidates for 10 minute screening interviews. This website was built with my team during the 2025 Hoya Hacks Hackathon at Georgetown with my team. I was primarily responsible for developing the backend code that is responsible for the AI integration which makes the phone calls work. 

I developed the backend code in Python using libraries and integrated several AI models to make the system work. The program utilizes voice activity detection (VAD) model to determine whose turn it is to speak, speech to text to translate the recipient's speech into text that can be processed, Google Gemini AI model to analyse and generate output, and text to speech to generate the final output. The code was especially challenging since I had to make several models work together efficiently enough such that the latency is not noticeable. To solve this I put in long hours of testing to ensure the code works properly. On top of this we faced issues where the AI interviewer was judging candidates harshly or not asking relevant questions which involved more prompting to prevent. 

## [Hindsight](https://github.com/Suchismit4/hindsight/tree/main)

Python, JAX, Pandas, NumPy, Xarray

This project is an open source Python library that facilitates backtesting of financial models using past data. The project is being developed with another undergraduate student and a finance professor and will later be used to backtest popular models in finance literature. While there were existing options, they lacked the customizability and performance we desired for our research, so we went the route of creating our own. 

My responsibility was creating the data loaders to import data from the WRDS data set into our Xarray format. I am also responsible for creating the abstract syntax tree that will allow us to define models as equations instead of code. This involved architecting the software, determining what level of abstraction the code should be written at to allow for future additions, and converting from models written in other languages to our library. The main challenges that I faced were around compatibility with the many libraries and formats we are translating between to make the library work. Solving the problems required many hours of debugging and testing until the code worked as expected.

## [M3 Math Modeling Challenge Solution: Modeling Homelessness in American Cities](https://areggevorgyan.github.io/files/M3_Math_Modeling_2024.pdf)

In fall of 2024, I lead a team of four other students in the M3 Math Modeling Challenge to produce a recommendation report for the Secretary of Department of Housing and Urban Development. The report provided a plan for dealing with the homelessness crisis in American cities backed with mathematical modeling from past data.

The paper consisted of three parts where the cities of Seattle, Washington and Albuquerque, New Mexico were used as sample cities to model national trends. For the first part we used an auto-regressive integrated moving average (ARIMA) model to predict the changes in housing supply for fixed time intervals in those cities. For the second part, we used multiple linear regression to forecast the changes in homelessness in those cities. For the third part, we used a monte carlo simulation to determine which variables are the most important and how adaptable our model is to unforeseen circumstances. The challenge also involved coming up with essential assumptions to simplify the problem and sensitivity analysis of our solutions. All the computations were done using Python and common data science libraries.

The paper was a collaborative effort that I initiated and coordinated involving weeks of preparation and 14 hours straight of work during the challenge window to produce our solution. This challenge provided an opportunity to apply my mathematical skills along with my computational skills to bring the math to reality on a real world problem that can benefit society. My team’s solution scored in the top 20% of submission in 2024.