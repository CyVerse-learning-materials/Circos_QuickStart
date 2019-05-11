|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

Quick start of Circos VICE app in DE
====================================

Goal
----

`JupyterLab-Circos <https://github.com/fomightez/circos-binder/>`_ is a Dockerized version of the Circos software. [Circos](http://circos.ca/) a software package for visualizing data and information that was created by Martin Krzywinski. It excels at showing genomic characteristics and relationships. The Circos VICE app makes itavailable in a Jupyter environment provided by Cyverse. Circos use and the convenience that comes with having Circos working inside the Jupyter environment with interactive Python are illustrated in a series of included Jupyter notebooks. Indeed there are pages paralleling all Martin's tutorial pages. 

Because JupyterLab-Circos provides Circos inside Cyverse's VICE app environment, there are these benefits.

- Circos is available for data visualization or for educational purposes without installing..

- Circos visualizations can be viewed right in the same development environment facilitating faster routes to new perspectives.

- Easily share results with your team, even those members without Circos installed.

In this quick start, we will show you how to launch the Circos VICE app in DE.

----

Prerequisites
-------------

*Haven't signed-up to Cyverse?* `Here <https://github.com/fomightez/circos-binder/>`_ *you can select ``launch binder`` to get the same content on a more limited system where you cannot link to the Cyverse data repository or share with Cyverse-using colleagues.*

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*

	.. list-table::
	    :header-rows: 1

	    * - Prerequisite
	      - Preparation/Notes
	      - Link/Download
	    * - CyVerse account
	      - You will need a CyVerse account to complete this exercise
	      - `Register <https://user.cyverse.org/>`_

----

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Learning Center Docs
    * - Discovery Environment
      - Web/Point-and-click
      - `Discovery Environment <https://de.cyverse.org/de/>`_
      - `DE Manual <https://wiki.cyverse.org/wiki/display/DEmanual/Table+of+Contents>`_
      - `Guide <https://learning.cyverse.org/projects/discovery-environment-guide/en/latest/>`__

----

Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this quickstart you will need to have the following inputs prepared*. 

.. Note::

  The example input data (which contains data and Jupyter notebooks) will either already prefilled for you during app launch or obtained in the course of running the notebooks

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * - Chromosome size data and Jupyter notebooks
      - - various genomic data
        - Jupyter notebooks 
      - Input data can be a text files with genomic data
      - Example data is included in the `tutorial materials <http://circos.ca/software/download/>`_ that are installed in the launched app.

-----

*Get started: Launch NanoDJ*
-----------------------------

1. Login to the |discovery_enviornment|.

2. Click on **Apps** window in the DE workspace and search for and run JupyterLab-Circos.

.. Tip::

  Alternatively you can clik this |JupyterLabCircos logo|_ button to directly launch the Circos VICE app.

3. Under “Analysis Name” leave the defaults or make any desired notes.

4. Click **Launch Analysis**. You will receive couple of notifications on the bell corresponding to job submission and running with the "Access your running analysis here". 

5. Clicking on the "Access your running analysis" will open the JupyterLab-Circos in another tab in the browser after a brief building phase.

.. Note::

  You will be asked to authenticate again to the JupyterLab with your CyVerse username and password

7. In the main JupyterLab interface, in the file browser pane on the left, double-click on ``index.ipynb``.

8. Click on a notebook description in the list to launch it.

9. Finally, once you finish analysis, navigate to the Discovery Environment tab, select the Analysis window and select the analysis, click "save and complete analysis". Upon clicking complete analysis, the analysis will be completed and all the outputs will be brought back to the analysis folder. Alternatively you can use ``iput -rPVT <folder name>`` command to transfer the data back to the data store.

----

Additional information, help
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- Full materials for the webinar is available `here <https://wiki.cyverse.org/wiki/pages/viewpage.action?pageId=????????????>`_

- See the original `JupyterLab quick start <https://learning.cyverse.org/projects/vice/en/latest/user_guide/quick-jupyter.html>`_ 

- Search for an answer: `CyVerse Learning Center <http://learning.cyverse.org>`_ or `CyVerse Wiki <https://wiki.cyverse.org>`_

- Contact CyVerse support by clicking the intercom button on the page.

----

**Fix or improve this documentation**

- On Github: `Repo link <https://github.com/CyVerse-learning-materials/Circos_QuickStart>`_
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home`_

.. |JupyterLabCircos logo| image:: ./img/vice_badge.png
.. _JupyterLabCircos logo: https://de.cyverse.org/de/?type=apps&app-id=4cc9f054-5343-11e9-8b4d-008cfa5ae621&system-id=de

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
.. _CyVerse logo: http://learning.cyverse.org/
.. |Home_Icon| image:: ./img/homeicon.png
    :width: 25
    :height: 25
.. _Home_Icon: http://learning.cyverse.org/
.. |discovery_enviornment| raw:: html

    <a href="https://de.cyverse.org/de/" target="_blank">Discovery Environment</a>