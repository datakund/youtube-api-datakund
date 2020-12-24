**************************************************
Like Comment
**************************************************
It likes the comment whose text is passed in ``comment``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.like_comment(comment="comment")

   
   :param str comment: comment text which need to be liked
   :return: {"body": [{'Column A@txt': 'Column A@txt'}], "success_score": "100", "errors": []}
   :rtype: dict