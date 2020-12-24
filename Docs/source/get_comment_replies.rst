**************************************************
Get Comment Replies
**************************************************
It fetches the comments replies text along with userlink and username currently opened in browser.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.get_comment_replies()

   
   :return: {"body": [{'userlink': 'userlink', 'replytext': 'replytext', 'user': 'user'}], "success_score": "100", "errors": []}
   :rtype: dict