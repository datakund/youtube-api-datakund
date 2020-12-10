**************************************************
Upload
**************************************************
It uploads the video to youtube.

Here is the code:-

.. py:function:: youtube.upload(title="title",description="description",kid_type="kid_type",video_path="video_path",playlist="playlist",type="type")

   
   :param str title: Video Title
   :param str description: Description of video
   :param str kid_type: e.g No, it's not Made for Kids
   :param str video_path: Full Video file path
   :param str playlist: 
   :param str type: e.g public, private
   :return: {'VideoLink': 'VideoLink'}
   :rtype: dict