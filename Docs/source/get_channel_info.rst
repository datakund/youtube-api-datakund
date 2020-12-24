**************************************************
Get Channel Info
**************************************************
It fetches the info of channel whose link is passed in ``channel_link``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.get_channel_info(channel_link="channel_link")

   
   :param str channel_link: channel link whose info need to be fetched
   :return: {"body": {'title': 'title', 'links': 'links', 'views': 'views', 'joined': 'joined', 'description': 'description', 'subscribers': 'subscribers', 'location': 'location'}, "success_score": "100", "errors": []}
   :rtype: dict