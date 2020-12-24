**************************************************
Upload To Playlist
**************************************************
It uploads the video to youtube.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.upload_to_playlist(title="title",video_path="video_path",kid_type="kid_type",description="description",playlist="playlist",type="type")

   
   :param str title: title of video
   :param str video_path: local file path of video
   :param str kid_type: e.g Yes, it's made for kids
   :param str description: description of video
   :param str playlist: playlist name
   :param str type: e.g. Private or Public
   :return: {"body": {'VideoLink': 'VideoLink'}, "success_score": "100", "errors": []}
   :rtype: dict