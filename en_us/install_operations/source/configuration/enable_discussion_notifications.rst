.. _Enable Discussion Notifications:

##########################################
Enable Discussion Notifications
##########################################

You can set up notifications that learners receive the first time that anyone
adds a response to a discussion post that they have made.

For more information, see :ref:`opencoursestaff:ADD_REFERENCE` and
:ref:`openlearners:ADD_REFERENCE`.

.. contents::
   :depth: 1
   :local:

*******************************
Enable Discussion Notifications
*******************************

To enable discussion notifications for all courses in your Open edX instance,
follow these steps.

#. Sign in to the LMS Django administration console for your base URL. For
   example, ``http://{your_URL}/admin``.

#. On the **Site Administration** page, locate **Site_Configuration**.

#. In the **Site_Configuration** section, next to **Site configurations**,
   select **Change**.

#. On the **Change site configuration** page, locate the **Values** field, and
   then add the following value.

   ::

     {
      "enable_forum_notifications":true
      }

#. Select **Save**.



.. include:: ../../../links/links.rst
