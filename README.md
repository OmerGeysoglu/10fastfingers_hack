# Hacking 10fastfingers

If you want to use it on your 10fastfingers account, line 6 must change like <br/> 
```
profile = webdriver.FirefoxProfile('/home/{your_username}/.mozilla/firefox/{your_default_profile}')
driver = webdriver.Firefox(profile)
```
if you want to use without account you just run script.

[Driver for Firefox](https://github.com/Mozilla/geckodriver/releases)

**Don't forget to edit path in environment variables**
