:author: Stéfan van der Walt
:email: stefan@sun.ac.za
:institution: Stellenbosch University

:author: Jarrod Millman
:email: millman@berkeley.edu
:institution: UC Berkeley

---------
Editorial
---------

.. class:: keywords

    Python, Scientific Computing

Introduction
------------

This is the third publication of a SciPy conference proceedings.  The
aim the proceedings is to increase the visibility of the conference
and the presented work, and to provide academic recognition of the
significant contributions made by the developers of software for
science and engineering.

To ensure the published proceedings are of sufficiently high quality,
we have have instituted a formal review process in which each paper is
reviewed by at least two reviewers according to explicit and uniform
criteria.  To ensure transparency, all reviews are made public. A more
detailed description of the process is given below.

The editors would like to apologise for the late publication of this
year's proceedings, mainly due to the significant time invested in
rewriting the publication framework.  The new framework allows us to
publish future editions much more rapidly, as witnessed by the 2010
and 2011 proceedings seeing the light almost simultaneously.  The
tools used to produce this document are made available under an open
source license, and may be obtained from the code repository at
`https://github.com/scipy/scipy-proceedings
</usr/share/doc/texlive-doc/latex/beamerposter/example.tex>`__.

Growing community
-----------------

This year's conference was attended by 187 participants from both academia and
industry.

SciPy attendees come from far and wide, including North America, Columbia,
Spain, South Africa, Turkey, Germany, Norway, Italy, Singapore and Great
Britain.

Welcome to the proceedings of the 9th Python in Science conference (SciPy2010),
held in Austin, Texas from June 28th to July 3rd 2010.

Since its inception, the conference was held at the California Institute of
Technology, but with Enthought taking a leading role in its organisation, it
made sense to move it to Austin, Texas.  We thank our colleagues and
co-organisers at CalTech for all their support and effort over the past 7
years, and for playing such an integral part in establishing this event.

What started as a small, informal meeting has now become a world-wide series of
conferences, with third EuroSciPy held at the Ecole Normale Supérieure in Paris
from July 8th to the 11th as well as the second SciPy India in Hyderabad, Andra
Pradesh from SciPy.in 2010, December 13th to 18th. 

Conference overview
-------------------

- transitions and maturity theme

Specialized tracks for this year's conference include Python for
Bioinformatics as well as Parallel Processing and Cloud Computing with Python. 

- keynotes

  - Python Concurrency, David Beazley
  - Moving Forward from the Last Decade of SciPy, Travis Oliphant

- major theme:  parallel computing and GPUs

  - tutorials

    - Brian Granger. High Performance & Parallel Computing
      mulitiple libraries: multiprocessing, mpi2py, pyzmq, IPython
    - Andreas Klockner. GPUs and Python: PyCuda, PyOpenCL

  - keynote

    - David Beazley. Python Concurrency

  - general session

    - Theano: Transparent GPU computing
      Bergstra et al.

    - Simple, Fast Messaging in Python with 0MQ and PyZMQ

  - special track: parallel

- minor theme: stat and stat data structure

  - general session

    - statsmodel, seabold
    - pandas, wes mckinney

  - BoF on datarray

  - sprints

    - added tests to scipy.stats
    - preliminary n-dimensional contingency table model w/ tests
    - scipy.stats distributions refactor
    - scikits.learn

- minor theme: astronomy

  - greenfield, aldcroft, morley, allen

- need to highlight a few articles and organize the order of articles and
  explain that organization here

Review and selection process
----------------------------

This year we received
33 abstracts from
... different countries. The submissions covered a number of research fields,
including ....
Moreover, the articles discussed involve a number of computational tools: these
include ...
 
Each abstract was reviewed by both the program chairs as well as
two members of the program committee (PC). The PC consisted of
... members from
... countries, and represented both industry and academia.


Abstracts were evaluated according to the following criteria:
applicability, novelty, and general impression.

We accepted 32 submissions for oral presentation at the
conference. At the end of the conference, we invited the
presenters to submit their work for publication in the
proceedings. These submissions were reviewed by
... proceedings
reviewers from
... countries, according to the following criteria:

Everyone who presented at this year's conference was invited to submit an
article for consideration in the peer-reviewed proceedings. The conference
presentations were selected by a program committee, based on submitted
abstracts and the follow criteria: applicability, novelty, and general
impression. Each abstract was reviewed by at least four reviewers. Of the 32
accepted abstracts, we have 19 submitted papers to review.

The purpose of the conference proceedings is to increase the visibility of the
conference and the presented work, as well as to provide academic recognition
of the significant contributions made by the developers of software for science
and engineering. To ensure the published proceedings are of sufficiently high
quality, we have have instituted a formal review process in which each paper
will be reviewed by at least two reviewers according to explicit and uniform
criteria.

The primary goal of the review process is to provide independent feedback that
guide authors in improving their papers. To review a paper, please complete the
attached review form for each article you review.

Please note that, while reviewers' recommendations regarding a paper's
suitability for publication are seriously considered, the final decision rests
with the proceeding editors.



- open review process
- review template

*GENERAL EVALUATION.* Reviewer's rated each paper using the following
criteria::

  below     doesn't meet standards for
            academic publication
  meets     meets or exceeds the standards
            for academic publication
  n/a       not applicable

- Quality of the approach:

- Quality of the writing:

- Quality of the figures/tables:


*SPECIFIC EVALUATION.*
Reviewers were also asked to provide more specific feedback to the following
questions:

- Is the code made publicly available and does the article sufficiently
  describe how to access it?  We aim not to publish papers that essentially
  advertise propetiary software.  Therefore, if the code is not publicly
  available, please provide a one- to two- sentence response to each of the
  following questions: 

  - Does the article focus on a topic other than the features
    of the software itself?
  - Can the majority of statements made be externally validated
    (i.e., without the use of the software)?
  - Is the information presented of interest to readers other than
    those at whom the software is aimed?
  - Is there any other aspect of the article that would
    justify including it despite the fact that the code
    isn't available?
  - Does the article discuss the reasons the software is closed?
   
- Does the article present the problem in an appropriate context?
  Specifically, does it:
  
  - explain why the problem is important,
  - describe in which situations it arises,
  - outline relevant previous work, 
  - provide background information for non-experts 

- Is the content of the paper accessible to a computational scientist
  with no specific knowledge in the given field?

- Does the paper describe a well-formulated scientific or technical
  achievement?

- Are the technical and scientific decisions well-motivated and
  clearly explained?

- Are the code examples (if any) sound, clear, and well-written?

- Is the paper factual correct?

- Is the language and grammar of sufficient quality?

- Are the conclusions justified?

- Is prior work properly and fully cited?

- Should any part of the article be shortened or expanded? Please explain.

- In your view, is the paper fit for publication in the conference proceedings?
  Please suggest specific improvements and indicate whether you think the
  article needs a significant rewrite (rather than a minor revision).
 
From the
... original abstracts,
... (...%) have been accepted for publication in these proceedings.

----------

A conference the size of SciPy is only possible through hard-work and dedication
of a large number of volunteers.

We would like to thank

  - sponsors
  
    - Enthought
    - PSF
    - Microsoft
    - HP
    - etc...
  
  - local organization
  
    - Leah
    - Amenity
    - etc...

  - participants, authors, reviewers, etc.

Enthought, Dell, Microsoft, D.E. Shaw & Co., AQR Financial Management, the Python Software Foundation, and one anonymous donor, have provided funding for 14 students to travel and attend SciPy 2010.
