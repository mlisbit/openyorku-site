.. _`About`:
About
==============
A RESTful API for all things York University.

.. note:: Open YorkU API is currently under active development. 


Why is this being built?
--------------
York University is the 3rd largest university in Canada, and with the recent addition of Lassonde school of Engineering - it's about time something like this existed. Though I doubt openYorkU will become officially adapted, I hope York will see the potential and allow for easier access to their information.

With open data, students may create brilliant apps around it, and profs will have a large data set to work with and discover things otherwise overlooked. Tying this type of service around clubs, news and events; information will travel faster throughout the campus. The world will become aware of all the great things York University offers.

Current limitations
--------------
Open YorkU API is currently under active development, though I don't have as much time as I'd like to work on it; other projects, school, and work all interfere. Things that are missing, and required for this to be successful:     

  * authentication (API tokens).
  * request tracking, and possible limits.
  * permissions for POST's and GET  

Future improvements
--------------
Once all that's done, I plan on adding the following features:  

  * Get timetable for user, using session cookie.
  * Get exam schedule for user, using session cookie.
  * Parsing YorkU's daily news feed.

Universities with API's of their own
--------------
  * `Waterloo University`_
  * `Berkeley University`_
  * `University of Michigan`_
  * `others`_ ...

.. _Waterloo University: https://github.com/uWaterloo/api-documentation
.. _Berkeley University: https://developer.berkeley.edu/
.. _University of Michigan: http://developer.it.umich.edu/
.. _others: http://blog.mashape.com/list-of-15-university-apis/

Possible app ideas
--------------
  * improved map of campus 

    * plot all food buildings, recreational areas, parking lots, and libraries.
    * directions to everything.
    * find the nearest bathroom facilities, art exhibits, or other place of interest.
    * find currently open restaurants and buildings. 
    * *not enough people know about all the great food places at York, cool study spots, and recreational areas.*
  * ratings 

    * courses (easiness/usefullness)
    * buildings (cleanliness/architectual appeal)
    * restaurants (cleanliness/cost/quantity)
  * social timetable picker (like `uwflow`_)

    * pick timetables with your friends, so you're all in the same courses. 

  * event notifications

    * with support for clubs to post events, every event would be known about 
    * (no more missing a bakesale, or a poster sale in Vari Hall.)

.. _uwflow: https://uwflow.com/
