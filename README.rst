===================
feincms-simpletable
===================

feincms-simpletable is a feincms plugin that adds a new content type for 
tables. Just copy-paste your data from Calc or Office spreadsheet into
simple table content in admin, and it will be automatically converted
to html and rendered as such on your website

Current limitation: merged cells are not supported

Quick start
-----------

1. Add "feincms-simpletable" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = (
        ...
        'feincms-simpletable',
    )

2. Run `python manage.py migrate` to create the polls models.

3. Add a Simple Table Content to any of your feincms pages. Add tables by copying 
   data from your Calc or Excel spreadsheet into content field
