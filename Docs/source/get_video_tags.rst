**************************************************
Get Video Tags
**************************************************
It fetches the video tags and tag links whose link is passed in ``video_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.get_video_tags(video_link="https://www.youtube.com/watch?v=eLrJUdBHiXA&list=PLsuCfYXzi5DJfjxOmPRJIS4KLlJhAlr8P&index=1")

   
   :param str video_link: video link whose tags need to be fetched
   :return: {"body": {'tags': 'tags', 'taglinks': 'taglinks'}, "success_score": "100", "errors": []}
   :rtype: dict
