**************************************************
Get Watch History
**************************************************
It fetches the title and link of the videos in watch history which is currently opened in browser

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.get_watch_history()

   
   :return: {"body": [{'title': 'title', 'link': 'link'}], "success_score": "100", "errors": []}
   :rtype: dict