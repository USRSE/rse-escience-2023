---
layout: page
title: Workshop Abstracts
description: Workshop Abstracts
permalink: /abstracts/
---

## Talks

### Benefits and Limitations of Jupyter-based Scientific Web Applications

*Nicole Brewer, Rob Campbell, Rajesh Kalyanam, I Luk Kim, and Carol X. Song*

Scientists are increasingly interested in creating standalone web-applications
as computational and data analysis tools. The authors have worked with several
such research groups to design, develop, and deploy such web applications that
are increasingly based on Jupyter notebooks. One of the primary reasons among
many to use Jupyter notebooks is the fact that research groups inheriting these
applications are capable of maintaining and extending them. In this paper, we
walk through the design process for one such application and discuss 
development environments that are best suited to Jupyter notebook development.
We then explore several other applications where we employ similar design
patterns. In doing so, we expound upon the benefits, limitations, and
challenges of Notebook-based applications to provide a guide for other
facilitators in similar situations.

[Presentation](/assets/files/BenefitsandLimitationsofJupyterbasedWebApps.pdf)

---

### Roles of Professional Research Software Engineers in the Science Gateway Landscape

*Sandra Gesing*

Science gateways are increasingly used by researchers and educators evident
in publications and presentations at events such as eScience and PEARC. Teams
around science gateway development are diverse and need a diverse set of
expertise. Skills needed are around developing and/or extending a science
gateway framework with backend connections to complex research infrastructure
or lab instruments, enabling collaboration with authentication and
authorization mechanism as well as addressing FAIR (Findable, Accessible,
Interoperable, Reusable) principles. One of the most important aspects are the
needs of the specific community for each science gateway on features and
user interface. 

[Presentation](/assets/files/GesingeScienceRSE2022RolesofProfessionalResearchSoftwareEngineers.pdf)

---

### Half-Precision Scalar Support in Kokkos and Kokkos Kernels: An Engineering Study and Experience Report

*Evan Harvey, Reed Milewicz, Christian Trott, Luc Berger-Vergiat, and Siva Rajamanickam*

To keep pace with the demand for innovation through scientific computing,
modern scientific software development is increasingly reliant upon a rich
and diverse ecosystem of software libraries and toolchains. Research software
engineers (RSEs) responsible for that infrastructure perform highly 
integrative work, acting as a bridge between the hardware, the needs of
researchers, and the software layers situated between them; relatively little,
however, has been written about the role played by RSEs in that work and what
support they need to thrive.

To that end, we present a two-part report on the development of half-precision
floating point support in the Kokkos Ecosystem. Half-precision computation is
a promising strategy for increasing performance in numerical computing and
is particularly attractive for emerging application areas (e.g., machine
learning), but developing practicable, portable, and user-friendly abstractions
is a nontrivial task. In the first half of the paper, we conduct an engineering
study on the technical implementation of the Kokkos half-precision scalar
feature and showcase experimental results; in the second half, we offer an
experience report on the challenges and lessons learned during feature
development by the first author. We hope our study provides a holistic
view on scientific library development and surfaces opportunities for future
studies into effective strategies for RSEs.

[Presentation](/assets/files/FY23Q1_RSEWorkshop_halfPrecisionReport.pdf)

---

### How to Grow Diverse and Sustainable Teams through Mentorship

*Caleb Jackson*

The chief question I will address is: in a sea of open-source
projects, how might mid- or senior-level developers best mentor early career
developers? As a software engineering apprentice, I have had the unique
experience of swimming through open-source projects and ultimately finding
tech spaces that align with my values (open science and collaboration) and
interests (biochemistry and neuroscience). During this transition time,
mentorship played a crucial role in making this happen!

So often, tech spaces lack diversity, and when they are open to individuals
from different backgrounds, these spaces do not feel safe. This makes the need
for identity-related support evident. My talk highlights the importance of
effective and empathetic mentorship and best mentorship practices for mentoring
those with different identities from the mentee's perspective. As a Black
trans person, I was initially hesitant to be mentored by a white person because
sharing one's interests and admitting to not knowing where to begin felt
vulnerable. During my talk, I plan to briefly share my story detailing how my
mentor and I cultivated trust. This talk also provides solutions for growing
diverse and sustainable teams where trust, learning, and experimentation are
encouraged! I'll pinpoint the strategies my mentor and I utilized over those
six months and have continued to use to this day.

This talk is necessary for anyone interested in gaining more effective
mentorship strategies as they guide individuals with different identities and
for any mentees, like me, interested in advice on navigating mentor/mentee
relationships. You don't necessarily need to hold the title of "mentor" to
utilize these strategies; most folks in this field guide others in some
capacity. All in all, I aim to show how mentorship plays a crucial role in
growing diverse and sustainable teams within the workplace. 

[Presentation](/assets/files/mentorship_eScience_2022.pdf)

---

### Best practices and Learned Lessons in Refactoring Researcher-Developed Statistical R Packages

*Naeem Khoshnevis and Mahmood Mohammadi Shad*

We present two years of faced challenges and success stories of collaboration
with biostatisticians. Research software engineering is a relatively new
career field, and the structure, responsibilities, evaluation metrics, and
collaboration boundaries are not firmly defined. All of these can build
unreasonable expectations and can negatively affect both researchers and RSEs.
The best practices and faced challenges discussed here can be an excellent
heuristic for the current RSEs to improve productivity and give a better
picture for the potential RSEs on what to expect. We discuss the followed
software engineering best practices and learned lessons, including unit
testing, functional testing, Continues Integration, documentation for users
and developers, containerizing development environment, and practical use of
version control systems. We also discuss requirements for addressing different
types of projects based on the maturity of the research (completed, in
progress, not started). Efficient communication is an essential part of the
collaboration, which can include a broad spectrum of researchers (from
undergraduate students to a well-established PI). We discuss the best practices
for communication and how provide tips on how to prepare good documentation
and test cases.

Our two years' experience shows how taking care of small, yet important
details can help researchers and RSEs in building sustainable and better
scientific software. 

[Presentation](/assets/files/Naeem_KH_Mahmood_MShad_eScience_2022.pdf)
