**************************************************
Delete Video From Watch Later
**************************************************
It deletes the video whose title is passed in ``title`` from the watch later videos.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.delete_video_from_watch_later(title="title")

   
   :param str title: title of video which needs to be deleted
   :return: {"body": [{'Column A@txt': 'Column A@txt'}], "success_score": "100", "errors": []}
   :rtype: dict