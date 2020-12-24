**************************************************
Check Video Exists
**************************************************
It returns title of video passed in ``video_url``  if exists, otherwise returns None in ``title``

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.check_video_exists(video_url="video_url")

   
   :param str video_url: video url which need to be checked for existence
   :return: {"body": {'Title': 'Title'}, "success_score": "100", "errors": []}
   :rtype: dict