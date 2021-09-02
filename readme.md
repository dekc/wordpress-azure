[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)


1. We will need to be able to update WP & Site Address (currently disabled via htaccess) - once we go live
2. Disable all inactive themes
3. Set PHP Memory limit to 768M
4. Does the server support cgi-fcgi? Preferred but not essential.
5. Set PHP max input variables to 3000
6. Set PHP version to 7.4.22 (major speed upgrades since 7.3.27)
7. Set max_execution_time to 120 if not already set.
8. Allow log_errors and display_errors = on
9. Check allow_url_fopen = on
