Awesome Motion Planning
=======================

[![Join the chat at https://gitter.im/AGV-IIT-KGP/awesome-motion-planning](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/AGV-IIT-KGP/awesome-motion-planning?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

An attempt to collect a curated list of awesome learning resources, research
papers, tools and other resources related to Motion Planning. This is inpired from
several such lists in programming community.

If you want to contribute to this list (please do), [send a pull
request](https://github.com/AGV-IIT-KGP/awesome-motion-planning/compare/),
[open an
issue](https://github.com/AGV-IIT-KGP/awesome-motion-planning/issues/new) When
sending suggestions please add a short blurb/description about each book that
you have personally read/benefited from. Feel free to debate quality, headings,
etc.  irrespective of any particular field or subject area.

All the resources need not be freely available for download.


Blogs and Tutorials
-------------------

* [Introduction to A-star](http://theory.stanford.edu/~amitp/GameProgramming/AStarComparison.html)
* [Toward More Realistic Pathfinding](http://www.gamasutra.com/view/feature/131505/toward_more_realistic_pathfinding.php)
* [Overview of Motion Planning](http://www.gamasutra.com/blogs/MattKlingensmith/20130907/199787/Overview_of_Motion_Planning.php)
* [A* Path Finding for Beginners](http://www.policyalmanac.org/games/aStarTutorial.htm) By Patrick Lester
* [Hybrid A* Implementation](http://blog.habrador.com/2015/11/explaining-hybrid-star-pathfinding.html)
* [Dubins Path](https://gieseanw.wordpress.com/2012/10/21/a-comprehensive-step-by-step-tutorial-to-computing-dubins-paths/)

Books
------

* [Planning Algorithms](http://msl.cs.uiuc.edu/planning/index.html) By Steven M. LaValle
* [Robot Motion Planning](http://www.springer.com/engineering/robotics/book/978-0-7923-9129-6) By Jean-Claude Latombe
* [Autonomus Robots: Modeling, Path Planning, and Control](http://books.google.co.in/books?id=s7-4g1wcp8MC&lpg=PA13&dq=robot%20%2B%20planning%20%2B%20feedback%20control&pg=PR4#v=onepage&q&f=false) by Farbod Fahimi
* [Principles of Robot Motion](http://mitpress.mit.edu/books/principles-robot-motion) By Howie Choset, Kevin M. Lynch, Seth Hutchinson, George A. Kantor, Wolfram Burgard, Lydia E. Kavraki and Sebastian Thrun

Papers
------

* [Randomized Kinodynamic Planning](http://ijr.sagepub.com/content/20/5/378.full.pdf+html) by Steven M. LaValle and James J. Kuffner, 
* [Limited-Damage A*: A path search algorithm that considers damage as a feasibility criterion](http://www.sciencedirect.com/science/article/pii/S0950705110001905) by Serhat Bayili, Faruk Polat
* [Real Time Continuous Curvature Path Planner for an Autonomous Vehicle in an Urban Environment](http://cs.stanford.edu/people/davidknowles/knowles-surf06.pdf) by David Knowles
* [An Evolutionary Artificial Potential Field Algorithm for Dynamic Path Planning of Mobile Robot](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=4058914&tag=1) by Cao Qixin, Huang Yanwen, Zhou Jingliang
* [Planning continuous-curvature paths for car-like robots](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=568985) by Scheuer A, Fraichard T
* [Optimal and Efficient Path Planning for Partially-Known Environments](http://link.springer.com/chapter/10.1007%2F978-1-4615-6325-9_11) by Anthony Stentz
* [An Introduction to the Conjugate Gradient Method Without the Agonizing Pain](http://www.cs.cmu.edu/~quake-papers/painless-conjugate-gradient.pdf) by Jonathan Richard Shewchuk
* [Practical search techniques in path planning for autonomous driving](http://ai.stanford.edu/~ddolgov/papers/dolgov_gpp_stair08.pdf)
* [Junior The Stanford entry in the urban challenge](http://robots.stanford.edu/papers/junior08.pdf)


### Heuristic Search

* [A Formal Basis for the Heuristic Determination of Minimum Cost Paths](http://ai.stanford.edu/~nilsson/OnlinePubs-Nils/PublishedPapers/astar.pdf) - The original A* paper. Introduces the ideas of consistency and admissibility. Also has proofs for the optimality of A*.
* [On the complexity of Admissible Search Algorithms](http://www.sciencedirect.com/science/article/pii/0004370277900029) - A* has worst-case performance with an admisible by inconsistent heuristic. This algorithm deals with such heuristics and improves the worst-case performance.
* [A Heuristic Search Algorithm with Modifiable Estimate](http://www.sciencedirect.com/science/article/pii/0004370284900031) - Most algorithms derived from A* consider the heuristic cost h(s) to be a constant. This is the first algorithm that treats the heuristic cost as a variable and improves it during search whenever possible. The paper also has an influential proof of a result that says that no overall optimal algorithm exits if the cost of an algorithm is measured by the total number of node expansions.

Lecture Notes
------------

* [Robot Motion Planning Lectures](http://www.cs.cmu.edu/~motionplanning/lecture/lecture.html) By Howie Choset.
* [Planning and Decision Making in Robotics](https://www.cs.cmu.edu/~maxim/classes/robotplanning_grad/) By Maxim Likhachev.

Software Packages and Libraries
-------------------------------

* [OMPL](http://ompl.kavrakilab.org/): Sampling based planning
* [SBPL](https://github.com/sbpl/sbpl): Heuristic search based planning
* [SMPL](https://github.com/aurone/smpl): Heuristic search based planning for manipulators