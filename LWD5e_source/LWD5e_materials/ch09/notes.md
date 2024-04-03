# forms
browser collects information and 'encodes' it
> characters not permitted are encoded into hexadecimal

field info added to database

&<html_entity>;

web application= stores data in database

good practice to wrap form controls in dev or lists

action="location of script"

some hosting plans have premade scripts in php

## get (read request)
uses resoruce url as seen in example below

cached

get method has "?" `.com/some_script?`

`get http://www.bandname.com/mailinglist.php?name=Sally+Strongarm&email=→
strongarm%40example.com`

encoded form data is tacked into the url

__don't submit sensitive data through this__

## post (create/update)
data is resubmitted upon reload

uses http request message body -- more secure

server request: special headers =followed by> data

https: encrypted data in transit


# name attribute
provides variable name as in field of the database

submit/reset buttons don't require name att as they had implicit functions in them

__variable name must match the one's in backend prog language__

# readonly is submitted but disabled is not
prevents user from changing value

# <input type="">
file | submitting a file
time;date;datetime-local;month;week | cal widget


