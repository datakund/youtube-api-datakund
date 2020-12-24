**************************************************
Auto Like
**************************************************
It likes the video passed in ``video_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.auto_like(video_url="video_url")

   
   :param str video_url: video link which need to be liked
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict