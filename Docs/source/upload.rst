**************************************************
Upload
**************************************************
It uploads the video to youtube.

.. raw:: html

        <div style="position: relative; padding-bottom: 56.25%; padding-top: 30px; margin-bottom:30px; height: 0; overflow: hidden; margin-left: 5%;"><iframe type="text/html" src="https://www.youtube.com/watch?v=fc-vL5F4EGo" frameborder="0" style="position: absolute; top: 0; bottom: 10; width: 90%; height: 100%;" allowfullscreen></iframe></div>

Here is the code:-

.. py:function:: youtube.upload(video_path="video_path",title="title",kid_type="kid_type",type="type",playlist="playlist",description="description")

   
   :param str video_path: Video Path
   :param str title: Title
   :param str kid_type: Kid Type
   :param str type: Type
   :param str playlist: Playlist
   :param str description: Description
   :return: {'VideoLink': 'VideoLink'}
   :rtype: dict