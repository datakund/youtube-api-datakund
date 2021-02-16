**************************************************
Auto Subscribe
**************************************************
It subscribes the channel passed in ``channel_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.auto_subscribe(channel_url="https://www.youtube.com/channel/UCM0YvsRfYfsniGAhjvYFOSA")

   
   :param str channel_url: Channel url which need to be subscribed
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
