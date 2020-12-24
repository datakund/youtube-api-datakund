**************************************************
Search
**************************************************
It searches the keyword passed in ``keyword`` on youtube.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.search(keyword="keyword")

   
   :param str keyword: keyword need to be searched on youtube
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict