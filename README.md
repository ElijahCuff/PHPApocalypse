# PHP Apocalypse©
PHP Apocalypse© is an advanced load bot that uses zombie proxies to start a user agent flood on a specified domain.
    
## Installation    
* Add the 2 files ( index & agents ) to your php server like heroku or free hosting provider    
* Open index.php with specific options

   
   
## Request Parameters    
* Cross Origin - for using on a cross origin environment,    
`crossOrigin=true`    

* Format - get a HTML or Formatted UTF-8 response,    
`format=utf-8`    
`format=html`   
    
* User Agent Predefined - override the random user agent with a specified one,   
`agent=url encoded user agent`    
    
* Proxy Predefined  - override the automatic proxy finder with a predetermined proxy,   
`proxy=url encoded proxy (1.0.0.0:8080)`    
   
* Refferer Override - change the referee from the preset fixed refferer,
`refferer=url encoded refferer`
 
* Rounds - set the amount of rounds to load after finding a proxy,   
`rounds=8`   
     
Many more options can be customised using some minor edits.
 
This script is provided for educational purposes only, please don't use it for a DDOS Script as this is illegal. You must take full responsibility of the way you use the script, we take no responsibility for your actions in relation to this script, please refer to the MIT licence for information.
