Other Functions
**************************************************
You can use basic functions which selenium provides with this library like opening a url, get pagesource, get current url etc. These are the functions:-

Open
========

It will open the url provided in the argument.

.. py:function:: youtube.open(url)

   :param str url: Link which need to be opened
   :return: {}
   :rtype: dict
	
	
Get Page Title
=================

It returns the title of page opened.

.. py:function:: youtube.get_page_title()

   :return: {"pagetitle":"youtube"}
   :rtype: dict

Get Page Source
===================

It returns the pagesource of page opened.

.. py:function:: youtube.get_page_source()

   :return: {"pagesource":"pagesource"}
   :rtype: dict

Get Current Url
===================

It returns the pagesource of page opened.

.. py:function:: youtube.get_current_url()

   :return: {"url":"url"}
   :rtype: dict

Reload
===================

It reloads the page opened.

.. py:function:: youtube.reload()

   :return: {}
   :rtype: dict

Keypress
===================

It perform the keypress passed.

.. py:function:: youtube.keypress(key)

   :param str key: Key which need to be pressed, e.g pagedown,arrowleft,enter
   :return: {}
   :rtype: dict

Scroll
===================

It scrolls to the end of page.

.. py:function:: youtube.scroll()

   :return: {}
   :rtype: dict
   
End
===================

It ends the youtube session and close the automated chromedriver.

.. note:: You will need to create youtube object again after ``end()``.

.. py:function:: youtube.end()

   :return: {}
   :rtype: dict
	
Quit
===================

It quits the bot-studio application runing in background.

.. note:: You will need to import bot-studio library again to start application.

.. py:function:: youtube.quit()

   :return: {}
   :rtype: dict
