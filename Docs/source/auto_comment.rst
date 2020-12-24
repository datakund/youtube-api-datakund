**************************************************
Auto Comment
**************************************************
It auto comments on the video passed in ``video_link`` with the comment passed in ``comment``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.auto_comment(comment="comment",video_link="video_link")

   
   :param str comment: comment which need to be typed
   :param str video_link: video url where need to post comment
   :return: {"body":{},"success_score":"100","errors":[]}
   :rtype: dict