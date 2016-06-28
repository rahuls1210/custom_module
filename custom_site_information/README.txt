INTRODUCTION
------------

The Custom Site Information providing a site_api_key custom field
on the Site Information page.

The site_api_key is used to acces the Json format of node of page content type

User can see the json format of page content type node by appending the page_json with Site API Key and node id to base url

 e.g http://localhost/page_json/FOOBAR12345/17

   where FOOBAR12345 is Site Api Key and 17 is the node id
  



NO SPECIAL REQUIREMENTS
-----------------------

INSTALLATION
------------
 
 * Install as you would normally install a contributed Drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.


CONFIGURATION
-------------
 
 * Configure in Administration » Configuration » Site information:

   - Set the Site API Key with specific string.


TROUBLESHOOTING
---------------

 * If the data not visible , check the following:

   - Are the "Site API Key" passing in the URL is same as in configuration settings

   - Node id passing in URL is exists.
    
   - Node is of page content type.


MAINTAINERS
-----------

 


