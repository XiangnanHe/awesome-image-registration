image-registration-resources
============================

image registration related books, papers, videos, and toolboxes 


.. image:: https://img.shields.io/github/stars/youngfish42/image-registration-resources.svg?color=orange
   :target: https://github.com/youngfish42/image-registration-resources/stargazers
   :alt: Stars
 

.. image:: https://img.shields.io/badge/%E7%9F%A5%E4%B9%8E-%E5%9B%BE%E5%83%8F%E9%85%8D%E5%87%86%E6%8C%87%E5%8C%97-blue
   :target: https://zhuanlan.zhihu.com/Image-Registration
   :alt: 知乎
 

.. image:: https://awesome.re/badge-flat.svg
   :target: https://awesome.re
   :alt: Awesome


.. image:: https://img.shields.io/github/license/youngfish42/image-registration-resources.svg?color=green
   :target: https://github.com/youngfish42/image-registration-resources/blob/master/LICENSE
   :alt: License
 

Many thanks to  `\ yzhao062 <https://github.com/yzhao062/anomaly-detection-resources/commits?author=yzhao062>`_ `Anomaly Detection Learning Resources <https://github.com/yzhao062/anomaly-detection-resources>`_\ , and I modeled his style to make this depository. 

----

`\ Image registration <https://en.wikipedia.org/wiki/Image_registration>`_ is the process of transforming different sets of data into one coordinate system. Data may be multiple photographs, data from different sensors, times, depths, or viewpoints.

It is used in computer vision, medical imaging, military automatic target recognition, and compiling and analyzing images and data from satellites. Registration is necessary in order to be able to compare or integrate the data obtained from these different measurements. 

This repository collects:


* Books & Academic Papers 
* Online Courses and Videos
* Datasets
* Open-source and Commercial Libraries/Toolkits
* Key Conferences & Journals

**More items will be added to the repository**.
Please feel free to suggest other key resources by opening an issue report,
submitting a pull request, or dropping me an email @ (im.young@foxmail.com).
Enjoy reading!

----

1. Books & Tutorials
--------------------

1.1. Books
^^^^^^^^^^
`Multiple view geometry in computer vision <https://www.robots.ox.ac.uk/~vgg/hzbook/>`_ 
by Richard Hartley and Andrew Zisserman, 2004: Mathematic and geometric basis for 2D-2D and 2D-3D registration. 
A **must-read** for people in the field of registration. `[E-book] <http://cvrs.whu.edu.cn/downloads/ebooks/Multiple%20View%20Geometry%20in%20Computer%20Vision%20(Second%20Edition).pdf>`_

`Computer Vision: A Modern Approach <http://www.informit.com/store/computer-vision-a-modern-approach-9780136085928>`_ 
by David A. Forsyth, Jean Ponce:  for upper-division undergraduate- and graduate-level courses in computer vision found in departments of Computer Science, Computer Engineering and Electrical Engineering.

`Algebra, Topology, Differential Calculus, and Optimization Theory For Computer Science and Engineering <https://www.cis.upenn.edu/~jean/gbooks/geomath.html>`_ By **Jean Gallier and Jocelyn Quaintance**. The latest book from upenn about the algebra and optimization theory.

`14 lectures on visual SLAM <https://github.com/gaoxiang12/slambook>`_ By Xiang Gao and Tao Zhang and Yi Liu and Qinrui Yan.  **SLAM**  `[github] <https://github.com/gaoxiang12/slambook>`_ `[Videos] <https://space.bilibili.com/38737757>`_

`Three-Dimensional Computer vision-A Geometric Viewpoint <https://mitpress.mit.edu/books/three-dimensional-computer-vision>`_  Classical 3D computer vision textbook.

`An invitation to 3D vision <https://www.eecis.udel.edu/~cer/arv/readings/old_mkss.pdf>`_ a self-contained introduction to the geometry of three-dimensional (3- D) vision.

1.2. Tutorials
^^^^^^^^^^^^^^


