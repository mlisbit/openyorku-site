.. _`About`:
Getting Started
==============

.. note:: Because this API is still under active development, don't expect anything to work. It's also hosted on a free instance of Heroku, so results will be slow. Or I went over my quota, and can't pay for it.    




Examples
--------------

  * {GET} `api.openyorku.com/courses`_ to get a list of all the courses york has to offer.
  * {GET} `api.openyorku.com/courses?limit=5&fields=title&q=science`_ get only the titles of 5 courses with 'science' in it.
  * {GET} `api.openyorku.com/courses/#course_code#`_ look a little closer at the course.
  * {GET} `api.openyorku.com/courses?credit_count=3,6&year_level=3&course_subject=EECS`_ get all the 3rd year computer science programs with a credit count of 3 or 6.
  * {GET} `api.openyorku.com/subjects`_ get a list of all the subjects, and their respective courses
  * {GET} `api.openyorku.com/places/restaurants`_ get a list of all the restaurants at York, their open/close times, gps co-ordinates, and types of food served.
  * {GET} `api.openyorku.com/places/restaurants?tags=coffee&now_open=1`_ get all the open coffee shops
  * {GET} `api.openyorku.com/places/buildings`_ get a list of all buildings, including all Points of Interests within them, gps co-ordinates, and building cover polygon for google maps. 

.. _api.openyorku.com/courses: http://api.openyorku.com/courses
.. _api.openyorku.com/courses?limit=5&fields=title&q=science: http://api.openyorku.com/courses?limit=5&fields=title&q=science
.. _api.openyorku.com/courses/#course_code#: http://api.openyorku.com/courses/ADMS1000
.. _api.openyorku.com/courses?credit_count=3,6&year_level=3&course_subject=EECS:  http://api.openyorku.com/courses?credit_count=3,6&year_level=3&course_subject=EECS
.. _api.openyorku.com/subjects: http://api.openyorku.com/subjects
.. _api.openyorku.com/places/restaurants: http://api.openyorku.com/places/restaurants
.. _api.openyorku.com/places/restaurants?tags=coffee&now_open=1: http://api.openyorku.com/places/restaurants?tags=coffee&now_open=1
.. _api.openyorku.com/places/buildings: http://api.openyorku.com/places/buildings