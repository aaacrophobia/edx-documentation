.. _Automatic Email:

###################################################
Automatic Email Messages from the Open edX Platform
###################################################

.. Note: Any update to the **discussion notification** information should also
.. be made to the manage_live_course/automatic_email.rst file in the partner
.. course authors guide.

To help learners become and remain engaged in a course, edX sends several types
of automatic email messages.

.. list-table::
 :widths: 20 10 20 50
 :header-rows: 1

 * - Email Type
   - Course Pacing
   - Day Sent
   - Description
 * - :ref:`Discussion Notification`
   - Instructor-paced and self-paced
   - Unspecified
   - Notifications that a user has responded to a post on a discussion.

*****************************
Automatic Email Message Text
*****************************

The following example messages show the text of the email messages that edX
sends to learners automatically.

.. contents::
 :local:
 :depth: 1

.. A SYSADMIN HAS TO ENABLE THIS IN DJANGO
.. A SYSADMIN HAS TO ENABLE THIS IN DJANGO
.. A SYSADMIN HAS TO ENABLE THIS IN DJANGO
.. A SYSADMIN HAS TO ENABLE THIS IN DJANGO
.. A SYSADMIN HAS TO ENABLE THIS IN DJANGO

.. _Discussion Notification:

================================
Discussion Notification
================================

After a learner or course team member creates a post in the course discussions,
edX sends the following email message the first time a learner or course team
member replies to the original post.

::

  Subject: Response to <title of post>

  <edX username> replied to <title of post>:

    <text of comment>

The message also contains a **View discussion** option that takes the learner
to the discussion post.

EdX does not send individual messages for any additional replies on the post.
However, the learner automatically receives a daily digest email message that
summarizes additional activity on the post. For more information, see
:ref:`learners:Receiving Discussion Notifications` and
:ref:`learners:Receiving Daily Digests`.
