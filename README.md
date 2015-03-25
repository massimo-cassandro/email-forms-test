# Using form in email test

See [http://www.sitepoint.com/forms-in-email/](http://www.sitepoint.com/forms-in-email/)

Test result.


| Client                         | Form is displayed | Form is functional |
|--------------------------------|:-----------------:|:------------------:|
| Thunderbird 31 (OSX)           |         Y         |        Y (2)       |
| Apple Mail 8.2 (OSX)           |         Y         |        Y (1)       |
| Opera Mail 1 (OSX)             |         Y         |          Y         |
| Windows Live Mail 2012 (win 7) |         Y         |      Y (1) (3)     |
| Outlook 2013 (Win 7)           |         N         |          N         |
| Outlook.com (web)              |         Y         |          N         |
| Yahoo Mail (web)               |         Y         |      Y (1) (3)     |
| GMail (web)                    |         Y         |      Y (1) (3)     |
| GMail App (Android)            |         Y         |    Y (1) (3) (4)   |
| GMail Inbox (Android)          |         Y         |    Y (1) (3) (4)   |
| Yahoo Mail App (android)       |         Y         |      Y (1) (4)     |
| Android Mail (4.4.4)           |         Y         |      Y (1) (4)     |
| Gmail App (IOS 8.1.3)          |         Y         |      Y (1) (3)     |
| Apple Mail (IOS 8.1.3)         |         Y         |        Y (1)       |
| Outlook for IOS (IOS 8.1.3)    |         N         |          N         |
| Yahoo Mail for IOS             |         Y         |      Y (1) (5)     |

## Notes
1. The `required` attribute is ignored
2. Fields with `required` attributes are highlighted if empty, but the form can be submitted anyway
3. Alert on submit
4. Input text and textarea fields are not editable
5. Result page is opened inside the app

