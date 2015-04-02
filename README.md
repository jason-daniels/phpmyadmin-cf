phpMyAdmin Cloud Foundry Ready
=============================

There is another version of phpMyAdmin made by [dmikusa](https://github.com/dmikusa-pivotal) (see: [https://github.com/dmikusa-pivotal/cf-ex-phpmyadmin](https://github.com/dmikusa-pivotal/cf-ex-phpmyadmin) ) but this version can't work in offline Cloud Foundry and also can't find another mysql provide by `cleardb` or `p-mysql`.

This version is a real fork from phpMyAdmin.

Installation
============
Just 5 steps:

 1. Download the zip file from here: [https://github.com/cloudfoundry-community/phpmyadmin-cf/archive/cf-ready.zip](https://github.com/cloudfoundry-community/phpmyadmin-cf/archive/cf-ready.zip).
 2. Unzip it
 3. Go inside the unzipped folder and run `cf push`
 4. Bind your mysql service with `cf bs phpmyadmin-cfready <service_name>`
 5. Restage the service with `cf restage phpmyadmin-cfready` and you're done


