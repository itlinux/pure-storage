Role Pure – Controllers
=========
This playbook set the controllers with all the necessary options to set pure as default
cinder block storage.

** It has two variables in the defaults: **
  -	IP ADDRESS for the PURE STORAGE
  -	PURE_TOKEN from PURE

** It prompts for the PROJECT ID  **

** It prompts for the token **


How To
-------
To run this playbook just create a new hosts files with the IP addres of the controllers
and run the

  `ansible-playbook -i hosts pure.yaml`


License
-------

Apache

Author Information
------------------

Remo Mattei
