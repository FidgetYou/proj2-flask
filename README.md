# CIS 322 proj2-flask
Editor:	Ryan Collier, RCollier@UOregon.edu

This program hosts a Syllabus web site. 
Given the Syllabus text (in the proper format) this program shows the
week of the term, the starting day of the term and the week's description.

Specifics:
This webserver application creates an HTML file based on the file schedule.txt
stored in the local data directory. It then automatically transmits the HTML to
any computer requesting said file.
Syllabus HTML starts on "begin" given by schedule.txt and shows the week, 
starting day and month, and the weeks descriptions. The current week 
(if it falls within the given schedule) will be highlighed with a blue/
green background.

Running:
This program should run on a Raspberry Pi 3 with the Jessie version of Raspbian
running on it. But may also require installing Flask, Gunicorn, Arrow, Jinja2,
and Python.
The 'make run' command makes it run. But you may have to execute 
'make configure' first. 

