**************************************************
Get Playlist Videos
**************************************************
It fetches link and title of the videos in the playlist passed in ``playlist_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.get_playlist_videos(playlist_link="playlist_link")

   
   :param str playlist_link: playlist link whose videos need to be fetched
   :return: {"body": [{'Title': 'Title', 'Video_Link': 'Video_Link'}], "success_score": "100", "errors": []}
   :rtype: dict