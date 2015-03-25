.. _RecommenderXBlock:

##################
RecommenderXBlock
##################


In a RecommenderXBlock tool, we can provide students a list of resources
in the form of pre-existing web pages. These resources could be recommended
by instructors or students for misconception remediation (e.g., attching
this tool to a problem), additional reading (e.g., attaching this tool
to the lecture video), etc. We give instructors and students several
gadgets for managing the resources in collaboration.

#. For instructors and students, they can:

   -  Add new resources.
   -  Edit existing resources and work jointly to improve the quality of
      resources (e.g., give an informative resource summary).
   -  Manage quality by voting for high quality resources or flagging spam
      and abuse.

#. Besides, for instructors, they can endorse useful resources or remove
   irrelevant entries.

Here is an example of how a RecommenderXBlock looks like in a course. The
upper part of the figure illustrate a question in problem set to which the
RecommenderXBlock tool is attached. The middle of the figure shows a list
of resources and several gadgets for users to work on the resources. The
bottom portion displays additional information (e.g., thumbnail, summary)
about a given resource on mouse-over event. 

.. image:: ../../../shared/building_and_running_chapters/Images/RecommenderXBlockExample.png
  :alt: An overview of the RecommenderXBlock


****************************
Create a RecommenderXBlock Tool
****************************


To create a RecommenderXBlock tool:

#. Add the RecommenderXBlock advanced component. 

    #. On the **Settings** menu, click **Advanced Settings**.

    #. In the field for the **Advanced Module List** policy key, place your
       cursor between the brackets.

    #. Enter the following value. Make sure to include the quotation marks.

       ``"recommender"``

    #. At the bottom of the page, click **Save Changes**.

       The page refreshes automatically. At the top of the page, you see a
       notification that your changes have been saved.

    #. Return to the unit where you want to attach this tool. The list of
       possible components now contains an Advanced component.

#. In the unit (e.g., problem, lecture video) where you want to attach this
   tool, click **Advanced** under **Add New Component**.
#. Click **recommender**.
#. [Optional] In the component that appears, click **Edit**. Then, in the
   component editor, specify the settings that you want.

   -  Whether to take users on a little introduction tour when they see the
      tool first time?.
   -  Whether to disable the user interface functions which are under
      development? Currently, they are untested. Thus, we strongly recommend
      you disable them, 
   -  How many resources do you want to show in each page of the resource list.
   -  How many page icons do you want to show in the pagination control (i.e.,
      the page range)? The icons for pages from (current page - page range) to
      (current page + page range) will be shown.

#. Click **Save**.
#. [Optional] You can go to the unit where you just added the RecommenderXBlock,
   and suggest some resources, or leave the works to students.

