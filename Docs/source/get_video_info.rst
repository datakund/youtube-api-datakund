**************************************************
Get Video Info
**************************************************
It fetches the video info whose link is passed in ``video_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.get_video_info(video_url="video_url")

   
   :param str video_url: video url
   :return: {"body": {'DisLikes': 'DisLikes', 'Title': 'Title', 'Subscribers': 'Subscribers', 'Comments': 'Comments', 'ChannelLink': 'ChannelLink', 'ChannelName': 'ChannelName', 'Desc': 'Desc', 'Views': 'Views', 'Duration': 'Duration', 'Publish_Date': 'Publish_Date', 'Likes': 'Likes'}, "success_score": "100", "errors": []}
   :rtype: dict