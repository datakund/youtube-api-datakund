**************************************************
Find Click Video
**************************************************
It will click on the video whose title is passed in ``searchtext``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.find_click_video(searchtext="searchtext")

   
   :param str searchtext: title or keyword which is present in video title or description
   :return: {"body": [{}], "success_score": "100", "errors": []}
   :rtype: dict