.. _RecommenderXBlock:

##################
RecommenderXBlock
##################


The RecommenderXBlock provides students with a list of resources on
the web related to the course content. These resources are jointly
managed by the instructors and the students. The most common use is
for remediation of errors and misconceptions, followed by providing
additional, more advanced resources. For example, if a student is
working through a physics problem, the Recommender is likely to show
links to concepts used in the problem on Wikipedia, PhET, and
OpenStax, as well as in the course itself.


#. Students and instructors can:

   - Add new resources.
   - Edit existing resources and work jointly to improve the quality of
     resources (e.g., give an informative resource summary).
   - Manage quality by voting for high quality resources or flagging
     resources as spam or abuse.

#. Besides, for instructors, they can endorse useful resources or remove
   irrelevant entries.


The tool has been successfully used in a course in introductory Python
programming, where it was placed below every problem. We found that
the resources provided were substantially more in-depth and less
scaffolded than what is found in the discussion forum -- in other
words, an excellent first line of defense for both complex knowledge
gaps, as well as the first nudges to move students in the right
direction. The tool is less useful for simple problems -- in a
one-liner programming exercise, students would usually have no
resources. 

When the tool is placed in a course, it is helpful to guide students
to using it the first time it appears. It is intentionally
non-obtrusive, so students may not notice it otherwise. We've found
substantially higher usage levels when students are explictly told about it. 

This is an example of a RecommenderXBlock in a course. The upper part
of the figure illustrates a question in problem set where the
RecommenderXBlock is attached. The middle of the figure shows a list
of resources and several gadgets for users to work on the
resources. The bottom portion displays additional information (e.g.,
thumbnail, summary) about a given resource on mouse-over event.

.. image:: ../../../shared/building_and_running_chapters/Images/RecommenderXBlockExample.png
  :alt: An overview of the RecommenderXBlock


****************************
Create a RecommenderXBlock Tool
****************************

To create a RecommenderXBlock tool:

#. Add the RecommenderXBlock advanced component. 

    #. On the **Settings** menu, click **Advanced Settings**.

    #. Make sure that **recommender** is in the field for the
    **Advanced Module List** policy key. For example, if you have no
    other advanced module, this field should be:

       ``["recommender"]``

    #. At the bottom of the page, click **Save Changes**.

       The page refreshes automatically. At the top of the page, you
       should see a notification that your changes have been saved.

    #. Return to the unit where you want to attach this tool. The
       Recommender will be available under the Advanced Component
       button.

#. In the unit (e.g., problem, lecture video) where you want to attach this
   tool, click **Advanced** under **Add New Component**.
#. Click **recommender**.
#. [Optional] In the component that appears, click **Edit**. Then, in the
   component editor, specify the settings that you want.

   - Whether to take users on a little introduction tour when they see
      the tool first time. If selected, the first time (and only the
      first time) a user sees the RecommenderXBlock, there will be a
      short guided tutorial. 
   - Whether to disable the user interface functions which are under
      development. Since these are untested and under development,
      please leave these disabled unless otherwise advised by edX staff.
   -  How many resources do you want to show in each page of the resource list.
   -  How many page icons do you want to show in the pagination control (i.e.,
      the page range)? The icons for pages from (current page - page range) to
      (current page + page range) will be shown.

#. Click **Save**.
#. [Optional] You can go to the unit where you just added the RecommenderXBlock,
   and suggest some resources, or leave the works to students.

