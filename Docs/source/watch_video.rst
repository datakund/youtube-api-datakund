**************************************************
Watch Video
**************************************************
It opens the video passed in ``video_url`` and then waits for the time passed in ``time``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.watch_video(time="time",video_url="video_url")

   
   :param str time: amount of time in seconds to wait
   :param str video_url: video which need to be opened
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict