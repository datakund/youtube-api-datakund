**************************************************
Login Cookie
**************************************************
It logins to youtube through the cookies passed in ``cookies``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.login_cookie(cookies=[{"domain": ".youtube.com","expirationDate": 1676431710.556339,"hostOnly": false,"httpOnly": false,"name": "__Secure-3PAPISID","path": "/",},...])

   
   :param str cookies: list of cookies of youtube
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
