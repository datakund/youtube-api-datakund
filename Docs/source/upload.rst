**************************************************
Upload
**************************************************
It uploads the video to Youtube.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.upload(title="Testing Upload",video_path="C:/Users/video.mp4",kid_type="Yes, it's made for kids",description="I am testing",type="Public")

   
   :param str title: title of video
   :param str video_path: local file path of video
   :param str kid_type: e.g. Yes, it's made for kids
   :param str description: description of video
   :param str type: e.g. Public or Private
   :return: {"body": {'VideoLink': 'VideoLink'}, "success_score": "100", "errors": []}
   :rtype: dict
