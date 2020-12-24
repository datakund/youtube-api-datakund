**************************************************
Set Playback Speed
**************************************************
It sets the playback speed passed in ``speed`` in the video currently playing on browser.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.set_playback_speed(speed="speed")

   
   :param str speed: speed to set e.g. 1.25
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict