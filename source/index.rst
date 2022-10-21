.. figure:: img/Spatial-analytics-logo.png

**Spatial analytics** -course introduces you to different analysis approaches and methods of spatio-statistical analysis, geostatistics, map algebra
and geovisual analysis. After the course, you can identify appropriate analysis approaches for different geospatial tasks,
and describe data needs and suitable methods for the given analysis process. You can discuss the strengths and limitations of the methods.
The course has been developed at the Department of Built Environment, Aalto University, Finland, and the materials are openly available for anyone interested.

Learning objectives
-------------------

After completing this course, you should:

- understand the typical data analysis workflow
- understand the basics of geostatistics and the associated terminology and mathematical principles
- understand the basic principles of map overlay and map algebra
- understand the principles of graph theory and network analysis
- understand the basic principles of spatio-temporal multivariate analysis
- be able to apply the previous concepts to different geographical problems using Python programming language

Prerequirements
---------------

Before taking this course, it is required to know the basics of Python programming as well as GIS.
If you are new to Python, or would like to refresh your Python skills, we recommend to start with an online
and open access course called Geo-Python which is available at `geo-python.github.io <http://geo-python.github.io/>`__.
If you need to refresh your Python GIS skills, we recommend starting with a course Automating GIS-processes available
at `autogis.github.io <https://autogis.github.io/>`__. Both of these courses include tutorials, videos and exercises.


.. admonition:: Help improving the materials

    **This is version 2.**

    The course was given for the very first time in its current form in 2021, meaning that the content of the course is likely to change and
    improve after each time the course is given (all versions will be available). By being a fully open
    educational resource, **you can also help making the course better**.
    If you find any errors, typos, or other problems, please help, by suggesting an edit in GitHub. You can do this easily by clicking
    ``suggest edit`` under the GitHub icon located at
    the top-right on each page:

    .. image:: img/suggest_edit.png
       :width: 130px

    |
    If you have good ideas about what should be taught, i.e. what methods, interesting datasets or literature should be introduced
    during the course, you can suggest and bring your ideas forward by `raising an issue in GitHub <https://github.com/AaltoGIS/Spatial-Analytics/issues/new>`__.

.. admonition:: Credits

    This course was originally developed by **Prof. Kirsi Virrantaus** at Aalto University, who has very much inspired how it is taught in its current form.
    Also Marko Kallio, Jaakko Madetoja and Salla Multimäki have contributed to the materials and exercises.
    Here, the materials are somewhat updated, restructured and aligned to work with Python spatial data science ecosystem,
    and the online learning ecosystem used in the course.


Course format
-------------

The majority of this course will be spent in front of a computer writing code with the Python language.
The course consists of lectures, tutorials and weekly exercises. The exercises will focus on
applying the introduced methods to given geographical problems.

Most exercises in this course involve real world examples and data. For each exercise, you may be asked to
submit the Python codes you have written, output figures and answers to related questions. You are encouraged to
discuss and work together with other students while working on the weekly exercises.

.. admonition:: Aalto University students

    The Spatial Analytics -course is part of the
    `Master's Programme of Geoinformatics at Aalto University <https://www.aalto.fi/en/study-options/masters-programme-in-geoinformatics>`__
    under the course code ``GIS-E1060``.

.. admonition:: Interactive contents

    Each tutorial in this course can be turned into an interactive programming session in the browser.
    You can find buttons for activating the python environment using `Binder <https://mybinder.readthedocs.io/en/latest/>`__ at the top of each programming lesson.
    Students at Finnish higher education institutions are encouraged to use the `CSC notebooks <https://notebooks.csc.fi/>`__ environment.

.. admonition:: Online teaching

    Please note that the course is organized completely online during the 2021 Fall semester.
    Access to zoom, slack and CSC notebooks is available to students at Finnish higher education institutes.

Program
-------

The course includes two lectures per week and is held at the Aalto University starting on Tuesday in the second teaching period.
Topics per Lesson are listed below. Please note that this web page is updated each week before the given lesson:

.. list-table::
    :widths: 1 8
    :header-rows: 1
    :stub-columns: 1
    :align: left

    * - Lesson
      - Themes
    * - 1
      - - Course overview and practicalities
        - Introduction to spatial analysis
        - Point pattern analysis
    * - 2
      - - Spatial autocorrelation
        - Git+Python tutorials
    * - 3
      - - Analysis of spatial field data
    * - 4
      - - Geostatistics: Interpolation (IDW+Kriging)
    * - 5
      - - Map overlay & algebra
    * - 6
      - - Spatial network analysis
    * - 7
      - - Spatial networks: Optimization & centrality
    * - 8
      - - Multivariate spatial analysis
    * - 9
      - - Visual analytics
|

Contents
--------

.. toctree::
    :maxdepth: 1
    :caption: Course information

    course-info/introduction
    course-info/course-info
    course-info/learning-goals
    course-info/resources
    course-info/grading
    course-info/course-environment-components
    course-info/slack-usage
    course-info/License-terms
    course-info/attribution

.. toctree::
    :maxdepth: 1
    :caption: Week 1

    lessons/L1/overview
    lessons/L1/introduction-to-spatial-analysis
    lessons/L1/point-pattern-analysis

..
    lessons/L1/spatial-autocorrelation
    lessons/L1/git-basics
    lessons/L1/intro-to-python-geostack.ipynb
    lessons/L1/exercise-1


    .. toctree::
        :maxdepth: 1
        :caption: Week 2

        lessons/L2/overview
        lessons/L2/analysis-of-spatial-field-data
        lessons/L2/geostatistics-kriging.rst
        lessons/L2/exercise-2

    .. toctree::
        :maxdepth: 1
        :caption: Week 3

        lessons/L3/overview
        lessons/L3/map-overlay
        lessons/L3/spatial-network-analysis
        lessons/L3/exercise-3

    .. toctree::
        :maxdepth: 1
        :caption: Week 4

        lessons/L4/overview
        lessons/L4/spatial-network-optimization-centrality
        lessons/L4/multivariate-spatial-analysis
        lessons/L4/exercise-4

    .. toctree::
        :maxdepth: 1
        :caption: Week 5

        lessons/L5/overview
        lessons/L5/visual-analytics

