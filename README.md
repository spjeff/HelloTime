## Project Description
WebAPI clean base template echoes current time in JSON. +CORS +Windows Auth

WebAPI 2.2 project and clean simple baseline without all those extra MVC GUI components.  "HelloController" echoes back the current system time to show a current HTTP 200 reply (not HTTP 304 cached).


## Get Started
* Download ZIP and extract
* Open SLN with Visual Studio 2013 or higher
* Open "Package Manager Console" and run "Update-Package" to download assemblies
* F5 to build and run
* Open http://whateversite/api/Hello to execute GET and see JSON reply


## Screenshots
* Solution Explorer showing controller classes (GET/POST/PUT/DELETE)
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/1.png)
* Controller source with key highlights (CORS + Windows Auth)
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/2.png)
* IE running IIS Express locally
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/3.png)
* IE download "/api/Hello" JSON
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/4.png)
* Verify JSON with NotePad++
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/5.png)
* Fiddler "Options tab > [X] Automatically Authenticate"
![image](https://raw.githubusercontent.com/spjeff/HelloTime/master/docs/6.png)

## Notes
* Windows Authentication is enabled
* With Fiddler F9 Composer be sure to check "Options tab > [X] Automatically Authenticate"
* May need to enable Automatic Login for IE, FireFox. Read [http://www.scip.be/index.php?Page=ArticlesNET38]( http://www.scip.be/index.php?Page=ArticlesNET38) for how.


## Contact
Please drop a line to [@spjeff](https://twitter.com/spjeff) or [spjeff@spjeff.com](mailto:spjeff@spjeff.com)
Thanks!  =)

![image](http://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square)