* MICCAI2019: `learn2reg <https://github.com/learn2reg/tutorials2019>`_ `PDF <https://github.com/learn2reg/tutorials2019/blob/master/slides>`_
  

     Medical image registration has been a cornerstone in the research fields of medical image computing and computer assisted intervention, responsible for many clinical applications. Whilst machine learning methods have long been important in developing pairwise algorithms, recently proposed deep-learning-based frameworks directly infer displacement fields without iterative optimisation for unseen image pairs, using neural networks trained from large population data. These novel approaches promise to tackle several most challenging aspects previously faced by classical pairwise methods, such as high computational cost, robustness for generalisation and lack of inter-modality similarity measures. Output from several international research groups working in this area include award-winning conference presentations, high-impact journal publications, well-received open-source implementations and industrial-partnered translational projects, generating significant interests to all levels of world-wide researchers. Accessing to the experience and expertise in this inherently multidisciplinary topic can be beneficial to many in our community, especially for the next generation of young scientists, engineers and clinicians who often have only been exposed to a subset of these methodologies and applications. We organise a tutorial including both theoretical and practical sessions, inviting expert lectures and tutoring coding for real-world examples. Three hands-on sessions guiding participants to understand and implement published algorithms using clinical imaging data. This aims to provide an opportunity for the participants to bridge the gap between expertises in medical image registration and deep learning, as well as to start a forum to discuss knowhows, challenges and future opportunities in this area.


* [kaggle:2016] `Image registration, the R way, (almost) from scratch <https://www.kaggle.com/vicensgaitan/image-registration-the-r-way>`_
  

     There are some packages in R for image manipulation and after some test I select “imager” , based on the CImg C++, fast and providing several image processing tools.


* [kaggle:2018] `X-Ray Patient Scan Registration <https://www.kaggle.com/kmader/x-ray-patient-scan-registration>`_
  

     SimpleITK, ITK, scipy, OpenCV, Tensorflow and PyTorch all offer tools for registering images, we explore a few here to see how well they work when applied to the fairly tricky problem of registering from the same person at different time and disease points.


2. Courses/Seminars/Videos
--------------------------

3. Toolbox
----------

3.1.
^^^^

3.2.
^^^^

4. Datasets & Competitions
--------------------------

4.1. Datasets
^^^^^^^^^^^^^


* [kaggle:2018] `ct-scans-before-and-after <https://www.kaggle.com/kmader/ct-scans-before-and-after>`_
  

     The dataset is supposed to make it easier to see and explore different registration techniques in particular `VoxelMorph <https://github.com/voxelmorph/voxelmorph>`_


4.2. Competitions
^^^^^^^^^^^^^^^^^

`\ All Challenges <https://grand-challenge.org/challenges/>`_
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

2019
""""

`CuRIOUS:2019 <https://curious2019.grand-challenge.org/>`_ | `Official solution <https://arxiv.org/ftp/arxiv/papers/1904/1904.10535.pdf>`_

..

   1 Register pre-operative MRI to iUS before tumor resection\ 
   2 Register iUS after tumor resection to iUS before tumor resection  


`ANHIR:2019 <https://anhir.grand-challenge.org/>`_ | `Official solution <https://www.researchgate.net/publication/332428245_Automatic_Non-rigid_Histological_Image_Registration_challenge>`_

..

   IEEE International Symposium on Biomedical Imaging (ISBI) 2019\ :
   High-resolution (up to 40x magnification) whole-slide images of tissues (lesions, lung-lobes, mammary-glands) were acquired - the original size of our images is up to 100k x 200k pixels. The acquired images are organized in sets of consecutive sections where each slice was stained with a different dye and any two images within a set can be meaningfully registered.


2018
""""

`iChallenges  <https://ichallenges.grand-challenge.org/>`_ 

`Continuous Registration Challenge <https://continuousregistration.grand-challenge.org/>`_ 

`Multi-shell Diffusion MRI Harmonisation Challenge 2018 (MUSHAC) <https://projects.iq.harvard.edu/cdmri2018/challenge>`_

2010
""""

`EMPIRE10 <http://empire10.isi.uu.nl/>`_

5. Papers
---------

5.1. Overview & Survey Papers
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

5.2. Key Algorithms
^^^^^^^^^^^^^^^^^^^

5.3.
^^^^

6. Key Conferences/Workshops/Journals
-------------------------------------

6.1. Conferences & Workshops
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

6.2. Journals
^^^^^^^^^^^^^
