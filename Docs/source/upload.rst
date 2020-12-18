**************************************************
Upload
**************************************************
It uploads the video to Youtube.

.. raw:: html

        <div style="position: relative; padding-bottom: 56.25%; padding-top: 30px; margin-bottom:30px; height: 0; overflow: hidden; margin-left: 5%;"><iframe type="text/html" src="https://www.youtube.com/embed/fc-vL5F4EGo?autoplay=1&mute=1" frameborder="0" style="position: absolute; top: 0; bottom: 10; width: 90%; height: 100%;" allowfullscreen></iframe></div>

Here is the code:-

.. py:function:: youtube.upload(video_path="video_path",playlist="playlist",kid_type="kid_type",type="type",description="description",title="title")

   
   :param str video_path: Video Path
   :param str playlist: Playlist
   :param str kid_type: Kid Type
   :param str type: Type
   :param str description: Description
   :param str title: Title
   :return: {'VideoLink': 'VideoLink'}
   :rtype: dict