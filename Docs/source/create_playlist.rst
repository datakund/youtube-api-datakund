**************************************************
Create Playlist
**************************************************
It creates new playlist with the name passed in ``playlist_name`` and returns playlist like in ``playlist_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.create_playlist(playlist_name="DataKund")

   
   :param str playlist_name: name of the new playlist to create
   :return: {"body": {'playlist_link': 'playlist_link'}, "success_score": "100", "errors": []}
   :rtype: dict
