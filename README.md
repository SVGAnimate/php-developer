# php-developer
PHP IDE


Based on Qt Creator:
### Change Application Name
<qt-creator>/src/app/app_version.h.in
```
namespace Core {
namespace Constants {
...
const char IDE_DISPLAY_NAME[] = \"Php Developer\";
const char IDE_ID[] = \"qtcreator\";
const char IDE_CASED_ID[] = \"PhpDeveloper\";
```
### Change Application Icon
<qt-creator>/src/plugins/coreplugin/images/logo/128/QtProject-qtcreator.png
