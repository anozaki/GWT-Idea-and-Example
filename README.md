GWT Idea and Example
====================

About This Project
------------------

Been programing GWT for the last 5 years and wanted to share some info. I really like using GWT over
straight javascript, so I want GWT to be more widely accepted as a viable solution.

I will be using GWT, Spring, Hibernate on Tomcat to run my application. This application will create
a war file you can drop right into the tomcat and run it.

Eclipse
-------

I'm using eclipse to work on my project and so should you. Here is a list of plugins I'm using
with Eclipse.

* m2e
* m2e-wtp
* gwt
* egit

Build
-----

I've choose maven. Not perfect but I think it works better then ant builds. 

Database
--------

I will be using PostgreSQL as my entity backing, but should be really easy to replace it to
use other database. The main reason I'm not going to use MySQL is because it lacks sequence.
I think this code will run under more database using sequence. So if you want to run this code on
mysql, you'll have to change the entity's GeneratedValue to be GenerationType.AUTO instead of
GenerationType.SEQUENCE.

Application Server
------------------

I'm using tomcat since its light weight but this application shouldn't care what you deploy it out 
on. Modify it to run on other application server if you like.

I might look into using App Engine but it is not my current priority.

Suggestion
----------

If you have any suggestion or problem with the code, please post on github's issue tracker.

Where Now?
----------

Browse my code and learn from it. Go read the GWT documentation. Join the GWT mailing list.
Contribute code to GWT.