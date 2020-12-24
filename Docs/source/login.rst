**************************************************
Login
**************************************************
It logins to youtube through the credentials passed in ``username`` and ``password``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: youtube.login(username="username",password="password")

   
   :param str username: Account Username
   :param str password: Account Password
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict