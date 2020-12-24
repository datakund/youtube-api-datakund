**************************************************
Get Transcript
**************************************************
It fetches the transcript of the video whose link is passed in ``video_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.get_transcript(video_url="video_url")

   
   :param str video_url: video link whose transcript need to be fetched
   :return: {"body": {'Transcript': 'Transcript'}, "success_score": "100", "errors": []}
   :rtype: dict