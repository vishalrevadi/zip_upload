# Changelog

All notable changes to this Package will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2024-04-02

### Added

- Implemented a package documentation deployment workflow and Added comprehensive documentation for the package. <!-- [(#102)](https://github.com/Healthlane-Technologies/pkg-zelthy3-crud/pull/129) -->


## [0.1.8] - 2024-04-02

**Date**: 2nd April 2024

* Celery Tasks Logging

## v1.48.0

**Date**: 29th Mar 2024  

* Added Multiple File option for these models: PatientConsentFormModel, DoctorConsentFormModel, SelfDeclarationModel, InvoiceModel, PrescriptionModel

## v1.47.0

**Date**: 22nd Mar 2024  

* Whitelist tntdemoapp schema


## v1.46.14

**Date**: 19th Mar 2024  

* convert PurchaseModel datetime fields to zdatetime field

## v1.46.13

**Date**: 14th Mar 2024  

* Fix whitelist of jjvn schemas

## v1.46.12

**Date**: 13th Mar 2024  

* Whitelist vn jj application  schemas

## v1.46.11

**Date**: 20th Feb 2024  

* Fix appLogo in Patient Portal

## v1.46.10

**Date**: 14th Feb 2024  

* Whitelist tafmek schema

## v1.46.9

**Date**: 8th Feb 2024  

* Resolved permission issue in release workflow
* Removed max_length in client_ip field

## v1.46.8

**Date**: 7th Feb 2024  

* Modified client_ip field type

## v1.46.7

**Date**: 6th Feb 2024

* In sync with hot fixes

## v1.46.6

**Date**: 25th Jan 2024

* Whitelist azkoselugo schema

## v1.46.5

**Date**: 17th Jan 2023

* Fixed in Audit logs table 

## v1.46.4

**Date**: 16th Jan 2023

* Fixed CC Log tables date filter

## v1.46.3

**Date**: 11th Jan 2023

* Whitelist cll schema

## v1.46.2

**Date**: 28th Dec 2023

* Fixed Audit log report

## v1.46.1

**Date**: 13th Dec 2023

* Fix Settings File
  
## v1.46.0

**Date**: 9th Dec 2023

* Celery Tasks Lgging

## v1.45.10

**Date**: 6th Feb 2024

* Changed audit logs changes from str to dict
* Fixed login signup skip alternate step
  

## v1.45.9

**Date**: 25th Jan 2024

* Whitelist azkoselugo schema

## v1.45.8

**Date**: 17th Jan 2024

* Fixed Audit log table date filter

## v1.45.7

**Date**: 28th Dec 2023

* Fixed Audit log report
* Added app timezone in app group details api

## v1.45.6

**Date**: 7th Dec 2023

* Whitelist jjvn schema


## v1.45.5

**Date**: 7th Dec 2023

* ZelthyCubeMixin Exception Bugfix

## v1.45.4

**Date**: 3rd Dec 2023

* Migration File issue

## v1.45.3

**Date**: 3rd Dec 2023

### Fix
* Access Logs implementation Changes for SSO and Open ID


## v1.45.2

**Date**: 28th Nov 2023

### Fix
* Access Logs implementation Changes
* Fixed dropdown search for choices fields
* Removed local static storage for development enviornment
  
## v1.45.1

**Date**: 28th Nov 2023

### Fix
* github repo and owner prefill api changes
  
## v1.45.0

**Date**: 28th Nov 2023

### Feat
* github disable repo and owner edit
* dynamic user restriction
* save method changes for staff user
 
## v1.44.5

**Date**: 15th Nov 2023

### Fix
* Fixed superuser creation
* Removed access data from Accesslogs api

## v1.44.4

**Date**: 14th Nov 2023

### Fix
* Fixed Syntax Issue
  
## v1.44.3

**Date**: 14th Nov 2023

### Fix
* Fixed dropdown options

## v1.44.2

**Date**: 13th Nov 2023

### Fix
* Fixed bugs in accesslogs

## v1.44.1

**Date**: 13th Nov 2023

### Fix
* Added is_login_unsuccessful field in UserAccesslogs

## v1.44.0

**Date**: 11th Nov 2023

### Feat
* Included user restriction for dynamic and admin panel
* Fix accesslogs

## v1.43.0

**Date**: 7th Nov 2023

### Feat
* added excel export with edit restriction in access logs view
* added edit restriction for audit logs excel report

## v1.42.7

**Date**: 6th Nov 2023

### Fix
* added filters in access logs view

## v1.42.6

**Date**: 3rd Nov 2023

### Fix
* Handle request has no tenant issue in CSP Middleware 

## v1.42.5

**Date**: 31st Oct 2023

### Fix
* Fix access logs api view

## v1.42.4

**Date**: 31st Oct 2023

### Fix
* Typo bug in dropdown in table script.
* Fix dropdown filter 

## v1.42.3

**Date**: 30th Oct 2023

### Fix
* Change the username & password field name in the access log middleware

## v1.42.2

**Date**: 30th Oct 2023

### Fix
* Remove file extension from migration dependency (companyusers)

## v1.42.1

**Date**: 30th Oct 2023

### Fix
* Fix user logged-in signal handler

## v1.42.0

**Date**: 27th Oct 2023

### Feat
* Added custom access logs
* Included dropdown filter functionality for ztables.

## v1.41.1

**Date**: 27th Oct 2023

### Fix
* Remove unwanted benefit models from auditlog

## v1.41.0

**Date**: 27th Oct 2023

### Feat
* Registered audit log for the required models

### Fix
* Code corrections in login/signup v2 

## v1.40.1

**Date**: 26th Oct 2023

### Fix
* Updated charfield attributes in PatientStatusesModel

## v1.40.0

**Date**: 25th Oct 2023

### Fix
* Added datetimefield and charfield in PatientStatusesModel
* Updated upload_file method of sftp connector
* Added methods to handle search of datefields in PurchaseSerializationModel & SerializationMasterModel

## v1.39.1

**Date**: 17th Oct 2023

### Fix
* Added gijgo files in assets

## v1.39.0

**Date**: 12th Oct 2023

### Feat
* Replaced external cdn with static files

## v1.38.6

**Date**: 9th Oct 2023

### Fix
* Changed SFTP connector response structure

## v1.38.5

**Date**: 5th Oct 2023

### Fix
* Fixed audit logs report & users report save location issue

## v1.38.4

**Date**: 3rd Oct 2023

### Fix
* Whitelisted onemgnvst004 for CSP

## v1.38.3

**Date**: 2nd Oct 2023

### Fix
* fixed app releases version execution order from lower to higher
* user role creation on frame updation for inital app release

## v1.38.2

**Date**: 27nd Sept 2023

### Feat
* Fixed apostrophe issue in table column names on which sorting is allowed
* Whitelisted India S3 bucket for csp
* Whitelisted tw app ven for csp
  

## v1.38.1

**Date**: 22nd Sept 2023

### Feat
* Fixed Sorting for custom tables where get_context_data is overrided

## v1.38.0

**Date**: 21th Sept 2023

### Feat
* Added SFTP Connector
* Handled New style s3 link for internal module of login signup.
* Added DLT handling in otp sms for login signup

## v1.37.0

**Date**: 20th Sept 2023

### Feat
* Added Patient Profile V2
* Whitelisted 2 schemas for CSP

## v1.36.0

**Date**: 20th Sept 2023

### Feat
* Added v1 of Dynamic Data Models (DDM)

## v1.35.1

**Date**: 20th Sept 2023

### Feat
* Added New application to Whitelist for CSP

  
## v1.34.1

**Date**: 16th Sept 2023

### Fix
* DocuSign connector Fix

## v1.34.0

**Date**: 15th Sept 2023

### Feat
* Added New application to Whitelist for CSP

## v1.33.1

**Date**: 15th Sept 2023

### Feat
* Fixed syntax issue in connector
  

## v1.33.0

**Date**: 15th Sept 2023

### Feat
* Added Docusign connector


## v1.32.0

**Date**: 8th Sept 2023

### Feat
* included `import_app` and `import_app_tasks` management commands to load app configs and tasks

## v1.31.5

**Date**: 5th Sept 2023

### Fix
* Removed order status sorting in ordertable

## v1.31.4

**Date**: 1st Sept 2023

### Fix
* include prod environment in release workflow

## v1.31.3

**Date**: 23th Aug 2023

### Fix
* Fixed searching in audit logs table.
* Removed CC related config models from filter options

## v1.31.2

**Date**: 21th Aug 2023

### Fix
* Handled context switching when searching id in audit logs table.

## v1.31.1

**Date**: 19th Aug 2023

### Fix
* Included missing commit for audit logs table.

## v1.31.0

**Date**: 18th Aug 2023

### Feat
* Included sorting capabilities for ztables.
* Added audit logs table to cloud console.
* App version info now included for apps in cloud console.
* Added LINE connector for sending and syncing messages from LINE messenger.
* Automated deployment support through natural keys and identified the configuration models

## v1.30.1

**Date**: 14th Aug 2023

### Fix
* Fixed Doctor customoption multiselect field bugs

## v1.30.0

**Date**: 11th Aug 2023

### Fix
* Added progressive search in choices field
* Added 70 characters cap in tables cell to show full data on hover
* Fixed some table bugs
* Fixed width of table columns
* Form following Fixes:
    * CheckBoc Allignment
    * Textfield height allignment
    * SHow placeholder for select2 fields
    * Next and Previous button in form changed to Submit

## v1.29.2

**Date**: 7th Aug 2023

### Fix
* Added progressive search in ID column for following models :
    * Sms
    * Email
    * Call Center

* Added fix for empty spaces, alphanumeric and trailing spaces search in order id field.

## v1.29.1

**Date**: 7th Aug 2023

### Fix
* Added fix for empty spaces, alphanumeric and trailing spaces search in id field.

## v1.29.0

**Date**: 4th Aug 2023

### Fix
* Added progressive search for the following models using Zcharfield, ZDatefield and search query :
    * Patient
    * Patient Program
    * Order
    * Hospital
    * Doctor
    * Notes Task


## v1.28.5

**Date**: 28th July 2023

### Fix
* Added ZDateField and search tag to PharmaCoVigil Model extrafield1_date, extrafield2_date and extrafield3_date.


## v1.28.4

**Date**: 27th July 2023

### Fix
* Added CSP Whitelisting for msdqrc and msdqrcommon 


## v1.28.3

**Date**: 20th July 2023

### Fix
* Added backup logic for ip retrieval of celery server for cube.js api

## v1.28.2

**Date**: 18th July 2023

### Fix
* Added pspheresg xp and msdqrc in csp exempted schemas

## v1.28.1

**Date**: 17th July 2023

### Fix
* Multilingual SMS content is accepted in MiTake

## v1.28.0 

**Date**: 14th July 2023

### Feat

* Added release workflow
* The `ZelthyCubeMixin` class streamlines Cube server interaction, handling queries and returning fetched data.
* Special Character also allowed in the SMS(MiTake) Content

## v1.27.0

**Date**: 11 July 2023

### Feat

* MiTake SMS Gateway Integration

# 1.26.1
**Date**: 3rd July 2023
* Whitelisted New Application Tenant for csp

# 1.26.0
**Date**: 1st July 2023
* ``zelthy-migrate`` a management command that efficiently migrates schemas across tenants. It first checks for pending migrations and then performs the necessary migrations in the required tenants.
* This command is part of the deployment workflow for every release.

# 1.25.0
**Date**: 28th June 2023
* added [zelthy-accounts](https://github.com/Healthlane-Technologies/zelthy-accounts) as submodule in which accounts codebase and accounts assets  will be managed and now accounts codebase is seperated from ``zelthy-initium``
* added [zelthy-cubejs](https://github.com/Healthlane-Technologies/zelthy-cubejs) as submodule in which cubejs files will be maintend for all the apps.
* introduced an environment variable ``CUBE_API_SECRET`` for maintaing CubeJS API Secret key
* changes from SG Staging which are required for switching to master branch in SG Staging


# 1.24.4
**Date**: 6th June 2023
* Added googletagmanager and statcounter in csp script whitelisting 

# 1.24.3
**Date**: 6th June 2023
* Revalidated schemas for non csp apps on private pages

# 1.24.2
**Date**: 6th June 2023
* Added lower to email in signup api v2 and edit user v2

# 1.24.1
**Date**: 6th June 2023
* Added Zcharfield to sms models destination number

# 1.24.0
**Date**: 2nd June 2023
* Added Share Point Connector

# 1.23.4
**Date**: 25th May 2023
* Fix for health check URL in CSP Middleware
* Updated button position for uploads view

# 1.23.3
**Date**: 25th May 2023
* Added CSP and HSTS Security validation

# 1.23.2
**Date**: 30th May 2023
* add: support for , in custom view routes

# 1.23.1
**Date**: 25th May 2023
* Reverted CSP Codebase

# 1.23.0
**Date**: 25th May 2023
* Added CSP and HSTS Security validation
* Login Signup version Bump

# 1.22.1
**Date**: 30th Mar 2023
#### Fixes
* Fixed capturing of video call start time

# 1.22.0
**Date**: 24th Mar 2023
* Added User Login Activation and Deactivation Login in Login Signup V2

# 1.21.3
**Date**: 23th Mar 2023
* Fixed Spelling of access_token in zemail open method

# 1.21.2
**Date**: 14th Mar 2023
* Added google fonts in login signup
* Fixed search in order and patient models


# 1.21.1
**Date**: 14th Mar 2023
* Fixed URL pattern of connector webhook


# 1.21.0

**Date**: 11th Mar 2023
* New Login Signup APIs Beta Version
#### Condense Frame Enhancements
* Download hand cursor on hover
* On hover a grey line is visible on table rows
* Space between items in Sidemenu
* Table rows hover effect as per design
* Search box position(adjusted by 8px) in table
* Padding between Columns (increase by 8px)
* Fixed header of table
* Scroll on table headers hidden
* Table and Sidemenu ui ux fix
#### Added Latest Refschema for launching apps from cloud console
# 1.20.0

**Date**: 24th Feb 2023
#### Dynamic Panel Enhancements
* Release notes capture while deploying the code
* Confirmation modal while discarding the local changes
* Task:
    * Search bar to search with all the columns of the table
    * Visual Indicator for Task Status (Enabled/Disabled)
* Route:
    * Search bar to search with all the columns of the table
    * Visual Indicator for Route Is Enabled
    * Search on View File dropdown (Route Create/Edit Form)
* Trigger:
    * Trigger name dropdown searchable in Add trigger Form

# 1.19.2

**Date**: 15th Feb 2023
#### Fixes
* Cloud Console: fix of site variable missing in user invite email for sso enabled user roles

# 1.19.1

**Date**: 14th Feb 2023
#### Fixes
* Updated TimezoneMiddleware to support Au and NZ apps 


# 1.19.0

**Date**: 4th Feb 2023
#### Feature releases
* Connector webhook
* New connector added: Airwallex
* Bug Fix: Auditlog environment API
* Bug Fix: AppUsers environment API

# 1.18.2

**Date**: 28th Jan 2023
#### Fixes
* Create CompanyUser Check for case insesitive Email Address


# 1.18.1

**Date**: 28th Jan 2023
#### Fixes
* Added auditlogs in salesforce models
* excluded customization auditlogs from dev and stag environments
* excluded task_ids attribute from auditlog of ZelthyPeriodicTaskModel 



# 1.18.0

**Date**: 16th Jan 2023
#### Feature releases
* Updated environment APIs to support Connectors
* Introduced Connector module and added support for Gdrive, WhatsApp
* Upgraded AppUser management APIs
Note: Migration is required with this upgrade

# 1.17.3

**Date**: 23th Dec 2022
#### Bug fixes
* OAuth 2.0 SMTP authorization bug fixes

# 1.17.2

**Date**: 17th Dec 2022
#### Bug fixes
* OAuth 2.0 SMTP and Basic SMTP integration bug fixes



# 1.17.1

**Date**: 13th Dec 2022

#### Bug fixes
* OAuth 2.0 SMTP bug fixes

# 1.17.0

**Date**: 9th Dec 2022

#### Feature
* Integrations module to support integration interfacing via Zelthy Cloud Console with third party providers
* Support for oAuth 2.0 based SMTP
* SMTP (Basic) & SMTP (oAuth 2.0) integration support via Zelthy Cloud Console


# 1.16.3

**Date**: 24rd Nov 2022

#### Bug fixes in Condense Legacy
    * Future date in table.
    * Sidebar menu and it's respective submenu remain in same position.
    * Calender in profile details.

# 1.16.2
**Date**: 23rd Nov 2022

* Added missing support for search in datefield, datetimefield of SupplyChainModel.

# 1.16.1
**Date**: 20th Nov 2022

#### Bug fixes
* Rename role selection title while login
* user role timeline fix incase therapy is not mapped
* appusers table fix if datetime format not available in appgroup client config


# 1.16.0
**Date**: 18th Nov 2022

#### Feature
* Fax integration
    * Sending fax to the user
    * Validation of data send as fax
    * Based on the validation status gets updated in portal

# 1.15.1
**Date**: 17th Nov 2022

#### Bug fixes
* Environment: Fixed user report generation

# 1.15.0
**Date**: 11th Nov 2022

* Enhancements in User Report Functionality under the Environment module
    * Report Title, File Name of the report, and Current Role column added
* Introduced an optional parameter in ``z_temp_s3_file_url`` safe function to pass the custom attachment filename for the file which will be downloaded from the pre-signed URL.

# 1.14.2
**Date**: 10th Nov 2022
#### Bug fixes
* Changed Altair condense legacy moment version 2.24.0

# 1.14.1
**Date**: 10th Nov 2022
#### Bug fixes
* Changed Altair condense legacy jquery version


# 1.14.0
**Date**: 7th Nov 2022
#### Features
* New Environment APIs added to support App Workflows including launching app, app detailview, user reports, audit logs etc.

# 1.13.2
**Date**: 1st Nov 2022
#### Bug fixes
* Reverted Altair mirgation static files

# 1.13.1
**Date**: 31st Oct 2022
#### Bug fixes
* Condense Legacy Frame Multi Select, Sidebar Menu and mobile ui fix


# 1.13
**Date**: 31st Oct 2022
* Added jsonfields in AbstractSalesperson Model.
* Added jsonfield in DispensingOptionsModel.


# 1.12.1
**Date**: 27th Oct 2022

#### Bug fixes
* Added vial Return condition in Purchase app to restrict stockist B from dispensing returned vial of stockist A.

# 1.12.0
**Date**: 25th Oct 2022
* Add jsonfield_extra2 in PhlebotomistModel
* Add file_2, extrafield1_date and extrafield2_date in DoctorModel
* Enhanced AuditLog Page in admin panel
    * Removed Create New, Save, Show History and Delete Option
    * Show User Name in Log Entries

#### Bug fixes
* fixed extrafield2 date search in Patient model
* Dynamic Panel: changed gihub list branch API per_page size to 100

# 1.11.6
**Date**: 25th Oct 2022
#### Bug fixes
* Removed the maximum 255 character constraint on the Call Record (extrafield1_text) Model

# 1.11.5
**Date**: 20th Sept 2022

#### Bug fixes
* Fixed SMS ID search
* Added __init__.py in video call migrations folder

# 1.11.4
**Date**: 20th Sept 2022

#### Bug fixes
* Fixed Set password validations

# 1.11.3
**Date**: 16th Sept 2022

#### Bug fixes
* Add Last Password changed date in app users list

# 1.11.2
**Date**: 10th Sept 2022

#### Bug fixes
* save last_login date for devuser sso
* allowed ``:`` and ``.`` in dynamic routes regex


# 1.11.1

**Date**: 7th Sept 2022
#### Bug fixes

* Condense legacy frame fixes:
    * table and form component fixes
    * Add Button for Modal issue fixes
### 1.11
**Date**: 3rd Sept 2022

* Added Video Call Functionality
* Added a json in phlebo model.
* Added multiple files functionality in order 1 and 5 document model


# 1.10.3

**Date**: 1st Sept 2022
#### Bug fixes

* SESSION_COOKIE_SECURE env variable issue
* Disabled browsable API page for DRF APIs

### 1.10.2

**Date**: 8th August 2022

#### Bug fixes
* Order Model extra fields datetime search issue fix

### 1.10.1

**Date**: 8th August 2022

#### Bug fixes
* Formatting issue in noframe head.html

### 1.10.0

**Date**: 5th August 2022

#### **Dynamic Panel**
#### Features

* Functionality for creating, reading and updating the user roles.
* Functionality for frame customisation and creating menus with submenus.
* Frames intgegration with Github
* File Search on Dynamic
### 1.9.6

**Date**: 8th July 2022
#### Bug fixes
* import issue fixed in reset password 

### 1.9.5

**Date**: 11th June 2022
#### Bug fixes
* Login Utils get_therapy method fix

### 1.9.4

**Date**: 11th June 2022
#### Bug fixes
* initial API call of logs on page load moved to on action of opening logs window
* Auto Refresh toggle switch for logs 
### 1.9.3

**Date**: 05th June 2022
#### Bug fixes
* Secrets model decrypter function name

### 1.9.2

**Date**: 31st May 2022
#### Bug fixes
* CodeExec History modal breaks when log item or value is not string
* None Branch is getting passed in git API when gihub auth cookie is expired
* Logs UI Improvement
* Search in multiple formula fields only returns filtered objects of the first formula field search query.

### 1.9.1

**Date**: 08th May 2022
#### Bugfix
* Prevent re-encryption on update

### 1.9.0

**Date**: 06th May 2022
#### Feature
* Introduced EncryptedCharField & EncryptedTextField to store sensitive data after encryption
* Email Configuration will encrypt smpt_password & incoming_password 
* Added a new add "secrets" to store encrypted sensitive data 


### 1.8.5

**Date**: 02nd May 2022
#### Bugfix
* Added logout in allowed_path in admin panel


### 1.8.4

**Date**: 01st May 2022
#### Security Patch & Bugfix
* Blocked restricted table access in production environment
* OpenID login bugfix in app tenant context

### 1.8.3

**Date**: 26th April 2022
#### Security Patches
* Upgrade Django to ``1.11.29`` which contains security patches
* Remove unused lib Pillow

### 1.8.2

**Date**: 24th April 2022
#### Bug Fix
* OpenID router bug fix

### 1.8.1

**Date**: 24th April 2022
#### Bug Fix
* OpenID router bug fix

### 1.8.0

**Date**: 23rd April 2022
#### Features
* Support for OpenID Connect; OpenID Connect integrations available with Microsoft & Google


### 1.7.1

**Date**: 8th April 2022
#### Bug fixes
* added git status icon
* changed highlighted text colour in code search
* Fix for deploying static file which was updated from remote branch 


### 1.7.0

**Date**: 25th March 2022
#### **Dynamic Panel**
#### Features
* Diff viewer for comparing local changes with remote files
* Git Status containing following information 
    * Conflicting files (Files that are updated in the remote branch and have unpushed local changes.)
    * Branch in local is how many commits behind to remote
* Generating Module JSON FIle for a template is now part of components utils ModuleUtils and it can be called from shell or codeexec.
* Depricated languages.xlsx in components folder and now it is part of directly the MODULE_FILE_UTILS for templates.
* For DEV ENV now the cookie consent modal will directly come and developers will not require to add it from console.

#### Bug fixes

* After switching branch updating branch_name in footer 
* Remove unused imports from codeexec task
* Fixed json serializable issue in extra_fields kwargs for report task containing 10k+ rows

### 1.6.3

**Date**: 14th March 2022
#### Bug fixes
* fixed url getting passed as objects in args of excel report function for custom table dynamic views


### 1.6.2

**Date**: 11th March 2022
#### Bug fixes
* fixed exrafields function in kwrargs not serializable issue in excel report task

### 1.6.1

**Date**: 10th March 2022
#### Bug fixes
* Updated worbook close method to save method according to `xlwt` lib in the tenants who are using `initialize_report` of `ExcelReportMixin` .
* kwargs saving in excel report model moved from view to task which ensures serialized kwargs.
* add total_rows in report model in purchase serialization report export view

### 1.6.0
#### Features

* Search functionality for view, trigger and template in Dynamic Panel 
* Footer containing User ID and Connected Branch name in Dynamic Panel
* ```output_file``` field in ```ZelthyAdminCodeExecutionModel``` and helper function to store data in output_file from codeexec.
* self many to many field in serialization master model
* Excel Report Download Enhancements
    * Processing reports in Chunks of 10k rows and after each 10k rows 15 mins of wait time for excel report task
    * Statuses and json_field in report model

#### Bug Fixes

* Trigger objects ordered by creation time while generating meta_data.json to overcome ordering issues in push operation
* view rename bug fix
* angle brackets escaped in codeexec execution history
#### Chores
* Remove unused settings file

### 1.5.3

* Added PyQrcode pip package

### 1.5.2

**Date**: 1st March 2022
#### Bug fixes
* Template Updater Task save missing call added

### 1.5.1

**Date**: 25th Feb 2022
#### Bug fixes
* File content-type preserved in uploading static files to s3 while pulling from Github
* Exception Handling for invalid JSON format in ZelthyDynamicCookie


### 1.5.0

#### Features

* Nosql Module for Zelthy Generic Table to accomodate objects outside predefined models.
* Pull from remote option in Dynamic Panel.
* Compnents Installer and Updater now satisfies the github version structure in all customization models.
* Icon to indicate Github is connected or not in the dynamic panel.
* ZelthySessionAPIView Class introduced so that apis can now use session authentication.

####  Bug Fixes

* Roles Track Json update role int issue.


### 1.4.4
**Date**: 14th Feb 2022
#### Bug fixes
* zcustom templates available to use from codeexec and tasks

### 1.4.3
**Date**: 14th Feb 2022
#### Bug fixes
* Fixed update method of customquery set of abstractusermodel to only work on Users and not other models.

### 1.4.2
**Date**: 8th Feb 2022
#### Bug fixes

* customization-panel: Fixed Github push operation for code containing non-ascii characters
* customization-panel: Route table order by modified time
* Excel export rows limited to ``10000``

### 1.4.1
**Date**: 7th Feb 2022
#### **Customization Panel**
Bug fixes
* Disabled switch branch on page reload
* Fixed error on saving view file while adding non-ascii characters(e.g, thai text)
* ``mimetypes`` import allowed
* Resolved deleted triggers getting executed

Features
* Converted push, switch branch, release and clone to async operations
* Table view for releases
* JWT_SECRET_KEY and CLOUD_MANAGER_TOKEN masking in logger

#### **Core**
* Bug fix for ``ZelthyUpdateView`` not rendering form validations
* Excel export rows limited to ``1000``
* Extrafields in credit transaction model

### 1.4.0
**Date**: 29th Jan 2022
* Introduced Manifest version in App Client Config
* Support for collaborative development on a single app
    * Dev Id & Branch based context on z-IDE
    * Support for released and development versions across models covered under manifest version 1.0 (Views, Templates, Trigger, Routes & Static)
    *  App serving based on context determined by ZelthyDynamicCookie
* README.md to maintain app documentation
* Github Integration with z-IDE
    * Switch to an existing branch
    * See local changes, stash or push
* Cloning Code from existing Versions
    * From latest released version
    * From other Developer context
* Release
    * ZelthyReleaseModel to maintain release history containing information like author, release time, file_changes
* App selector within the same environment
* Visual indicators for Platform Version & Environment

### 1.3.1
**Date**: 26th Jan 2022
### Bug Fixes
* Variable name bug in create company user fixed

### 1.3.0
**Date**: 24th Jan 2022
#### Features
* Integrated django-json-widget in admin.py version 1.1.1
* Added helper functions for roles_track_json to give monthly active users and timeline of roles assigned or revoked
* Login API v1 now returns loggedin session token
### Bug Fixes
* Fixed Bug in Login API for invalid email
* Token in otp 2FA can be sent in either integer or string
* Template Updater Version Check Fixed
### 1.2.2
**Date**: 24th Jan 2022
#### Bug fixes
* zcloudmanager: Fixed referencing of incorrect attribute
* z_temp_s3_file_url: Fixed fpr s3's v4 signature version

### 1.2.1
**Date**: 23rd Jan 2022
#### Bug fixes
* zcloudmanager: Added  imports missed from healthcheck


### 1.2.0
**Date**: 22nd Jan 2022
#### Features
* zcloudmanager: New APIs to get environment details
* zcloudmanager: New APIs to to manage dev users, get application auditlogs, healthchecks
* zelthy_safe_functions: New zelthy_safe_functions to store and retrieve temp file in tenant's media bucket
* registration: superuser restrictions 


### 1.1.1
**Date**: 10th Jan 2022
#### Bug fixes
* customization: Graceful handling of ```zlogger``` Non JSON serializable values
* customization: Handling of invalid route regex
* customization: Handling of duplicate static folder and static files in the same location
* customization: Fix for Periodic task is always getting enabled after creating it.


### 1.1.0
**Date**: 8th Jan 2022
* zcloudmanager: New APIs for list of users & user roles in an environment 
* zcloudmanager: Additional attributes (roles, developers, platform version & git short hash) returned in ZCloudAppApiView

### 1.0.0
**Date**: 5th Jan 2022

* Initial release.
