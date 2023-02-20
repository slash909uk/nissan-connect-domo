# nissan-connect-domo
PHP script to pull Nissan Leaf battery status from Nissan Connect cloud API and report to Domoticz/MQTT
Add your Nissan Connect credentials and rename the script from nissan-connect-domo.php.example to just .php to use it.

The script uses a Nissan Connect API wrapper class created by Guillame Boudreau here: https://github.com/gboudreau/nissan-connect-php

WARNING! Unlikely to work in US as API is hacked repeately by Nissan - refer to Guillame's class docs for more info. Works for me in UK/EU zone on 2018 Leaf.
