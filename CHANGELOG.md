# Change Log

## [1.0.4] 2021-01-04
### Bug fixing

- Read properly the `.env` variables. Impacted file(s):
    - Impacted file: **core/settings.py**

## [1.0.3] 2021-01-01
### Bug fixing, Improvements

- 2021-01-01 - Improvements
    - Update login form label
    - Inject the current page name in view (segment variable) 

- 2020-06-28 - Update the UI Kit
    - Quick UI KIt by Webpixels

- Patch #3 - Whitenoise Fix - Wrong positioning in 'core/settings.py'
    - WhiteNoiseMiddleware must be positioned right after SecurityMiddleware
    - Impacted file: **core/settings.py** / MIDDLEWARE section

## [1.0.2] 2020-06-18
### Bug fixing, Improvements

- Patch #1 - Error when access `admin` path (no trailing slash)
- Update Sample UI Kit - [Neumorphism UI](https://themesberg.com/product/ui-kits/neumorphism-ui) by Themesberg

## [1.0.1] 2020-05-30
### Bug fixing, Improvements

- Add CHANGELOG.md to track all changes
- Patch Error-404.html not used in all contexts
- Rename error pages: error-40X become page-40X
- Update LICENSE file - added more information regarding the app usage

## [1.0.0] 2020-02-07
### Initial Release
