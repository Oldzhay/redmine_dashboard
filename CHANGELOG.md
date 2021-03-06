## 2.3.3

* Fix error with pluralization patch (#53)
* Update locales
* Bundle transfiex utility as gem instead of git repo

## 2.3.2

* Fix error with missing pluralization keys (#50):
  Redmine I18n backend does not include a CLDR pluralization rule aware
  pluralize method. Rdb now patches the backend to include
  I18n::Backend::Pluralization as well as Redmines lazy locale load to
  load the pluralization rules.
* Update locales

## 2.3.1

* Fix version number

## 2.3.0

* New translations

## 2.2.0

* Add support for subprojects

## 2.1.0

* Include groups to assignee filter (#9)
* Add swimlane for each team member instead of "others" (#18)
* Several bug fixes

## 2.0 (2.0.dev)

* New release for Redmine 2.1+
* Improve grouping, swimlanes, filters
* New drop-down menus
* Quick issue editing (progress & assignee only)
* Workflow based column drag'n'drop

## 1.4

* Initial release for Redmine 1.4
* Simple task board
* Simple filter and grouping options
