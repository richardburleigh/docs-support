---
locale: en-us
guid: 33d2b43e-d133-4adf-866d-aaa440fce6de
app_type: traditional web apps, mobile apps, reactive web apps
---

<h1>Platform Server</h1>
<h2 id="Platform_Server_10.0.1115.0">Platform Server 10.0.1115.0</h2>
<div class="info">
<p>Released on Jun 22, 2021</p>
</div>
<h3 id="Bug_Fixing_0">Bug Fixing</h3>
<ul>
<li>[Java Only] Fixed an issue that caused a Java.ArrayIndexOutOfBoundsException error when the expiration date of cookies is set at the exact same time in different requests. (RPM-1189)</li>
</ul>
<h2 id="Platform_Server_10.0.1114.0">Platform Server 10.0.1114.0</h2>
<div class="info">
<p>Released on Jun 21, 2021</p>
</div>
<ul>
<li>Fixed a security issue related to CVE-2019-11358 that could affect the behavior of client-side runtime. CVSSv3.1 score 6.1 (Medium). (RPM-621)</li>
<li>Fixed a security issue related to CVE-2015-9251 that could affect the behavior of client-side runtime. CVSSv3.1 score 6.1 (Medium). (RPM-622)</li>
<li>Fixed a security issue related to CVE-2020-7656 that could affect the behavior of client-side runtime. CVSSv3.1 score 6.1 (Medium). (RPM-623)</li>
<li>Fixed a security vulnerability. CVSSv3.1 score 8.3 (High)." (RPM-657)</li>
<li>Fixed a security vulnerability. CVSSv3.1 score 9.9 (Critical). (RPM-683)</li>
<li>Fixed a security vulnerability. CVSSv3.1 score 8.8 (High). (RPM-786)</li>
<li>Fixed a security vulnerability. CVSSv3.1 score 7.2 (High) (RPM-813)</li>
</ul>
<h2 id="Platform_Server_10.0.1108.0">Platform Server 10.0.1108.0</h2>
<div class="info">
<p>Released on Dec 02, 2020</p>
</div>
<h3 id="Bug_Fixing_1">Bug Fixing</h3>
<ul>
<li>Fixed an issue that caused emails to be sent more than once when there are multiple frontends registered. (RPD-4844)</li>
<li>[Java Only] Updated 3rd party jar libraries due to known vulnerabilities (RPSFCT-55):
<ul>
<li>Commons-collections</li>
<li>Guava</li>
<li>Sanselan-incubator</li>
<li>jackson</li>
</ul>
</li>
<li>Fixed a security vulnerability. CVSSv3.1 score 5.4 (Medium). (RPD-4842)</li>
<li>Fixed a security issue that allowed access to private information. CVSSv3.0 score 5.3 (Medium). (RPD-4670)</li>
<li>Fixed a security issue that allowed an attacker to perform DoS attacks by submitting feedback requests. CVSSv3.0 score 5.8 (Medium). (RTAF-3479)</li>
</ul>
<h2 id="Platform_Server_10.0.1106.0">Platform Server 10.0.1106.0</h2>
<div class="info">
<p>Released on Sep 24, 2020</p>
</div>
<h3 id="Bug_Fixing_2">Bug Fixing</h3>
<ul>
<li>Fixed the ListClear action so Traditional Web Apps transfer less data between the server and web browser. This improves the data transfer optimization mechanism. (RTAF-3335)</li>
<li>Fixed a security vulnerability. CVSSv3.1 score 7.4 (High). (RTAF-3379)</li>
</ul>
<h2 id="Platform_Server_10.0.1104.0">Platform Server 10.0.1104.0</h2>
<div class="info">
<p>Released on Aug 11, 2020</p>
</div>
<ul>
<li>Fixed a security vulnerability. CVSSv3.1 score 7.4 (High). (RTAF-2226)</li>
</ul>
<h2 id="Platform_Server_10.0.1102.0">Platform Server 10.0.1102.0</h2>
<div class="info">
<p>Released on Jul 27, 2020</p>
</div>
<ul>
<li>Fixed a security vulnerability. CVSSv3.0 score 9.6 (RPD-5160)</li>
</ul>
<h2 id="Platform_Server_10.0.1100.0">Platform Server 10.0.1100.0</h2>
<div class="info">
<p>Released on May 28, 2020</p>
</div>
<h3 id="New_in_Platform_Server_10.0.1100.0">New in Platform Server 10.0.1100.0</h3>
<ul>
<li>[.NET Only] Upgraded Oracle Data Provider for .NET, Managed driver to version 19.3.1. According to the <a href="https://docs.oracle.com/en/database/oracle/oracle-database/19/odpnt/InstallSystemRequirements.html#GUID-A6405CAD-C0E9-45E0-9C38-26B7ED214479">official documentation</a>, this driver allows applications to connect to Oracle Database 11g Release 2 or later.<b>If you have integrations with earlier versions of Oracle Database, they will not work. You will need to upgrade your Oracle engine to version 11g Release 2 or later, in order to continue using those integrations.</b> This driver supports native encryption, meaning that you can set up your database to require encryption and this means all connections will be encrypted between the server and the database (applicable for the platform and external databases). (RSAT-2115)</li>
<li>[.NET Only] Added support for Oracle 18c. This applies to the platform database, as well as external databases. (RSAT-2308)</li>
<li>[.NET Only] Added support for Oracle 19c. This applies to the platform database, as well as external databases. (RSAT-2309)</li>
</ul>
<h3 id="Bug_Fixing_3">Bug Fixing</h3>
<ul>
<li>[.NET Only] Fixed an issue that was blocking the generation of mobile apps in some specific cases. (RLIT-3508)</li>
<li>[.NET Only] Fixed issue causing Solution Report link to now be visible in Solution_Edit screen if the solution is downloaded after the publish (RLIT-3536)</li>
<li>[.NET Only] Fixed a concurrency issue executing BPT processes that generate an error of the type "PROCEDURE ddl_NUMBER already exist" (RSAT-2121)</li>
<li>[.NET Only] Fixed an error that stopped publishing a solution with more than 1000 Modules in an environment with an Oracle platform database. (RPD-4773)</li>
</ul>
<h2 id="Platform_Server_10.0.1023.0">Platform Server 10.0.1023.0</h2>
<div class="info">
<p>Released on Apr 02, 2020</p>
</div>
<h3 id="Bug_Fixing_4">Bug Fixing</h3>
<ul>
<li>Fixed an error that showed when using the Rich Widgets Pop-Up pattern with the List Bulk Select widget, where a link/button triggered a pop-up and had the link/button associated with the List Bulk Select widget. (RTAF-2062)</li>
<li>Fixed multiple executions of Screen Preparation Action that occurred when Rich Widgets File Upload was used in the Screen. (RTAF-2064)</li>
<li>Fixed the triggering of the onclick event with a Rich Widget Popup Editor on a Screen/Block that would cause the onclick event handlers of its parents to trigger during the screen rendering. (RTAF-2089)</li>
<li>Fixed an issue that caused a link that should open a popup window would not work depending of the order of the widgets. (RTAF-2216)</li>
<li>Fixed a security vulnerability. CVSSv3.0 score 9.1 (Critical). (RLIT-3368)</li>
<li>Fixed an issue in LifeTime Deployment API v1 that was preventing to tag a mobile application using the native platform name, e.g. Android (v1). (RLIT-3395)</li>
<li>We improved the Error_Log screen search experience by allowing you to reduce the timeouts in large factories. You can now use a checkbox to enable the search of the stack trace, as it's no longer enabled by default. (RPD-2538)</li>
<li>Fixed issue in LifeTime that prevented on-premises environments registered in Cloud Infrastructure to sync properly due to multiple users with a specific Administrator role. (RPD-3582)</li>
<li>Fixed error when invoking SOAP web services with Integrated Authentication, when the Platform Database is configured to use Windows Authentication. (RSBO-1317)</li>
</ul>
<h2 id="Platform_Server_10.0.1021.0">Platform Server 10.0.1021.0</h2>
<div class="info">
<p>Released on Jan 20, 2020</p>
</div>
<h3 id="Bug_Fixing_5">Bug Fixing</h3>
<ul>
<li>Fixed an error that showed that triggered an onclick event when a nested Rich Widget Popup Editor was present. (RTAF-2089)</li>
</ul>
<h6>Note</h6>
<ul>
<li>A change in Rich Widgets in Platform Server 10.0.1021.0 causes a broken reference when creating a new module. Please upgrade to Service Studio 10.0.1022.0 to avoid the issue.</li>
</ul>
<h2 id="Platform_Server_10.0.1020.0">Platform Server 10.0.1020.0</h2>
<div class="info">
<p>Removed from availability on Jan 20, 2020</p>
</div>
<h3 id="Bug_Fixing_6">Bug Fixing</h3>
<ul>
<li>Fixed an error that showed when using the Rich Widgets Pop-Up pattern with the List Bulk Select widget, where a link/button triggered a pop-up and had the link/button associated with the List Bulk Select widget. (RTAF-2062)</li>
<li>Fixed the multiple executions of Screen Preparation Action that occurred when you used Rich Widgets File Upload in the Screen. (RTAF-2064)Known Issues</li>
<li>In Screens or Blocks with a nested Popup_Editor Rich Widget, the onclick event handlers of its parents can be triggered during the screen rendering, leading to unexpected runtime behavior.</li>
</ul>
<h3 id="Known_Issues_0">Known Issues</h3>
<ul>
<li>In Screens or Blocks with a nested Popup_Editor Rich Widget, the onclick event handlers of its parents can be triggered during the screen rendering, leading to unexpected runtime behavior.</li>
</ul>
<h2 id="Platform_Server_10.0.1019.0">Platform Server 10.0.1019.0</h2>
<div class="info">
<p>Removed from availability on Jan 17, 2020</p>
</div>
<h3 id="New_in_Platform_Server_10.0.1019.0">New in Platform Server 10.0.1019.0</h3>
<ul>
<li>Added new environment security options to force Secure and SameSite properties in cookies generated by the platform. Check the document <a href="https://success.outsystems.com/Support/Enterprise_Customers/Maintenance_and_Operations/Upcoming_changes_in_cookie_handling_in_Google_Chrome#Release_schedule">Upcoming changes in cookie handling in Google Chrome</a> for more information. (RPC-502)</li>
</ul>
<h3 id="Bug_Fixing_7">Bug Fixing</h3>
<ul>
<li>Fixed a compiler crash when introspecting the database index without the corresponding column. This fix makes the staging of apps between environments more resilient. (RPD-4602)</li>
<li>Fixed JPEG images in E11. An invalid content-type response header caused this. (RPD-4591)</li>
<li>Solved issue with concurrent calls to stored procedures in MySQL when AutoCommit is On. (RPD-4449)</li>
<li>Fixed an issue preventing users of different tenants from submitting feedback. (RPD-4419)</li>
<li>Fixed a security vulnerability. CVSSv3.0 score 7.6 (High). (RPD-4310)</li>
<li>[.NET Only] Fixed Platform Server license becoming invalid after the machine restarts in recent versions of Windows due to the change of the serial number. (RPD-4216)</li>
<li>[.NET Only] Fixed the Service Center application pool crashes in error request scenarios. (RPD-4486)</li>
<li>[.NET Only] We fixed a memory performance issue related to Aggregates, SQL elements, and Entity Actions. The connection objects in the generated source code by the platform are now correctly disposed of and do not take up the resources. (RPD-4443)</li>
<li>[.NET Only] Fixed compilation when an effective user provider was not included in a solution. Errors were thrown in Compilations of "Users" and any module with "Users" as user provider when "User" had another module as effective user provider. (RPD-4361)</li>
<li>[.NET Only] Fixed the error "Circular attribute group reference" when executing the XMLDocument_Load action of the Xml extension. (RPD-3742)</li>
<li>[.NET Only] Fixed the scenarios where the "Add Query Origin to Generated SQL" setting wasn't applied. (RSBO-498)</li>
<li>[Java Only] Fixed the inefficient performance of getXMLGregorianCalendar method. (RPD-4401)</li>
</ul>
<h3 id="Known_Issues_1">Known Issues</h3>
<ul>
<li>When using the File Upload Rich Widget in a Screen that includes assigns to local variables shared between Preparation and OnNotify actions, Preparation runs multiple times, which may result in data corruption or unexpected runtime behavior.</li>
</ul>
<h2 id="Platform_Server_10.0.1016.0">Platform Server 10.0.1016.0</h2>
<div class="info">
<p>Released on Aug 14, 2019</p>
</div>
<h3 id="New_in_Platform_Server_10.0.1016.0">New in Platform Server 10.0.1016.0</h3>
<ul>
<li>The installation checklist now includes the instructions to disable Adaptive Optimizer features (OPTIMIZER_ADAPTIVE_PLANS, OPTIMIZER_ADAPTIVE_STATISTICS) in Oracle 12c R2. (RSAT-1623)</li>
<li>Downloading a mobile app by scanning the QR code in Service Studio is now possible on iOS 13. (RTAF-628)</li>
</ul>
<h3 id="Bug_Fixing_8">Bug Fixing</h3>
<ul>
<li>Fixed a security vulnerability. CVSSv3.0 score 7.5 (High). (RNMT-2812)</li>
<li>Fixed a security vulnerability. CVSSv3.0 score 7.2 (High). (RPD-4260)</li>
<li>Fixed misbehavior when using confirmation message with pop-up editor screens. (RPD-4242)</li>
<li>Fixed an issue that prevented mobile applications from loading in Production environments when a producer module was published in Debug mode. (RPD-3596)</li>
<li>[.NET Only] Updated Oracle driver (ODAC) to version 12.2c Release 1. (RPD-4251)</li>
<li>[Java Only] Fixed Error Message and Stack being returned to the browser in Ajax Requests in Internal Errors. (RPD-4295)</li>
</ul>
<p> </p>
<p><b>Disclaimer: </b><i>QR CODE is a registered trademark of Denso Wave Incorporated.</i></p>
<p> </p>
<h2 id="Platform_Server_10.0.1014.0">Platform Server 10.0.1014.0</h2>
<div class="info">
<p>Released on Jul 11, 2019</p>
</div>
<h3 id="New_in_Platform_Server_10.0.1014.0">New in Platform Server 10.0.1014.0</h3>
<ul>
<li>Added a new option in the "Single Sign-On" tab in Service Center. It allows you to bootstrap the admin password for the user provider. (RLIT-2571)</li>
<li>The Platform Server installation, update or upgrade now requires a password for the Platform Server admin user:<br/>
— Use the Configuration Tool to define the password<br/>
— If you have any installation automation, you must <a href="https://success.outsystems.com/Documentation/10/Setting_Up_OutSystems/Unattended_Installation_and_Upgrade/server.hsconf_Configuration_File_Reference"> update the server configuration file </a> (server.hsconf) or command-line options and arguments<br/>
— Check <a href="https://success.outsystems.com/Support/Enterprise_Customers/Maintenance_and_Operations/No_default_credentials_in_Platform_Server">No default credentials in Platform Server</a> for more information. (RSAT-1346)</li>
</ul>
<h3 id="Bug_Fixing_9">Bug Fixing</h3>
<ul>
<li>Fixed an issue that could cause a user with the correct set of permissions to fail to publish using Integration Studio. Instead, they would get the following error "You don't have enough permissions over the database connections that own the following external entities." (RPD-4162)</li>
<li>Improved queries using a full join in LifeTime deployment validation stage. Affects only Oracle and SQL Server. (RPD-4147)</li>
<li>Fixed a permission error that caused users with Change &amp; Deploy permissions to be unable to publish a new extension with database connection entities. (RPD-4103)</li>
<li>Improved the performance of the Process Monitoring page in environments with a large number of activities. (RPD-4080)</li>
<li>[.NET Only] Fixed a rare 'The process cannot access the file' error that occurred during deployments. (RPD-4166)</li>
<li>[.NET Only] Fixed an issue that could cause applications not to deploy automatically, when starting the Deploy Service. (RSCT-1761)</li>
<li>[.NET Only] Fixed ListBox widget variable being empty inside OnChange handler in specific scenarios. (RPD-3983)</li>
<li>[Java Only] Adds a timeout parameter to WebLogicDeployer to prevent deadlocks during deployment operations due to Weblogic bug with Progress object. (RPD-4065)</li>
</ul>
<h2 id="Platform_Server_10.0.1010.0">Platform Server 10.0.1010.0</h2>
<div class="info">
<p>Released on May 03, 2019</p>
</div>
<h3 id="New_in_Platform_Server_10.0.1010.0">New in Platform Server 10.0.1010.0</h3>
<ul>
<li>Improved the experience of the Users application. We gave it a new look and feel and made the following usability improvements:<br/>
— Page-specific links/actions were moved to inside the pages; the sidebar will now only display fixed links and recent items<br/>
— Added breadcrumbs to pages and pagination and records counter to all pages showing lists<br/>
— Added text filter in users sub-lists<br/>
— When a user does not have a username defined it appears as "Not Defined" in the lists so that you can click it<br/>
— Roles, Groups and Users dropdowns don't show the records already added to the lists; however, roles still show when they were inherited by group to allow overriding<br/>
— When a role is inherited by a group, it does not show the option to remove the role, since this operation is not possible<br/>
— Added the list of users able to access the application to the Application_List page – inspired by <a href="https://www.outsystems.com/ideas/4962/Users+Application+Bugs%2fImprovements">Rebecca Hall's idea</a> (RLIT-2343)</li>
<li>Minor improvements in Users font and UI. (RLIT-2592)</li>
<li>Added to FactoryConfiguration the option to include X-Content-Type-Options header with nosniff as a method of preventing MIME sniffing from older browser versions. (RRCT-2270)</li>
</ul>
<h3 id="Bug_Fixing_10">Bug Fixing</h3>
<ul>
<li>Fixed an issue that caused Service Center to crash when changing the configuration of a mobile application. (RLIT-2490)</li>
<li>Fixed an issue in the Spanish translation of RichWidgets. (RPD-3132)</li>
<li>Fixed runtime error in client-side Aggregates with dynamic Order By's containing more than one attribute. (RSBO-54)</li>
<li>The MABS version tag of a mobile application is now correctly updated in Service Center for all environments, including the ones not connected to LifeTime. (RPD-3851)</li>
<li>Fixed query errors in some Users screens. (RPD-4015)</li>
<li>Fixed an issue in AddAttributeToHtmlTag action that could lead to an ArgumentOutOfRange exception in runtime. (RPD-3931)</li>
<li>Fixed a security issue that could cause session ids to be leaked with access to the Platform logs. CVSSv3.0 score 4.9 (Medium). (RRCT-2277)</li>
<li>Fixed incorrect duration in some scheduler error logs. (RPD-3993)</li>
<li>Fixed a problem when using ListAppend and ListInsert functions containing an If expression in the List input parameter. (RPD-3984)</li>
<li>[.NET Only] Fixed a lock on a file by Compiler Service after a second stage compilation error in Service Studio publication. (RPD-4024)</li>
</ul>
<h2 id="Platform_Server_10.0.1005.2">Platform Server 10.0.1005.2</h2>
<div class="info">
<p>Released on Mar 04, 2019</p>
</div>
<h3 id="New_in_Platform_Server_10.0.1005.2">New in Platform Server 10.0.1005.2</h3>
<ul>
<li>We improved the experience of the Users application.<br/>
We gave it a new look and feel and made the following usability improvements:<br/>
— Page-specific links/actions were moved to inside the pages, leaving the sidebar displaying fixed links and recent items only<br/>
— Added breadcrumbs to the pages for better guidance<br/>
— Added pagination and records counter to all lists (Users, Groups, Applications and sub-lists)<br/>
— Added text filter in users sub-lists<br/>
— When a user does not have a username defined it appears as "Not Defined" in the lists so that you can click it<br/>
— Roles, Groups and Users dropdowns don't show the records that are already added to the lists (however, roles still show when they were inherited by group to allow overriding)<br/>
— When a role is inherited by a group, it does not show the option to remove the role, since this operation is not possible<br/>
— Added the list of users able to access the application to the Application_List page – inspired by <a href="https://www.outsystems.com/ideas/4962/Users+Application+Bugs%2fImprovements">Rebecca Hall's idea</a> (RLIT-2343)</li>
<li>When configuring a mobile application, it is now possible to choose the version of the Mobile Apps Build Service (MABS) that will be used to generate the mobile app package. (RNMT-2296)</li>
<li>Added a new action Session_GetWebAppLoginInfo to the PlatformRuntime API that allows you to get user information in advanced REST authentication scenarios. (RRCT-2274)</li>
<li>The VerifySqlLiteral action from Sanitization API was deprecated in favor of BuildSafe_InClauseIntegerList and BuildSafe_InClauseTextList. These new actions are available in Platform Server 10.0.1005.0 and in the upcoming O11 Platform Server Release Apr.2019. (RRCT-2108)</li>
<li>[Java Only] Added support for OpenJDK. (RSAT-1168)</li>
<li>Added to FactoryConfiguration the option to include X-Content-Type-Options header with nosniff as a method of preventing MIME sniffing from older browser versions. (RRCT-2270)</li>
</ul>
<h3 id="Bug_Fixing_11">Bug Fixing</h3>
<ul>
<li>The User_Login action of the Users API no longer logs errors when the authentication is set to Active Directory or LDAP and the login is successful. (RLIT-2387)</li>
<li>Fix an issue that would prevent Service Center from installing when "Force HTTPS for screens in Web Applications" and "Enable HTTP Strict Transport Security (HSTS)" settings were enabled and the application server was configured to receive a Fully Qualified Domain Name (FQDN) in the HTTPS port. (RSAT-627)</li>
<li>Fixed an image rendering issue in Image widgets using binary data when Content Security Policy (CSP) is enabled. (RRCT-2186)</li>
<li>The User_Login action of the Users API no longer aborts database transactions when an exception occurs. (RRCT-2189)</li>
<li>Fixed a bug that allowed Light Processes to have Input Parameters but would cause a compilation error when publishing. (RPD-3358)</li>
<li>Fixed an issue that created multiple BPT processes in case of error when the Scheduler was committing a database transaction. (RPD-3759)</li>
<li>Fixed a rare runtime error while running Aggregates when the Entity internal name was a reserved keyword. (RSBO-29)</li>
<li>Fixed SAP introspection corruption that prevented you from consuming some methods dealing with multi-level tables. (RPD-3773)</li>
<li>Fixed an issue that was closing the DatePicker widget on iOS devices in web applications. (RPD-3852)</li>
<li>Fixed the deployment error "Could not find a part of the path" that appeared when publishing a solution through OSPTool when eSpaces were moved across database catalogs. (RPD-3863)</li>
<li>Fixed an issue when choosing "Mark Hotfix as Solved" for mobile apps if the application hadn't been deployed to the next environment yet. (RPD-3871)</li>
<li>Fixed JavaScript errors when using non-default locales. (RPD-3959)</li>
<li>Fixed issue in LifeTime when downloading a specific Application Version. (RLIT-2416)</li>
<li>Fixed a security vulnerability. CVSS v3.0 score 7.1 (High) - Full details to be released in May 2019 (RLIT-2388)</li>
<li>Fixed a security vulnerability (reported by Mina Edwar from Verizon). CVSS v3.0 score 8.1 (High) - Full details to be released in May 2019 (RPD-3849)</li>
<li>Fixed a rare over-optimization issue occurring in implicit conversions for List Records. (RSCT-1705)</li>
<li>[.NET Only] Fixed issue where "_" (underscore) characters were removed from email attachment filenames. (RPD-3690)</li>
<li>[Java Only] Improved application logging performance in Java. (RPD-3738)</li>
<li>[Java Only] Database sessions are no longer created for BPT activities. (RPD-3835)</li>
<li>Fixed an issue with Input_AutoComplete being triggered in IE11 due to an unexpected 'keydown' event. (RPD-3866)</li>
</ul>
<h2 id="Platform_Server_10.0.1001.0">Platform Server 10.0.1001.0</h2>
<div class="info">
<p>Removed from availability on Feb 12, 2019</p>
</div>
<h3 id="New_in_Platform_Server_10.0.1001.0">New in Platform Server 10.0.1001.0</h3>
<ul>
<li>When configuring a mobile application, it is now possible to choose the version of the Mobile Apps Build Service (MABS) that will be used to generate the mobile app package. (RNMT-2296)</li>
</ul>
<h3 id="Bug_Fixing_12">Bug Fixing</h3>
<ul>
<li>Fixed a runtime error occurring when a List Box is inside a Table Records. (RAFT-1703)</li>
<li>The information on the available database storage for cloud environments is now showing correctly. (RPD-3432)</li>
<li>Fixed an issue that was causing the error "Duplicate is not a valid operation inside a StartIteration/EndIteration block" when using cached actions. (RPD-3698)</li>
<li>Fixed an issue in the Oracle driver that was preventing to abort a query when a HTTP request timeout occurred while session data was being manipulated. (RPD-3726)</li>
<li>Fixed an issue that caused JSON Deserialize to fail when deserializing Null DateTimes "1900-01-01T00:00:00" in Mobile Devices with Negative Timezones offsets. (RPD-3661)</li>
<li>Fixed an issue that was changing the strings within brackets passed to an SQL element via an expand inline parameter. (RPD-3565)</li>
<li>Queries to LDAP can now fallback to LdapConnection objects when using basic authentication. (RPD-3624)</li>
<li>App Feedback application is now more resilient to feedback submitted from screens having frames injected dynamically or resources with zero content length. (RPD-3588)</li>
<li>Fixed an issue that was causing high memory consumption when using complex structures with several lists. (RPD-3633)</li>
<li>Added X-Content-Type-Options header with nosniff to prevent MIME sniffing from older browser versions. (RPD-2812)</li>
<li>Now the system entities in the Oracle databases create the correct indexes for primary keys of the Text type. (RPD-3528)</li>
<li>Publishing a module with TrueChange errors in View Data aggregated attributes no longer causes a compilation error. (RPD-3568)</li>
<li>Users module now allows Basic Authentication using LDAP. (RPD-3557)</li>
<li>We improved the stability of Service Studio by fixing an occasional crash related to the Run Server Action node. (ABE-1352)</li>
</ul>
<h2 id="Platform_Server_10.0.912.1">Platform Server 10.0.912.1</h2>
<div class="info">
<p>Released on Dec 20, 2018</p>
</div>
<h3 id="New_in_Platform_Server_10.0.912.1">New in Platform Server 10.0.912.1</h3>
<ul>
<li>Removed the obsolete referrer directive from the Content Security Policy (CSP) configuration screens. (RLIT-2270)</li>
<li>Added more information in ApplicationVersion structure in LifeTime Deployment API. (RLIT-2168)</li>
<li>Added support for Version Code in mobile applications. (RLIT-2106)</li>
<li>Added support for MySQL 5.7 as database and integration database. (RSAT-1066)</li>
<li>Added a comment in the generated SQL of Advanced Queries and Aggregates with the location of the query in OutSystems applications. Configurable using Factory Configuration. Inspired by <a href="https://www.outsystems.com/ideas/4817/reverse-tracking-sql" rel="external nofollow" target="_blank">Neil Munro's idea</a>. (ABE-1151)</li>
</ul>
<h3 id="Bug_Fixing_13">Bug Fixing</h3>
<ul>
<li>Fixed high database load caused by the "GetDevEffort" query during LifeTime synchronization operations. (RPD-3542)</li>
<li>Fixed the default browser behavior to ask to save the login credentials. Now the password fields in OutSystems applications such as Service Center or LifeTime have the "autocomplete" property set to "off" by default. (RPD-3464)</li>
<li>Fixed PerformanceMonitoring API returning a TTLB (Time To First Byte) value lower than the TTFB (Time To Last Byte) value for Submit requests. (RPD-3497)</li>
<li>Fixed server stackoverflow in Ajax request (RPD-3504)</li>
<li>Fixed the problem in concurrent execution of two screens preventing the navigation from working after fast navigating the mobile application. (RPD-3505)</li>
<li>User information is no longer propagated in BPT actions (e.g. ActivityClose) when the process is defined in a module with a different User Provider. (RRCT-1969)</li>
<li>Single line comments in Advanced Queries no longer break its behavior when not right at the start of the line. (RPD-892)</li>
<li>Fixed the lifetime bootstrap process that was failing in white labeling environments. (RPD-3523)</li>
<li>Fixed issue that prevented unblocking operations on blocked IP Addresses in the Users application when using Oracle as the database platform. (RPD-3537)</li>
<li>Fixes issue with Oracle driver not being able to abort a query when a HTTP request timeout occurs. (RPD-3426)</li>
<li>Fixed Ajax Request failing when WebScreen has multiple HTML Forms (RPD-3558)</li>
<li>Fixed DB connections not being listed in the extension configuration when the server has more 100 connections (RPD-3571)</li>
<li>Fixed Feedback Message in Screen Preparation being shown twice. (RPD-3516)</li>
<li>Fixed issue that prevents setting an empty Timer schedule. (RPD-3580)</li>
<li>In modules with multi-tenant tables, the compilation time no longer scales with the number of existing tenants. (RPD-3085)</li>
<li>Fixed issue in LifeTime that prevented a user with 'Reuse &amp; Monitor' role to validate a deployment plan. (RPD-3480)</li>
<li>Fixed an issue that was preventing the restore of LifeTime communication with an environment after changing the environment properties. (RLIT-2216)</li>
<li>Some previously missing administrative operations are now allowed in on-premises environments in hybrid infrastructures. (RPD-3449)</li>
<li>Changing the password of the current logged in user now requires typing the current password. (RLIT-2237)</li>
<li>Fixed message when there was an invalid request while creating a deployment. (RLIT-2250)</li>
<li>Service Center "Publish All Consumers" button now publishes only the consumers that have references to the producer module on the current running version. (RPD-3355)</li>
<li>Fixed broken links in the Users Application. (RPD-3055)</li>
<li>Fixed broken links in the Users Application. (RPD-2833)</li>
<li>The Users application now shows the correct number of users with a role in an application. (RLIT-2274)</li>
<li>Fixed security issue in LifeTime that allow a user to change its own username. (RPD-3595)</li>
<li>Fixed a problem that caused a horizontal list with 3 elements to have the first and last elements missing in runtime (RPD-3489)</li>
<li>Fixed OsVisitor cookies changing value when the browser is closed and reopened (RPD-3590)</li>
<li>You can now set OutSystems to reject the requests for non-supported image formats. In "Factory Configuration" Forge component, go to Security and check the option "Enforce Valid Image Formats on Image and Binary Endpoints". The valid image formats are GIF, PNG, and JPEG. The setting applies to the images the end-users upload through the applications created in OutSystems. (RRCT-2002)</li>
<li>Added X-Content-Type-Options header with nosniff to prevent MIME sniffing from older browser versions (RPD-2812)</li>
<li>Fixed error parsing JSON request when mobile app upgrade was rolled back (RPD-3118)</li>
<li>Fixed a bug that caused the execution of queries with the inline comment syntax to fail when used in the Service Studio SQL tool. (ABE-1216)</li>
<li>Fixed the "Expected ';'" JavaScript error that appeared after an AJAX Refresh in some scenarios. (RPD-3511)</li>
<li>Fixed a performance issue in .Net clients and Oracle Database that affected the publishing process of the modules with many tenants and multi-tenancy tables. (RPD-3440)</li>
<li>Fixed error when publishing a mobile module about a 'precache.manifest' file not found. (RSCT-1638)</li>
<li>Support Oracle July 2018 Security Patch. (RPD-3487)</li>
<li>Fixes HarvestAndGroupData timer when there is more than one environment with monitoring enabled. (RPD-3600)</li>
<li>Fixed an issue with the compiler optimizer that sometimes caused long compilation times. (RSCT-1302)</li>
<li>Fixed SAP connection testing in Service Center that always failed with an invalid login error. (RPD-3847)</li>
</ul>
<h2 id="Platform_Server_10.0.904.0">Platform Server 10.0.904.0</h2>
<div class="info">
<p>Released on Sep 25, 2018</p>
</div>
<h3 id="New_in_Platform_Server_10.0.904.0">New in Platform Server 10.0.904.0</h3>
<ul>
<li>The time-out for building mobile applications has been increased to 30 minutes, once you launch it from Service Studio. (RLIT-2095)</li>
<li>The millisecond precision has been added to the getdate() function for the MySQL databases. This enables the timers relying on getdate() to properly restart on demand. (RPD-3421)</li>
<li>The logs of the query errors from Aggregates and Advanced SQL now contain more details. (RRCT-1918)</li>
<li>We improved the way mobile apps save information when put in background or after being closed. This prevents a known iOS issue that causes the deletion of the local storage when the device is running low on free space. (RRCT-1973)</li>
<li>Added support for Red Hat Enterprise Linux 7 with JBoss 6 EAP as the application server. (RSAT-1028)</li>
</ul>
<h3 id="Bug_Fixing_14">Bug Fixing</h3>
<ul>
<li>Fixed application data displayed on LifeTime Analytics. (RPD-3513)</li>
<li>Fixed a path-related bug that broke compilation of style sheets in mobile apps with Resources in subdirectories. (RRCT-1951)</li>
<li>Fixed a bug that caused invalid generation of the CSP HTTP headers when using the default values from the Service Center settings. This prevented a small number of iOS apps from loading after the splash screen. (RRCT-1979)</li>
<li>Fixed a bug that prevented CSP violation logs from reaching the endpoint specified by the report-to header field. Now the violation logs are saved properly. (RRCT-1982)</li>
<li>Fixed a bug that caused the processing of error logs to fail with long Action names. (RPD-1769)</li>
<li>Fixed the bug that caused "Could not login to 127.0.0.1" error while publishing the "Current Running Version" of a Solution in Service Center. This caused issues in some upgrades. (RPD-2415)</li>
<li>Fixed the performance issue of "Exporting LifeTime data to Development as sample data" in LifeTimeSDK. (RPD-3388)</li>
<li>Fixed an issue that caused the configuration of the internal network to block the access from the IP sources that match both the trusted proxies addresses and the internal network addresses. (RPD-3391)</li>
<li>Fixed the default browser behavior to ask to save the log-in credentials. Now the password fields in OutSystems applications such as Service Center or LifeTime have the "autocomplete" property set to "off" by default. (RPD-3464)</li>
<li>Fixed the bug that caused "Cannot read property 'type' of null" JavaScript error when removing a radio button via Ajax. (RPD-3490)</li>
<li>Fixed the compilation of resources files when the Target Directory starts or ends with '/' (RRCT-1903)</li>
<li>Fixed the bug that caused the “Continue Deployment” button not to show in LifeTime. It occurred in some scenarios when multiple users were logged-in to the same Staging_Progress page. (RPD-3290)</li>
<li>Fixed a wrong message in the LifeTime staging. The users now see the correct message “you have no permission to deploy” instead of the incorrect “you have no permissions to tag”. (RPD-3319)</li>
<li>Fixed the bug in the French translation (fr-FR) for RichWidgets that prevented the Feedback Message from being displayed. (RPD-3252)</li>
<li>Fixed the bug in LifeTime Analytics that prevented actions with long names to appear in the Screen Details. (RPD-3427)</li>
<li>Fixed a navigation error in accessing the environment change log when the environment is not defined. (RLIT-2205)</li>
<li>Fixed the LifeTime error screen that shows when users try to access Security with this feature not enabled for the environment. (RLIT-2196)</li>
<li>Fixed the error message in LifeTime Deployment API about unsuccessful request for the Create Version call. (RLIT-2195)</li>
<li>Fixed the LifeTime error screen that users without the correct permissions see when attempting to access Permissions of an application. (RLIT-2194)</li>
<li>Fixed the name of the export file obtained after clicking the "Export to Excel" link from the Integrations Log page in Service Studio. (RLIT-2153)</li>
<li>Fixed the LifeTime error screen related to the missing user session. (RLIT-2191)</li>
<li>Fixed the spacing between the links on the Tenant tab of the eSpace details screen. (RLIT-2193)</li>
<li>Fixed an error in accessing the LifeTime audits when a username is not defined. (RLIT-2190)</li>
<li>Fixed an error that happened after choosing the Synchronise Now option from an Environment in LifeTime, in cases where the user didn't have the correct permissions. (RLIT-2189)</li>
<li>Fixed a bug related to checking the Nativiser status that caused LifeTime to crash. (RLIT-2188)</li>
<li>Fixed the Service Center mobile request logs so they now have a unit of time. (RLIT-2170)</li>
<li>Fixed invalid login error when using Integrated Authentication for both database and web service consumption. (RPD-3417)</li>
<li>Fixed an error related to the generation of the application icons when uploading an icon or creating a solution by uploading an OSP or OAP. (RPD-3444)</li>
<li>Fixed the deletion of Oracle Hints from the queries passed by the input parameters to the SQL Tool. (RPD-3457)</li>
<li>Fixed Service Center so it now ignores the database incoherences that can cause timers to appear to be running indefinitely. (RPD-2999)</li>
<li>Fixed an inconsistency in the Null binary parsing when serialized. Now a Null binary returned by server actions is always serialized to '{}'. (RRCT-1968)</li>
<li>Fixed an issue where database images containing trailing white spaces were not being rendered. (RRCT-1967)</li>
<li>Fixed a performance issue in .Net clients and Oracle Database that affected the publishing process of the modules with many tenants and multi-tenancy tables. (RPD-3440)</li>
<li>Fixed a bug that caused the execution of queries with the inline comment syntax to fail when used in the Service Studio SQL tool. (ABE-1216)</li>
</ul>
<h2 id="Platform_Server_10.0.900.0">Platform Server 10.0.900.0</h2>
<div class="info">
<p>Released on Aug 14, 2018</p>
</div>
<h3 id="New_in_Platform_Server_10.0.900.0">New in Platform Server 10.0.900.0</h3>
<ul>
<li>To achieve higher performance, you can now create stateless BAPI calls to the SAP servers. (RINT-1934)</li>
<li>Improved the ability to access deployment plans to propagate hotfixes backwards. To access these plans, in the applications list page click the drop-down menu of the target environment name. (RLIT-1863)</li>
<li>Added Integration Studio support for Visual Studio 2017. (RINT-490)</li>
<li>Updated the Oracle JDBC driver to version 12.2.0.1. If your platform database is configured as SID and your platform installation connects to it using a ServiceName, you will need to run the Configuration Tool and change the database configuration to use TNS Names <strong>before</strong> applying this upgrade. Follow the procedure described in <a href="https://success.outsystems.com/Support/Enterprise_Customers/Maintenance_and_Operations/Configuring_Oracle_database_in_the_OutSystems_platform">Configuring Oracle database in the OutSystems Platform</a>. (RSAT-988)</li>
</ul>
<h3 id="Bug_Fixing_15">Bug Fixing</h3>
<ul>
<li>Fixed an issue in the web applications that prevented Combo Box widgets inside Forms to open if they were clicked on a mobile device. (RPD-3097)</li>
<li>Fixed an issue that prevented editing properties of on-premises front-end servers in the hybrid infrastructures. For example, now it’s possible to transform an environment into a pure Deployment Controller for an on-premises server with LifeTime in the cloud. (RPD-2993)</li>
<li>Fixed an issue that allowed disabled buttons to trigger inputs with the Enter key in IE browsers. (RPD-3151)</li>
<li>Fixed an LDAP injection vulnerability. (RPD-3194)</li>
<li>Fixed an issue that caused triggering On After Fetch events in disposed Screens of the mobile apps. The logs of the affected application had ControllerDisposedException error. (RPD-3216)</li>
<li>Fixed a security issue related to cached pages. (RPD-3270)</li>
<li>Fixed an issue that prevented creating Zones in on-premises machines within a hybrid infrastructure. (RPD-3272)</li>
<li>Changes to cookie security setting are now immediately applied. (RPD-3207)</li>
<li>Fixed an issue in ECT Provider (App Feedback) that caused the feedback to be displayed like a page with broken CSS. (RPD-3381)</li>
<li>Fixed limitation in Service Center that blocked listing all the consumers and producers in the details of each eSpace. (RPD-3157)</li>
<li>Fixed an issue that caused modules with App Feedback activated to call the module when ServiceCenter cache is invalidated. The issue made applications become temporary unresponsive when publishing a solution with many eSpaces. (RPD-3228)</li>
<li>Fixed an issue in LifeTime that caused "Unknown version component: 0" error while staging a mobile application that had no manual tag assigned. (RPD-3261)</li>
<li>Fixed error when using Integration Studio to import Entities with one or more columns with user-defined data types from an external SQL Server database. (RPD-2549)</li>
<li>Fixed an issue that caused an unspecified error in LifeTime when registering an environment with a higher version than LifeTime. LifeTime now prevents adding environments to the infrastructure if the environment that is being added has higher version. (RPD-3347)</li>
<li>Fixed an issue in the Service Center search that caused the Google Chrome tab to hang. (RLIT-2058)</li>
<li>Fixed an issue that caused the Service Center global search not to work. (RLIT-2056)</li>
<li>Fixed an issue in LifeTime staging that caused the sync to fail during the execution of a deployment plan. (RLIT-1885)</li>
<li>Fixed an issue that caused generation of the Hourly Activity report in Service Center to fail. (RPD-3298)</li>
<li>Fixed a bug that was blocking changes in Environment Configurations settings in the Sentry offer. (RLIT-2045)</li>
<li>Fixed an issue that prevented users who have Change and Deploy role with “list” and “reuse” permissions to publish an application in Service Center. (RPD-3176)</li>
<li>Blocked LifeTime environment from being registered on cloud. (RPD-3027)</li>
<li>Fixed an issue that prevented registering an on-premises environment in the cloud LifeTime. Now LifeTime in the cloud is much better at discovering the environment properties. (RPD-3258)</li>
<li>Fixed an issue that caused an error when end-users tried to log in with usernames longer than 50 characters. The maximum number of characters for the username is now 250. (RPD-3234)</li>
<li>Fixed an issue that caused invalid encoding of the email attachment file names. (RPD-3275)</li>
<li>Fixed an issue that prevented the App Feedback (ECT Provider) to correctly fetch chunked resources when processing the feedback submissions. (RPD-3383)</li>
<li>Fixed an issue that occasionally caused the database constraint names to end with zeros instead of a pseudo-random number. The issue resulted in “Could not create foreign key constraint” error. (RPD-3182)</li>
<li>The selection of modules in LifeTime for option Deploy Custom now is saved correctly, avoiding reaching a plan with no module to deploy. (RLIT-2075)</li>
<li>Fixed a bug that caused a redirect to a debug server error page and not to the custom error page. This happened after an AJAX request timeout. (RRCT-1870)</li>
<li>Fixed an issue that prevented Configuration Tool to return the error code after the unattended Service Center installation failure. (RSAT-955)</li>
<li>Fixed an issue that caused SetCurrentLocale to increase the CPU load in high concurrency scenarios. (RPD-3382)</li>
<li>Fixed an issue that caused System WebScreens and WebServices API to be accessible outside the internal network.. (RPD-3356)</li>
</ul>
<h2 id="Platform_Server_10.0.828.0">Platform Server 10.0.828.0</h2>
<div class="info">
<p>Released on Jul 27, 2018</p>
</div>
<h3 id="Bug_Fixing_16">Bug Fixing</h3>
<ul>
<li>Fixed a security vulnerability. The details to be disclosed at a later date. CVSS 3.0 score of 8.7 (CVSS:3.0/AV:N/AC:H/PR:N/UI:N/S:C/C:H/I:H/A:N) (RPD-3384)</li>
<li>Fixed an issue that caused the configuration of the internal network to block the access from the IP sources that match both the trusted proxies addresses and the internal network addresses. (RPD-3391)</li>
<li>Fixed a bug that prevented saving the list of records into the database. This is a reverted fix to #ABE-705 introduced in 10.0.804.0 to prevent infinite loops in compiling screen actions that have type conversion ListAppends. This fixes the issue that caused in-memory changes and failure to properly save the list of records into the database. They only way to save them was to use changed record attributes by elements other than the ListAppend operation and the entity actions. (RSCT-1399)</li>
<li>Fixed an issue in Java Stack that broke introspection of tables and query execution when using an external MySQL database connection. (RPD-3390)</li>
</ul>
<h2 id="Platform_Server_10.0.823.0">Platform Server 10.0.823.0</h2>
<div class="info">
<p>Released on Jun 11, 2018</p>
</div>
<h3 id="New_in_Platform_Server_10.0.823.0">New in Platform Server 10.0.823.0</h3>
<ul>
<li>Improved submit feedback usability in Service Center. (RLIT-1865)</li>
<li>LifeTime Analytics retention data period can be now defined through Factory Configuration tool. (RLIT-1749)</li>
<li>Improved the process to delete old deployment data in LifeTime. (RLIT-1718)</li>
</ul>
<h3 id="Bug_Fixing_17">Bug Fixing</h3>
<ul>
<li>Fixed an issue preventing the recompilation of web screens and emails when the "Internal Access" property of the UI Flow they belong to was changed. (ABE-1002)</li>
<li>Fixed an issue that would leave the local storage database in an inconsistent state after retrying a local storage update. (RRCT-1653)</li>
<li>Fixed an issue preventing expired sessions from being deleted from the database. (RPD-3035)</li>
<li>Fixed an issue in LifeTime for cloud hybrid infrastructures that made the security settings inaccessible for all environments. (RPD-2827)</li>
<li>Fixed an issue that allowed disabled buttons to trigger inputs with the Enter key in IE browsers. (RPD-3151)</li>
<li>Fixed an issue that occurred while downloading files in Android with a MIME type larger than 50 characters. (RPD-3158)</li>
<li>Fixed an issue in HTTP-to-HTTPS redirect functionality when two Web Screens from different UI Flows share the same name. (RPD-3170)</li>
<li>Fixed LDAP injection vulnerability. (RPD-3194)</li>
<li>Fixed a SQL injection vulnerabilities in Service Center. (RPD-3196)</li>
<li>Fixed an issue in iOS 11.3 mobile apps where the virtual keyboard did not open when the end-user touched an input very fast. (RPD-3198)</li>
<li>Fixed an issue in PerformanceMonitoring API that caused consecutive successful logins to lock out the user. (RPD-3199)</li>
<li>Fixed issue in mobile apps that caused the first and last elements of virtualized lists with the data source set to an Aggregate to be rendered with a height of 0 pixels. (RPD-3300)</li>
<li>Deployment Controller service is shown as being down whenever stored procedure 'DeleteExpiredSessionVarsReturningDeletedRows' does not exist. (RPD-3304)</li>
<li>Fixed an error when running a mobile app after deleting all its local database entities. (RSCT-1218)</li>
<li>Fixed an issue in iOS mobile apps that was causing one click to trigger two click events. (RPD-3204)</li>
<li>Fixed bug that in some cases would cause infinite loops while compiling screen actions with List Appends having type conversions. (ABE-1003)</li>
<li>Changing the description of REST API method parameters will now update the exposed REST API documentation. (RINT-1563)</li>
<li>Fixed a performance issue in LifeTime that occurred while validating Deployment Plans. (RLIT-1888)</li>
<li>Fixed a bug that caused Service Center not to show all Consumed SOAP and REST Web Services for eSpaces with more than 100 entries. (RPD-3201)</li>
<li>The maintenance window of the Lifetime environment in a cloud infrastructure now only changes when defining the maintenance window for the leftmost environment displayed in Lifetime's Infrastructure screen. (RLIT-1876)</li>
<li>Changes to cookie security setting are now immediately applied. (RPD-3207)</li>
<li>Fixed a performance issue in Service Center that occurred while accessing the Process Monitoring page. (RLIT-1837)</li>
<li>Fixed an intermittent issue in Service Center that caused a timeout when accessing logs in the Monitoring tab. (RLIT-1813)</li>
<li>Fixed an issue that caused Service Center to incorrectly show a success message when changing a Timer Schedule. (RLIT-1611)</li>
<li>Fixed an issue in Service Center that prevented the automatic cleanup of old Solutions. (RPD-2592)</li>
<li>Fixed mobile apps becoming unresponsive after resuming from background in iOS 11.3. (RPD-3203)</li>
<li>Fixed several UI issues in LifeTime. (RLIT-1820)</li>
<li>Removed redundant EnableViewStateMac attribute from web screens. (RPD-3197)</li>
<li>Improvements in session cleanup mechanism. NOTE: It's strongly recommended to re-create the session database using the Configuration Tool. (RPD-3059)</li>
<li>Fixed RichWidgets InputAutoComplete/ListNavigation/ListOrderBy not working if the page was first accessed using an URL that contained a different casing from the original page name. (RPD-3231)</li>
<li>The platform server installation checklist now includes instructions to install the WebLogic patch that fixes RPC Web Service calls swapping the parameters order. (RPD-3083)</li>
</ul>
<h2 id="Platform_Server_10.0.816.0">Platform Server 10.0.816.0</h2>
<div class="info">
<p>Released on Apr 30, 2018</p>
</div>
<h3 id="Bug_Fixing_18">Bug Fixing</h3>
<ul>
<li>Fixed an error in Web Applications that was preventing the feedback message to be displayed when using the RichWidgets Feedback_Message action in a pop-up together with the RichWidgets Popup_Editor_Close action. (RPD-3206)</li>
</ul>
<h2 id="Platform_Server_10.0.811.0">Platform Server 10.0.811.0</h2>
<div class="info">
<p>Released on Apr 12, 2018</p>
</div>
<h3 id="New_in_Platform_Server_10.0.811.0">New in Platform Server 10.0.811.0</h3>
<ul>
<li>Improved User_Login description. (RLIT-1786)</li>
</ul>
<h3 id="Bug_Fixing_19">Bug Fixing</h3>
<ul>
<li>Fixed an issue with the persistence of permissions while re-registering an Environment in LifeTime. (RPD-3024)</li>
<li>Fixed a security granting permissions issue in LifeTime. (RPD-2652)</li>
<li>Fixed an issue in LifeTime that caused the staging of an Application to abort when a tag was created in Deploy Custom. (RLIT-1639)</li>
<li>Fixed problem saving deployment notes when plan needs to be revalidated. (RPD-3014)</li>
<li>Fixed an issue in LifeTime that caused slowness in the Staging Summary of a deployment with several Applications. (RLIT-1686)</li>
<li>Updated Install Checklist to reflect support for 8 KB Tablespaces in patched Oracle 12c R2 instances. (RSAT-781)</li>
<li>Fixed version tagging when deploying a hotfix on LifeTime. (RPD-2998)</li>
<li>Fixed an issue in LifeTime that was causing a loop in the staging plan validation when there were modules moved between applications or new modules in the target environment. (RPD-3041)</li>
<li>Fixed an issue on the status method in LifeTime Deployment API that returned "running" status when the deployment plan finished with errors. (RLIT-1830)</li>
<li>Increased the maximum length of configuration fields for Content Security Policy in LifeTime. (RPD-3047)</li>
<li>Fixed an issue on the execute command method in LifeTime Deployment API that prevented the deployment plan from continuing when there were database configurations missing. (RLIT-1733)</li>
<li>Fixed an issue that caused some Service Center features to not be available after upgrading LifeTime. (RLIT-1732)</li>
<li>Fixed problem calculating size of list virtualization buffers in mobile apps. (RPD-2920)</li>
<li>Fixed an issue that caused incorrect rendering of virtualized lists with horizontal stacked elements in Mobile Apps. (RPD-3003)</li>
<li>Fixed a bug in LifeTime that caused recently moved Modules that do not exist in the target Zone to be suggested for redeployment. (RLIT-1735)</li>
<li>Fixed a bug that caused navigation links to stop working on concurrent screen redirects. (RPD-2837)</li>
<li>Fixed an issue that caused “Request is not available in this context” errors during Application start when using IIS in Integrated Mode. (RRCT-1571)</li>
<li>Fixed compilation error that occurred when using a Client Entity to generate a Process Event. (ABE-763)</li>
<li>Fixed issue that caused "thread was being aborted" errors during server-side redirects. (RQR-222)</li>
<li>Fixed an issue that caused a Windows "Application Encountered an Error" dialog when closing the Configuration Tool. (RSAT-783)</li>
<li>Fixed Application Server unresponsiveness when it was not possible to establish a connection to an external database. (RPD-2791)</li>
<li>Fixed default Users "admin" being recreated after the first install. (RPD-3076)</li>
<li>Solution publish no longer prompts the operator for unnecessary DB connection configurations during LifeTime deployments. (RPD-3015)</li>
<li>Fixed a query error that appeared when using Oracle attribute references with different casing inside Expand Inline Attribute values. (RPD-2961)</li>
<li>Fixed connection leak that lead to Service Center unavailability. (RPD-3056)</li>
<li>Fixed security vulnerability. Details <a href="https://success.outsystems.com/Support/Security/Vulnerabilities/Vulnerability_RPD-2903" title="/Support/Enterprise_Customers/Troubleshooting/2018-07-04_-_Security_Issue_-_Dormouse">here</a>. (RPD-2903)</li>
</ul>
<h3 id="Known_Issue">Known Issue</h3>
<ul>
<li>In Web Applications, when using the RichWidgets Feedback_Message action in a pop-up together with the RichWidgets Popup_Editor_Close action, the feedback message is not displayed. </li>
</ul>
<h2 id="Platform_Server_10.0.808.0">Platform Server 10.0.808.0</h2>
<div class="info">
<p>Released on Mar 21, 2018</p>
</div>
<h3 id="Bug_Fixing_20">Bug Fixing</h3>
<ul>
<li>Fixed a concurrent publishing error that could happen after a failed 1-Click Publish, which prevented the future publishing of the module. (RSCT-1198)</li>
</ul>
<h2 id="Platform_Server_10.0.804.0">Platform Server 10.0.804.0</h2>
<div class="info">
<p>Released on Feb 26, 2018.</p>
</div>
<h3 id="New_in_Platform_Server_10.0.804.0">New in Platform Server 10.0.804.0</h3>
<ul>
<li>New LifeTime experience to improve the performance of browsing through applications and preparing deployments. <br/>
The performance of LifeTime Analytics was significantly improved. Check out to <a href="https://success.outsystems.com/Support/Enterprise_Customers/Upgrading/Updating_LifeTime_Analytics_to_10.0.804.0" title="https://success.outsystems.com/Support/Enterprise_Customers/Upgrading/Updating_LifeTime_Analytics_to_10.0.804.0">here</a> how to update your LifeTime to take advantage of these improvements. (RLIT-766)</li>
<li>Business Process Technology (BPT) now supports light process execution. (ABE-612)</li>
<li>NullDates stored in local storage can no longer become non-null due to timezone conversions for new Platform Server installations. (RAFT-1026)</li>
<li>Changed the database exception messages generated by queries to prevent database information to be shown to end users. The full exception messages can still be found in error logs. (RRCT-772)</li>
<li>Improved security of the image endpoints. (RRCT-1175)</li>
<li>Improved the load time of the License Usage screen in Service Center. (RPD-2537)</li>
<li>It is now possible to set "Auto Commit" property in DB2 Advanced Configuration. (RPD-2911)</li>
<li>The native error messages and general messages on Service Center will now have more information about the device, such as: Device Information, DeviceModel, OperatingSystem, Cordova version, DeviceUUID, NetworkType, NativeShell version and NetworkStatus. (RNMT-1283)</li>
<li>Improved the encryption logic on upgrade scenarios. (RLIT-1330)</li>
<li>Added more information about Public area inconsistencies when publishing to a PTA. (RSCT-733)</li>
<li>The applications in LifeTime Deployment are now sorted by the name, and not by the IDs. (RLIT-1379)</li>
<li>Improved the inconsistency message in LifeTime when validating a deployment. (RLIT-1500)</li>
<li>It is now possible to view database usage details in LifeTime in the Cloud. (RLIT-1560)</li>
<li>Updated community supported translation of the System Components. (RLIT-1602)</li>
<li>It is now possible to specify a domain name for a mobile app in Service Center. (RLIT-1486)</li>
<li>Improved security to avoid the injection of HTML or JavaScript in the URL in App Feedback. (RPD-2517)</li>
<li>LIfeTime received updated localization for Japanese. (RLIT-1470)</li>
<li>Improved LifeTime validation performance of the deployment plans. (RLIT-1406)</li>
<li>Updated the Chinese and French translation for the RichWidgets Calendar. (RSUT-732)</li>
</ul>
<h3 id="Bug_Fixing_21">Bug Fixing</h3>
<ul>
<li>Fixed a bug that prevented ListFilter, ListAny, ListAll, ListIndexOf and ListSort from returning the results because some attributes from the source list were ignored. (ABE-674)</li>
<li>Fixed a bug that caused a module contained within several solutions to open slowly in Service Center. (RPD-2893)</li>
<li>Fixed exposed REST documentation examples to comply with Swagger 2.0. (RPD-2895)</li>
<li>Fixed the deployment error “Could not find a part of the path” that appeared when publishing a solution using OSP Tool. (RPD-2924)</li>
<li>Fixed a bug that caused issues in redirection from HTTP to HTTPS when using SEO Rule links. (RPD-2847)</li>
<li>Fixed a bug that caused an error in the long integer conversion when using XMLtoRecordList from the XML system extension. (RPD-2625)</li>
<li>Fixed a concurrency issue that appeared when creating tenant views in MySQL. (RPD-2820)</li>
<li>Fixed a bug that caused date conversions in local storage upgrade process. (RPD-2834)</li>
<li>Fixed a bug that prevented manual unblock of external user accounts after invalid login attempts. (RPD-2148)</li>
<li>Fixed a bug that caused the compiler to crash in rare circumstances due to internal thread concurrency. (RPD-2387)</li>
<li>Fixed possible deadlock scenario when uploading eSpaces in Service Center. (RPD-2507)</li>
<li>Fixed a bug that caused MySQL Generic SQL Error during upgrade when the multi-tenancy of the module was changed. (RPD-2648)</li>
<li>Fixed a bug that prevented editing data in the datepicker when using Chrome or Firefox on a desktop touch screen device. (RPD-2781)</li>
<li>Fixed a bug where an application with multiple modules could not be deleted (due to a deadlock) when having a SEO eSpace alias rule defined in the factory. (RPD-2990)</li>
<li>Fixed a bug that caused runtime errors on mobile applications when using a variable of LongInteger type that had a default value defined. (RRCT-1476)</li>
<li>Fixed a bug on the client-side mobile application debugger where a "Cannot read property 'toString' of null" error would show up when having a function as an Aggregate Filter. (RPD-2901)</li>
<li>Fixed an issue in mobile apps that caused error logs not to be sent to the server from the default error screen. (RRCT-1305)</li>
<li>LogRecord system action now works with values other than Records and no longer throws a runtime error. (RRCT-1255)</li>
<li>Fixed a bug that prevented the update of multi-tenant site properties values when they were changed inside a module that has a different user provider from the module defining the properties. (RRCT-1084)</li>
<li>Fixed a bug that prevented modules created in the beta version from being published. (RPD-2825)</li>
<li>Fixed a bug where a mobile application with " ' " in the name would cause runtime errors due to invalid JavaScript code. (RRCT-1071)</li>
<li>Fixed a bug that caused re-creation of the client entity tables when the AutoNumbered attribute was changed. (RRCT-959)</li>
<li>Fixed a bug in the Configuration Tool that caused a crash when exporting a configuration pointing to a database that is not accessible. (RSAT-606)</li>
<li>Fixed an issue that was deleting static entities in the compilation stage of a two-stage deployment. (RPD-2879)</li>
<li>Fixed an issue regarding the creation of static entity information in a newly created tenant between the compilation and deployment stage. (RPD-2873)</li>
<li>Fixed a bug that caused the following error: “You don’t have enough permissions over the database connections...". The bug also prevented publishing an extension in Integration Studio in cases where that extension had External Entities whose Physical Table name already existed in a non-accessible External Database Connection. (RSCT-898)</li>
<li>Fixed date of log when HarvestAndGroupData timer from LifeTime Analytics runs. (RLIT-1378)</li>
<li>Fixed a redirection bug in LifeTime that occurred in a completed deployment. (RLIT-1462)</li>
<li>Fixed a bug that prevented sending LifeTime Analytics mails for all environments except the first. (RPD-2725)</li>
<li>Fixed a bug that caused “ran out of internal resources” error message while cleaning the old login attempts in Service Center. (RPD-2970)</li>
<li>Fixed an issue related to missing application icons after a staging in LifeTime. (RLIT-1594)</li>
<li>Fixed a security issue granting permissions in LifeTime. (RPD-2652)</li>
<li>Fixed a bug that caused a feedback message not to appear after adding a new On-Premises Environment in a LifeTime hosted in the Cloud. (RPD-2854)</li>
<li>Fixed UI glitch in LifeTime users list. (RLIT-1399)</li>
<li>Fixed a long URLs bug that prevented feedback submission in App Feedback. (RPD-2576)</li>
<li>Fixed a bug that prevented the invalidation of the cache when setting the hostname in Service Center. (RLIT-1584)</li>
<li>Fixed a bug in the Deploy Custom popup that removed the last changed date of a module. (RLIT-1426)</li>
<li>Fixed the unregistration of on-premises Java environments from cloud infrastructures (RPD-2832)</li>
<li>Fixed a bug that caused “ran out of internal resources” error message while cleaning the old login attempts in Users application. (RPD-2745)</li>
<li>Fixed a bug that caused Service Center to stop responding while generating the Analytics Report. (RLIT-1498)</li>
<li>Removed Japanese characters showing incorrectly in LifeTime. (RLIT-1224)</li>
<li>Fixed a bug that prevented the rendering of a confirmation message during a deployment in LifeTime. (RPD-2500)</li>
<li>Fixed overlapping information on staging summary. (RLIT-1222)</li>
<li>Fixed a bug that caused unneeded refresh of the List widget on the first load. (RAFT-873)</li>
<li>Fixed misplaced warning icon when an environment is OK in LifeTime. (RLIT-1408)</li>
<li>Fixed UI glitch on LifeTime Analytics when using firefox (RLIT-1388)</li>
<li>Fixed javascript error while editing an environment configuration in LifeTime Analytics (RLIT-1387)</li>
<li>Fixed the order by of applications dropdown in LifeTime Analytics (RLIT-1383)</li>
<li>Fixed issue opening LTCC when one environment has connectivity issues. (RPD-2358)</li>
<li>Fixed an error that prevented importing users after re-registering an environment in LifeTime. (RPD-2826)</li>
<li>Increased the throughput of mobile request logs. This issue affected mostly Personal environments (RRCT-1254)</li>
<li>Fixed issue in which in-memory changes to a list of records wouldn't be properly saved into the database unless the changed record attributes were being used by elements other than the ListAppend operation and the entity actions. (ABE-705)</li>
<li>Fixed intermittent connectivity issues to Oracle 12c R2 databases by updating Oracle .NET Managed Driver to version 4.121.2.20170316. (RPD-2727)</li>
<li>Fixed referencing an inline function in an Ajax Refresh. (RPD-1807)</li>
<li>Fixed Deploy Service hang when validating the deployment of an application. (RPD-2641)</li>
<li>Fixed script syntax error in exported session script in Configuration tool (RPD-2509)</li>
<li>Improved performance of Scheduler while obtaining timers to executed. (RPD-2988)</li>
<li>Updated iDB2 driver (RPD-2967)</li>
<li>Fixed syntax error in SQL Server Runtime Script exported by Configuration Tool. (RSAT-714)</li>
<li>Fixed incorrect exception being thrown when the exception originates from a List Records widget. (RPD-2777)</li>
<li>Fixed an issue preventing mobile applications from uploading images stored in the device with metainformation problems. (RPD-2964)</li>
<li>Fixed binding error when importing WS with enumerations containing values with square brackets. (RPD-2836)</li>
<li>Fixed Malformed Class Name error when using the SetWebReferenceProxy (RPD-2974)</li>
<li>Added an "Add null checks to imported items" option to the import .Net assembly wizard. (RPD-2606)</li>
</ul>
<h2 id="Platform_Server_10.0.723.0">Platform Server 10.0.723.0</h2>
<div class="info">
<p>Released on Feb 22, 2018.</p>
</div>
<h3 id="New_in_Platform_Server_10.0.723.0">New in Platform Server 10.0.723.0</h3>
<ul>
<li>Changed the database exception messages generated by queries to prevent database information to be shown to end users. The full exception messages can still be found in error logs. (RRCT-772)</li>
</ul>
<h3 id="Bug_Fixing_22">Bug Fixing</h3>
<ul>
<li>Fixed a bug that prevented ListFilter, ListAny, ListAll, ListIndexOf and ListSort from returning the results because some attributes from the source list were ignored. (ABE-674)</li>
<li>Fixed an issue related to missing application icons after a staging in LifeTime. (RLIT-1594)</li>
<li>Fixed a bug that prevented the rendering of a confirmation message during a deployment in LifeTime. (RPD-2500)</li>
<li>Fixed an overflow crash in LifeTime Analytics when trying to display large data. (RPD-523)</li>
<li>Fixed a concurrency issue that appeared when creating tenant views in MySQL. (RPD-2820)</li>
<li>Fixed a bug that caused date conversions in local storage upgrade process. (RPD-2834)</li>
<li>Fixed an issue regarding the creation of static entity information in a newly created tenant between the compilation and deployment stage. (RPD-2873)</li>
<li>Fixed a bug that caused a module contained within several solutions to open slowly in Service Center. (RPD-2893)</li>
<li>Fixed exposed REST documentation examples to comply with Swagger 2.0. (RPD-2895)</li>
<li>Fixed a bug on the client-side mobile application debugger where a "Cannot read property 'toString' of null" error would show up when having a function as an Aggregate Filter. (RPD-2901)</li>
<li>Fixed a bug that caused the following error: “You don’t have enough permissions over the database connections...". The bug also prevented publishing an extension in Integration Studio in cases where that extension had External Entities whose Physical Table name already existed in a non-accessible External Database Connection. (RSCT-898)</li>
</ul>
<h2 id="Platform_Server_10.0.710.0">Platform Server 10.0.710.0</h2>
<div class="info">
<p>Released on Nov 20, 2017</p>
</div>
<h3 id="Bug_Fixing_23">Bug Fixing</h3>
<ul>
<li>Fixed duplicate feedback messages being displayed in pages containing iframes that call Feedback_Message action. (RPD-2764)</li>
<li>Service Center now hides modules that don't need catalog configuration during a solution publish. (RPD-2341)</li>
<li>Fixed an issue that prevented changing the length of a Text entity attribute from 2000 to a larger value. (RPD-2224)</li>
<li>Fixed an internal error occurring while registering a new environment in LifeTime. (RLIT-1402)</li>
<li>Fixed an issue that prevented LifeTime Analytics from showing information for scenarios with a huge amount of data to process. (RLIT-1380)</li>
<li>Fixed scroll on horizontal lists. (RAFT-940)</li>
<li>Fixed an issue that was causing the resources of a web responsive application (such as CSS, images or JavaScript) to remain outdated after deploying the application from one environment to another. (RSCT-882)</li>
<li>Fixed tab indexes having the wrong order in an Ajax Refresh. (RPD-2809)</li>
<li>Fixed Ajax Refresh overriding "tabindex" attribute defined in Extended Properties. (RPD-2753)</li>
<li>Fixed runtime error when opening pages having widgets using properties of other widgets in Extended Properties. (RPD-2650)</li>
</ul>
<h2 id="Platform_Server_10.0.710.1">Platform Server 10.0.710.1</h2>
<p>OutSystems mobile application logs have been enhanced with additional info to help in evaluating the impact a particular issue is having on their user base.</p>
<p>The logs now have a unique identifier that identifies an installation of the application in a device. This identifier is aligned with Apple Store and Play Store best practices. It is generated in the following manner:</p>
<meta charset="utf-8"/>
<ul>
<li dir="ltr">
<p dir="ltr">Android: Generated on the device's first boot. If the device is reset, a new identifier is generated.</p>
</li>
<li dir="ltr">
<p dir="ltr"><span class="os-concept">iOS: Generated from multiple hardware identifiers, guaranteed to be unique per installation of the application in a device and cannot be tied to the user account. Deleting the application and reinstalling it will generate a new identifier.</span></p>
</li>
</ul>
<p dir="ltr">This info has been added as the "DeviceUUID" to any general or error log created client side, and general, error and mobile request log created server side during the execution of a request from a mobile application. With this info it is now easier to identify the errors happening on a device, or how many devices are having a specific error.</p>
<p dir="ltr"> </p>
<p dir="ltr"><strong>On Service Center, this info can be found on</strong>:</p>
<ul>
<li>Error Log: The detail of the log, in the "Environment Information" section, preceded by the "DeviceUUID" tag.</li>
<li>General Log: not displayed</li>
<li>Mobile Request Log: The "Source" column.</li>
</ul>
<p dir="ltr"> </p>
<p dir="ltr"><strong>On the database, this info can be found on</strong>:</p>
<ul>
<li>Error Log: OSLOG_ERROR views and tables, on the "EnvironmentInformation" column, preceeded by the "DeviceUUID" tag.</li>
<li>General Log: OSLOG_GENERAL views and tables, on the "Client_IP" column, preceeded by the "DeviceUUID" tag.</li>
<li>Mobile Request Log: OSLOG_MOBILE_REQUEST views and tables, on the "Source" column, preceded by the "DeviceUUID" tag.</li>
</ul>
<p dir="ltr">It is now also easier to identify if a user had an unhandled error during the usage of the application. Every time a user is presented with the default error screen, an error log is automatically generated to register this event. That log entry can be easily identified since it has "ErrorScreen" as module and its message also starts with "[ErrorScreen]".</p>
<h2 id="Platform_Server_10.0.708.0">Platform Server 10.0.708.0</h2>
<div class="info">
<p>Released on Oct 16, 2017</p>
</div>
<h3 id="Bug_Fixing_24">Bug Fixing</h3>
<ul>
<li>Fixed an issue when deploying multi-tenant modules for scenarios having a large number of tenants and entities with a large number of attributes. (RPD-2496)</li>
<li>Is now possible to edit the Developer Role in LifeTime. (RPD-2605)</li>
<li>Fixed an issue when deploying applications with broken references through Lifetime. (RPD-2715)</li>
<li>Fixed an internal error while validating a deployment plan in LifeTime. (RLIT-1331)</li>
<li>Fixed an error related to users synchronization in the LifeTime process for cleaning up old metadata. (RLIT-1306)</li>
<li>Fixed security issue while editing protected users in LifeTime. (RPD-2581)</li>
<li>The error message displayed in LifeTime while validating a staging plan now includes all the inconsistencies. (RLIT-1285)</li>
<li>Fixed a security vulnerability in LifeTime. (RPD-2580)</li>
<li>Fixed an issue in LifeTime that was causing a loop in the staging plan validation when there was a change in the source environment. (RLIT-559)</li>
<li>Fixed an issue when adding a meta tag to an email screen. (RPD-2506)</li>
<li>[.NET Only] Cleaned up unnecessary page meta tags from auto generated pages. (RPD-2651)</li>
<li>[.NET Only] Fixed an issue that was causing SEO site rules to override IIS rules. (RPD-2600)</li>
<li>[.NET Only] Fixed an error while creating sessions in Oracle stack. (RPD-2546)</li>
</ul>
<h2 id="Platform_Server_10.0.705.0">Platform Server 10.0.705.0</h2>
<div class="info">
<p>Released on Sep 19, 2017</p>
</div>
<h3 id="New_in_Platform_Server_10.0.705.0">New in Platform Server 10.0.705.0</h3>
<ul>
<li>The debugging of client-side actions is now available. It requires the Development Environment version 10.0.704.0 or higher. (RAFT-162)</li>
<li>Improved security to avoid the injection of HTML or JavaScript in the URL while running the mobile app in PreviewInDevices. (RPD-1957)</li>
<li>Improved DBCleaner_API documentation and Service Center messages to reflect restrictions on deleting old eSpace versions. (RPD-2000)</li>
<li>Extended properties 'virtualization-threshold-before' and 'virtualization-threshold-after' can now be used to configure the virtualization of lists and this way improve the scroll experience in mobile apps. (RAFT-831)</li>
<li>Improved the rendering of images of Binary Data type to be faster. The scroll in lists with images is also smoother. (RAFT-822)</li>
<li>Reduced the number of loaded application resources to improve the rendering and upgrade time of mobile apps. (RAFT-796)</li>
<li>The scroll experience through lists is now faster and more stable, due to list virtualization performance and stability improvements. (RAFT-673)</li>
<li>Added new Japanese translations to LifeTime. (RLIT-1157)</li>
<li>Updated Japanese translations in LifeTime. (RLIT-915)</li>
<li>In LifeTime, applications in the staging summary are now sorted alphabetically. (RLIT-562)</li>
<li>Logs of the mobile app generation can now be downloaded in Service Center, in the Native Platform tab of the application page. (RNMT-424)</li>
<li>Error screens in mobile applications can now be customized via Extensibility Configurations of the module. (RRCT-903)</li>
<li>Reduced the amount of data transferred from the server when detecting if a new application version is available. (RRCT-705)</li>
<li>Improved the load time of mobile application screens for first-time visits. (RRCT-745)</li>
<li>[.NET Only] Improved the logging of consumed SOAP Web Services to allow configuring the level of detail. (RINT-694)</li>
</ul>
<h3 id="Bug_Fixing_25">Bug Fixing</h3>
<ul>
<li>Fixed an issue in the Deployment Controller that was causing the publishing operation to hang in some platform upgrade scenarios. (RPD-2442)</li>
<li>Fixed the Configuration Tool query timeouts when upgrading the database. (RPD-2351)</li>
<li>Fixed the optimization of type mappings that was ignoring the indexes of lists and function arguments. (RPD-2362)</li>
<li>Fixed the launch of BPT processes for newly created records in heavy loaded databases. (RPD-2147)</li>
<li>Fixed an issue in the environment synchronization and staging operations in LifeTime that was causing the environment to keep synchronizing. (RPD-2452)</li>
<li>Fixed an issue in Multiple Database Catalogs (MDC) scenarios that caused the database updates to fail. (RPD-2377)</li>
<li>Fixed runtime errors when accessing attributes of an output parameter of an action and the output parameter is defined by a structure that was modified. This occurs in environments in Development Mode, not in Production Mode. (RSCT-688)</li>
<li>Fixed an issue with renamed modules where the old version remained deployed. (RPD-2205)</li>
<li>Fixed a runtime error with Static Entity translations when the Static Entity has a single attribute. (RPD-2112)</li>
<li>Fixed an issue in mobile apps navigation that was causing the app to crash when the user clicked too many times on Go Back links. (RAFT-800)</li>
<li>Now you can enter values like 0.01 or 0.0001 in Input Widget. It was difficult to enter 0.0 because of an issue that made that value be replaced with a zero in the widget upon an internal comparison. (RAFT-580)</li>
<li>Fixed an error in the basic authentication of exposed REST APIs when the password contained a colon (':'). (RINT-651)</li>
<li>Fixed an issue that didn’t allow users to discard the plan they had created. (RLIT-1108)</li>
<li>Fixed an issue that prevented a mobile app from doing a rollback of a failed upgrade that had started when the user opened the app for the first time. (RRCT-697)</li>
<li>Fixed an issue that would cause a mobile app to keep reloading when the rollback of an app upgrade failed. (RRCT-700)</li>
<li>Fixed the order by which versions were sorted when getting the versions of an application through the LifeTime Deployment API. (RLIT-1101)</li>
<li>Fixed returned status code (401 Unauthorized) when the authentication fails in calls to methods of the LifeTime Deployment API. (RLIT-472)</li>
<li>Fixed an error when running the application in the Personal Area. (RPD-2502)</li>
<li>Fixed mobile charts to trigger the event when they are rendered. (RSUT-337)</li>
<li>Fixed mobile charts to be drawn when multiple points have the same label. (RPD-1280)</li>
<li>Fixed mobile charts to display the label of data points that are added. (RPD-1351)</li>
<li>Fixed an error occurring when the login was performed from a device having the User-Agent request header string larger than 200 characters. (RPD-2175)</li>
<li>Configuration Tool no longer logs query errors when checking if tables and columns already exist in the database. (RPD-2238)</li>
<li>Fixed an issue in the LifeTime SDK that was causing the export of sample data to take a long time. (RPD-2401)</li>
<li>Fixed an issue in the LifeTime SDK when importing sample data and the module version was not filled. (RPD-2411)</li>
<li>Fixed a license validation error while publishing a Solution that made the applications temporarily unavailable. (RPD-2420)</li>
<li>Fixed an issue that prevented a mobile app user from leaving the splash screen after the rollback of an app upgrade. (RRCT-758)</li>
<li>Fixed an issue that caused back button to stop working on iOS. (RRCT-866)</li>
<li>Fixed mobile charts to allow more than 1000 data points. (RSUT-12)</li>
<li>Fixed an issue that was skipping the input's OnChange function when the Enter key was pressed just after changing the input. (RPD-2450)</li>
<li>Fixed compiler service error when performing automatic dependencies refresh. (RPD-2515)</li>
<li>Fixed the detection of concurrent publications of the same module. (RPD-2566)</li>
<li>Removed the error message that was shown in case of a successful deployment through the LifeTime Deployment API. (RLIT-1131)</li>
<li>[.NET Only] Fixed runtime error with lists manipulated in extensions using the .NET GetFields() method and those lists are stored in session variables. (RPD-2525)</li>
<li>[.NET Only] Fixed slowness and timeouts when publishing the application in MySQL. (RPD-2474)</li>
<li>[.NET Only] Fixed a compilation error when consuming a SOAP Web Service with elements including a hyphen ('-') in the name. (RPD-2389)</li>
<li>[.NET Only] Fixed an access error when introspecting iDB2 tables in Integration Studio by removing a dependency to QADBFDEP table. (RPD-2514)</li>
<li>[Java Only] Changed the returned status code from 204 No Content to 200 Success in the LifeTime Deployment API when no content is returned. (RLIT-904)</li>
<li>[Java Only] Fixed a compilation error when consuming a SOAP Web Service with nested complex types. (RPD-2449)</li>
</ul>
<h2 id="Platform_Server_10.0.702.0">Platform Server 10.0.702.0</h2>
<div class="info">
<p>This version is exclusive to Personal Environments and includes the same features and fixes as Platform Server 10.0.705.0.</p>
<p>Check the <a href="https://success.outsystems.com/Support/Release_Notes/10/Platform_Server/221_Platform_Server_10.0.705.0" title="Platform Server 10.0.705.0">Release Notes of Platform Server 10.0.705.0</a> for details.</p>
</div>
<h2 id="Platform_Server_10.0.617.0">Platform Server 10.0.617.0</h2>
<div class="info">
<p>Released on Nov 20, 2017</p>
</div>
<h3 id="Bug_Fixing_26">Bug Fixing</h3>
<ul>
<li>Fixed duplicate feedback messages being displayed in pages containing iframes that call Feedback_Message action. (RPD-2764)</li>
<li>Service Center now hides modules that don't need catalog configuration during a solution publish. (RPD-2341)</li>
<li>Fixed an issue that prevented changing the length of a Text entity attribute from 2000 to a larger value. (RPD-2224)</li>
<li>Fixed an issue that prevented LifeTime Analytics from showing information for scenarios with a huge amount of data to process. (RLIT-1380)</li>
<li>Fixed an issue that was causing the resources of a web responsive application (such as CSS, images or JavaScript) to remain outdated after deploying the application from one environment to another. (RSCT-882)</li>
<li>Fixed tab indexes having the wrong order in an Ajax Refresh. (RPD-2809)</li>
<li>Fixed Ajax Refresh overriding "tabindex" attribute defined in Extended Properties. (RPD-2753)</li>
<li>Fixed runtime error when opening pages having widgets using properties of other widgets in Extended Properties. (RPD-2650)</li>
</ul>
<h2 id="Platform_Server_10.0.616.0">Platform Server 10.0.616.0</h2>
<div class="info">
<p>Released on Oct 16, 2017</p>
</div>
<ul>
</ul>
<h3 id="Bug_Fixing_27">Bug Fixing</h3>
<ul>
<li>Fixed an issue when deploying multi-tenant modules for scenarios having a large number of tenants and entities with a large number of attributes. (RPD-2496)</li>
<li>Is now possible to edit the Developer Role in LifeTime. (RPD-2605)</li>
<li>Fixed an issue when deploying applications with broken references through Lifetime. (RPD-2715)</li>
<li>Fixed an internal error while validating a deployment plan in LifeTime. (RLIT-1331)</li>
<li>Fixed an error related to users synchronization in the LifeTime process for cleaning up old metadata. (RLIT-1306)</li>
<li>Fixed security issue while editing protected users in LifeTime. (RPD-2581)</li>
<li>Fixed a security vulnerability in LifeTime. (RPD-2580)</li>
<li>Fixed an issue when adding a meta tag to an email screen. (RPD-2506)</li>
<li>[.NET Only] Cleaned up unnecessary page meta tags from auto generated pages. (RPD-2651)</li>
<li>[.NET Only] Fixed an issue that was causing SEO site rules to override IIS rules. (RPD-2600)</li>
<li>[.NET Only] Fixed an error while creating sessions in Oracle stack. (RPD-2546)</li>
</ul>
<h2 id="Platform_Server_10.0.614.0">Platform Server 10.0.614.0</h2>
<div class="info">
<p>Released on Sep 19, 2017</p>
</div>
<h3 id="New_in_Platform_Server_10.0.614.0">New in Platform Server 10.0.614.0</h3>
<ul>
<li>Added new Japanese translations to LifeTime. (RLIT-1157)</li>
</ul>
<h3 id="Bug_Fixing_28">Bug Fixing</h3>
<ul>
<li>Fixed an error when running the application in the Personal Area. (RPD-2502)</li>
<li>Fixed an issue in the environment synchronization and staging operations in LifeTime that was causing the environment to keep synchronizing. (RPD-2452)</li>
<li>Fixed an issue that was skipping the input's OnChange function when the Enter key was pressed just after changing the input. (RPD-2450)</li>
<li>Fixed an issue in the Deployment Controller that was causing the publishing operation to hang in some platform upgrade scenarios. (RPD-2442)</li>
<li>Fixed an error occurring when the login was performed from a device having the User-Agent request header string larger than 200 characters. (RPD-2175)</li>
<li>Fixed an XSS vulnerability in the iframe to preview mobile devices screens. (RPD-1957)</li>
<li>Fixed an issue in mobile apps navigation that was causing the app to crash when the user clicked too many times on Go Back links. (RAFT-800)</li>
<li>[.NET Only] Fixed an access error when introspecting iDB2 tables in Integration Studio by removing a dependency to QADBFDEP table. (RPD-2514)</li>
<li>[.NET Only] Fixed slowness and timeouts when publishing the application in MySQL. (RPD-2474)</li>
<li>[.NET Only] Fixed a runtime error when calling a SAP BAPI having a decimal value which length exceeds the decimal length of the BCD SAP data type. (RPD-2409)</li>
<li>[.NET Only] Fixed a compilation error when consuming a SOAP Web Service with elements including a hyphen ('-') in the name. (RPD-2389)</li>
<li>[Java Only] Fixed a compilation error when consuming a SOAP Web Service with nested complex types. (RPD-2449)</li>
</ul>
<h2 id="Platform_Server_10.0.604.0">Platform Server 10.0.604.0</h2>
<div class="info">
<p>Released on Jul 25, 2017</p>
</div>
<h3 id="New_in_Platform_Server_10.0.604.0">New in Platform Server 10.0.604.0</h3>
<ul>
<li>Added the possibility to define the locale convention when configuring connections to external Oracle databases in Service Center. (RINT-387)</li>
<li>[.NET Only] Added support for Azure SQL using database authentication (Windows authentication not supported). (RSAT-337)</li>
</ul>
<h3 id="Bug_Fixing_29">Bug Fixing</h3>
<ul>
<li>Fixed an issue that prevented the cleanup of some expired sessions. (RRCT-718)</li>
<li>Fixed incorrect behavior while parsing dates in some Android devices (inputs and built-in functions). (RPD-2395)</li>
<li>Fixed possible lock escalation when waking up timers during the publication of modules. (RPD-2346)</li>
<li>Fixed an issue that would cause the Unattended Installation and Upgrade command line tools to return success exit codes even when errors did occur. (RPD-2313)</li>
<li>Fixed an error that prevented changing an entity attribute if the corresponding MySQL column set or cleared a DEFAULT constraint. (RPD-2274)</li>
<li>Fixed a syncing problem involving multiple front-ends that were not connected to the same database as the controller. (RPD-2225)</li>
<li>Fixed an issue that prevented changing the length of a Text entity attribute from 2000 to a larger value. (RPD-2224)</li>
<li>Fixed a compilation error when consuming Structures without Attributes. (RPD-2065)</li>
<li>[.NET Only] Fixed RichWidgets InputAutoComplete/ListNavigation/ListOrderBy not working if the page was accessed using an URL that contained a different casing from the original page name. (RPD-2379)</li>
<li>[Java Only] Fixed database connection leak when publishing a module. (RPD-2298)</li>
<li>[Java Only] Fixed memory leak caused by redeploying modules while the debugger has active sessions.</li>
</ul>
<h2 id="Platform_Server_10.0.603.201_Mobile_Improvements">Platform Server 10.0.603.201 Mobile Improvements</h2>
<div class="info">
<p>Released on Aug 23, 2017</p>
</div>
<h3 id="New_in_Platform_Server_10.0.603.201_Mobile_Improvements">New in Platform Server 10.0.603.201 Mobile Improvements</h3>
<ul>
<li>Improved the load time of mobile application screens for first-time visits. (RRCT-745)</li>
<li>Reduced the amount of data transferred from the server when detecting if a new application version is available. (RRCT-705)</li>
<li>The threshold for the list widget OnScrollEnding callback trigger was tuned from 1000px to 2000px to improve the final user experience on <a href="https://success.outsystems.com/Documentation/Best_Practices/Development/OutSystems_Mobile_Best_Practices#Optimize_the_Loading_of_Lists">infinite scroll patterns</a>. (RAFT-779)</li>
</ul>
<h3 id="Bug_Fixing_30">Bug Fixing</h3>
<ul>
<li>Fixed an issue that prevented a mobile app user from leaving the splash screen after the rollback of an app upgrade. (RRCT-758)</li>
<li>Fixed an issue that would cause a mobile app to keep reloading when the rollback of an app upgrade failed. (RRCT-700)</li>
<li>Fixed an issue that prevented a mobile app from doing a rollback of a failed upgrade that had started when the user opened the app for the first time. (RRCT-697)</li>
<li>Fixed an issue with navigation in mobile apps when clicking a link that wasn't fully initialized yet. (RAFT-800)</li>
</ul>
<h2 id="Platform_Server_10.0.603.0">Platform Server 10.0.603.0</h2>
<div class="info">
<p>Released on June 19, 2017</p>
</div>
<h3 id="New_in_Platform_Server_10.0.603.0">New in Platform Server 10.0.603.0</h3>
<ul>
<li>Improved the generation of mobile apps through Service Studio Native Platforms tab: is now possible to configure and generate a mobile app for a given platform while the other platform is still being generated; is now possible to change the iOS certificate password without having to reupload the certificate file; improved the accuracy of the mobile app generation progress bar; the error message now includes a timestamp. (RNMT-448)</li>
<li>Improved mobile apps robustness in poor network coverage by increasing the timeout when requiring JavaScript libraries. (RRCT-559)</li>
<li>Added <a href="https://success.outsystems.com/Documentation/10/Managing_the_Applications_Lifecycle/Secure_the_Applications/Use_an_External_Authentication_Provider" title="Use an External Authentication Provider">External Authentication</a> capabilities to Enterprise Cloud offers. (RSCT-220)</li>
<li>Reviewed Japanese translations in LifeTime. (RLIT-839)</li>
<li>Added a command line flag to the Configuration Tool to obtain the machine serial number. Useful for unattended installations. (RSAT-239)</li>
<li>Added a Boolean attribute ("show-default-value") to the mobile Input widget. When true, the default value of each type is rendered instead of showing an empty input. (RAFT-579)</li>
<li>[Java Only] Installation checklist now includes instructions to use Red Hat Subscription Manager instead of Red Hat Network. (RSAT-221)</li>
</ul>
<h3 id="Bug_Fixing_31">Bug Fixing</h3>
<ul>
<li>LifeTime is now selecting the correct external authentication provider when a user is logging in. (RLIT-950)</li>
<li>Fixed issue upgrading platform server from version 10.0.408.0 to 10.0.502.0 using MySQL and Oracle databases. (RPD-2352)</li>
<li>Changes to mobile native configurations now correctly generate a native build in the next publish. (RPD-2075)</li>
<li>Logs sent by mobile apps now use the server time instead of the device time. (RPD-1950)</li>
<li>Fixed connectivity error while trying to generate a mobile app when using an authenticated proxy. (RPD-2253)</li>
<li>Fixed an issue that was preventing mobile apps to cache updated resources from the server. (RPD-2042)</li>
<li>Enable content security policy report REST API method to accept other than "application/json" content type messages, for example "application/csp-report". (RPD-1731)</li>
<li>Fixed an issue in ModuleVersion_ListOldest action of DbCleaner API that was causing the absence of some modules in the returned list. (RPD-2012)</li>
<li>Service Accounts are no longer included in User_List output provided by the UserManagementService web service (LifeTime Services API). (RLIT-881)</li>
<li>Fixed scenarios where version suffixes wouldn't be properly updated after the One-Click Publish, causing the browser to keep using outdated versions of resources that changed between versions. This issue affected only Web Applications in Development Mode. (RPD-2034)</li>
<li>Site Property values set through Service Center are now correctly propagated to all front-ends. Applies to Oracle installations. (RPD-2038)</li>
<li>Fixed database permission errors when producer and consumer eSpaces are deployed in different MDC catalogs. (RPD-2084)</li>
<li>Fixed possible data loss when using type conversions in entity Update Actions. (RPD-2098)</li>
<li>Fixed an error that was causing Editable Tables to lose formatting in iPhone after editing a row. (RPD-2140)</li>
<li>Fixed arithmetic overflow error in LifeTime Analytics when the sum of grouped data exceeded the max integer value. (RPD-2174)</li>
<li>Fixed a client-side error in Chrome browser that was occurring when an Ajax request was triggered by an autocomplete input to refresh that input. (RPD-2183)</li>
<li>X-UA-Compatible header is now correctly added to all eSpaces. (RPD-2186)</li>
<li>Fixed an issue that would cause Configuration Tool to log some passwords in clear text. (RPD-2213)</li>
<li>The behavior of automatic activity's retry for timeouts and errors has been standardized to have an exponential backoff retry time. (RPD-2091)</li>
<li>Removed "undefined" from the error log messages of some native upgrade errors. (RPD-1954)</li>
<li>Modified the generated error message of invalid values Date, Time and DateTime in Exposed REST APIs to avoid sending the text back in the service response and making them consistent with the other data types. (RPD-1959)</li>
<li>Fixed a null pointer exception in session fixation protection when doing requests to the server. (RPD-2217)</li>
<li>[.NET Only] Fixed compilation error when consuming a SAP service with several inputs of type Structure List. (RPD-2073)</li>
<li>[.NET Only] Fixed an error that was causing locked DLLs when publishing solutions. (RSCT-421)</li>
<li>[Java Only] Added tuning information about io-threads to the installation checklist for WildFly application server. (RPD-2070)</li>
<li>[Java Only] Fixed a compilation error when using an entity with a Text identifier and an attribute of type Binary Data. (RPD-2118)</li>
<li>[Java Only] Fixed an error in exposed REST APIs returning binary content that was causing OnResponse callback to affect the returned binary content. (RPD-1788)</li>
</ul>
<h2 id="Platform_Server_10.0.503.0">Platform Server 10.0.503.0</h2>
<div class="info">
<p>Released on May 31, 2017</p>
</div>
<h3 id="Bug_Fixing_32">Bug Fixing</h3>
<ul>
<li>Fixed issue upgrading Platform Server from version 10.0.408.0 to 10.0.502.0 using MySQL and Oracle databases. (RPD-2352)</li>
</ul>
<p> </p>
<h3 id="Known_Issue">Known Issue</h3>
<ul>
<li>If using a custom authentication provider which remaps usernames, users will not be able to login in LifeTime.</li>
</ul>
<h2 id="Platform_Server_10.0.502.0">Platform Server 10.0.502.0</h2>
<div class="info">
<p>Released on May 24, 2017</p>
</div>
<h3 id="New_in_Platform_Server_10.0.502.0">New in Platform Server 10.0.502.0</h3>
<ul>
<li>App Feedback is now available for Mobile Application. (RLIT-894)</li>
<li>Added support for Unicode characters in application names. (RPD-1457)</li>
<li>Improved the loading time of the page that lists Applications in LifeTime. (RPD-1928)</li>
<li>Improved the performance of the page used to create a deployment plan in LifeTime. (RPD-1929)</li>
<li>Improved handling of process events when the system has hundreds of thousands of events in the queue. (RSWT-252)</li>
<li>[.NET Only] Added support for Windows Server 2016. (RSAT-64)</li>
<li>[.NET Only] Added support for Microsoft SQL Server 2016. (RSAT-3)</li>
<li>[.NET Only] Added support for Application Pools in Integrated mode. (RSAT-294)</li>
<li>[Java Only] Upgraded Microsoft JDBC Driver for SQL Server from version 4.1 to 6.0. (RSAT-35)</li>
</ul>
<h3 id="Bug_Fixing_33">Bug Fixing</h3>
<ul>
<li>Fixed an issue that was preventing the mobile application to cache updated resources from the server. (RPD-2042)</li>
<li>Fixed issues that prevented mobile applications from rolling back faulty upgrades. (RRCT-448)</li>
<li>After changing the configurations of a mobile application in Service Center, the message informing that the mobile application needs to be generated is now correctly displayed. (RPD-2008)</li>
<li>Fixed an issue in generated mobile applications causing the absence of necessary resources to work offline when the application was published in two-step mode and required Impact Analysis. (RPD-1934)</li>
<li>Fixed "Invalid compiler output" error during the Impact Analysis in staging and solution publish of mobile applications. (RPD-1934)</li>
<li>Fixed an issue occurring in mobile applications at runtime that was allowing the end-user to type more text than the defined Max. Length in Input and Text Area widgets. (RPD-1949)</li>
<li>Fixed an issue in the upload widget for mobile applications that was preventing devices in Android 4.4.2 to see the uploaded file name. (RPD-1983)</li>
<li>Database images are now correctly refreshed when they change. (RPD-1523)</li>
<li>Fixed the date time of the user last login in MySQL. (RPD-1639)</li>
<li>Improved the performance of deleting emails in MySQL. (RPD-1554)</li>
<li>Fixed an issue in FormatText() built-in function occurring when the given padding char was an empty string. (RPD-1870)</li>
<li>Fixed an issue in the validation e-mail function that was validating emails with two consecutive dots. (RPD-1742)</li>
<li>Fixed the logging mechanism for consumed REST APIs to no longer log when Activity Logging is disabled. Errors are still logged. (RPD-1903)</li>
<li>LifeTime users are now allowed to discard their own deployment plans. (RPD-1641)</li>
<li>Fixed an issue in LifeTime information screens that was causing mobile builds to be incorrectly marked as outdated. (RPD-1751)</li>
<li>Fixed the user synchronization when LifeTime is not installed in a dedicated environment. (RPD-280)</li>
<li>Clicking the Service Account link in LifeTime's Application Permissions screen now redirects to the correct screen. (RPD-1645)</li>
<li>Fixed breadcrumb in LifeTime's Service Account detail screen. (RPD-1646)</li>
<li>LifeTime now allows specifying multiple Content Security Policy report-to directive values. It also allows overriding the default value of this directive. (RPD-1920)</li>
<li>Content Security Policy report-to directive default value is now being replaced by the correct internal URL and directive violations are being logged in Error Log. (RPD-1902)</li>
<li>The limit of characters in Content Security Policy properties fields within LifeTime application security settings was increased to the number of characters supported in the database. (RPD-2015)</li>
<li>LifeTime is now catching the error and showing an explanatory error message if there are conflicts with the application name when deploying to an environment. (RPD-1056)</li>
<li>Fixed LifeTime Deployment API v1 method "/environments/{EnvironmentKey}/applications/{ApplicationKey}/content/" to return a valid download link. (RPD-1748)</li>
<li>Method Command.CreateParameter from RuntimePublic.Db API now respects parameter value when called twice. (RPD-1442)</li>
<li>Fixed an issue that was causing BPT Processes to be locked after changed and deployed via Service Studio 1-Click-Publish. (RPD-1312)</li>
<li>The event subscriptions for processes that use the "Launch On" property are now cleared when deleting a module. (RSWT-253)</li>
<li>[.NET Only] Fixed exposed REST APIs that were not working when debugging in the Personal Area. (RPD-1762)</li>
<li>[Java Only] Fixed an issue that was blocking a new installation using Java stack with MySql database. (RPD-2179)</li>
</ul>
<h3 id="Known_Issues_2">Known Issues</h3>
<ul>
<li>If using Oracle or MySQL databases, an error will occur in Configuration Tool when upgrading from version 10.0.408.0 to version 10.0.502.0. To fix the issue, install version 10.0.503.0.</li>
<li>If using a custom authentication provider which remaps usernames, users will not be able to login in LifeTime. </li>
</ul>
<h2 id="Platform_Server_10.0.408.0">Platform Server 10.0.408.0</h2>
<div class="info">
<p>Released on April 19, 2017</p>
</div>
<h3 id="New_in_Platform_Server_10.0.408.0">New in Platform Server 10.0.408.0</h3>
<ul>
<li>Improved the performance of the Login operation.</li>
</ul>
<h3 id="Bug_Fixing_34">Bug Fixing</h3>
<ul>
<li>Fixed an infinite loop while publishing a solution due to constantly trying to generate native builds of mobile apps that failed to publish.</li>
<li>Fixed the performance issue when a deployment was prepared in the LifeTime interface.</li>
<meta charset="utf-8"/>
<li>Fixed incorrect URL paths that sometimes were generated in style sheets when publishing solutions, which lead applications to be unavailable offline.</li>
<li>Fixed the compiled code of action flows that, in very particular scenarios, raised an unwanted exception at runtime.</li>
<li>Fixed a compilation error when consuming an Entity with attributes with default values.</li>
<li>Added a compilation error when generating queries with join types (e.g.: FULL JOIN) that are not supported by the underlying database (e.g.: MySQL).</li>
<li>Fixed a runtime error caused by calling a client-side action without arguments inside a JavaScript node, even if all parameters were optional.</li>
<li>Fixed runtime error due to a missing implicit conversion from Record List to List when assigning the result of a client-side function to a variable.</li>
<li>Fixed runtime error when running in the Personal Area and debugging elements consumed from another module.</li>
<li>Fixed error when running in the Personal Area and the Entry Module is a consumer module.</li>
<li>Fixed a different behavior when comparing compound data types (like structures or entities) on client and server sides.</li>
<li>Fixed a publish error after changing the entity action in the 'Start On' property of a Conditional Start to an action of another entity and then deleting the previous entity.</li>
<li>Fixed the feedback message that sometimes did not disappear in Android 4.4 devices.</li>
<li>Fixed a compilation error after changing the database catalog of a mobile application with local storage.</li>
<meta charset="utf-8"/>
<li>Fixed an error when upgrading mobile applications created in version 10.0.200.0 to a newer version.</li>
<li>Fixed raising an error when OnAfterFetch is executed and the element to render data is no longer present on the page.</li>
<li>PreviewInDevices module is no longer available by default in Production environments.</li>
<li>Fixed a compilation error when a Boolean Literal was assigned to a Long Integer variable.</li>
<li>Fixed the user permissions to tag a version in LifeTime, where users with different permissions in different environments always had the most restrictive permissions from all environments.</li>
<li>Changed Service Accounts in LifeTime to be defined by a name and username (instead of just the username), which allows identifying if an application was deployed by a service account or a single user.</li>
<meta charset="utf-8"/>
<li>Fixed tooltip text in the Application Details page in LifeTime that was showing HTML tags.</li>
<li>Fixed the consumption of SOAP Enum elements with only white spaces. They were created as Item and used as Item instead of white spaces.</li>
<li>Fixed the performance issue in dequeuing emails with MySQL.</li>
<li>Fixed error message in Configuration Tool that was referring Oracle when upgrading a MySQL database.</li>
<li>[.NET Only] Fixed a client-side error when a list of binary data containing nulls (NullBinary) is used in a call to the server.</li>
<li>[.NET Only] Fixed Service Center when it sometimes hanged while publishing modules or extensions that needed to be upgraded.</li>
<li>[.NET Only] Fixed Configuration Tool and OutSystems Solution Pack Tool (OSPTool) to block and wait for requested operations to finish.</li>
<li>[.NET Only] Fixed variables that lost their value when it was set inside an On Notify action of a Web Block/Web Screen that was not rendered.</li>
<li>[.NET Only] Fixed error when compiling consumed REST methods with DateTime parameters.</li>
<li>[.NET Only] Fixed applications that were changing to the default language after logging out or switching tenant.</li>
<li>[Java Only] Fixed a type conversion error when calling a SOAP web service with a list of enumerates.</li>
<li>[Java Only] Fixed the advanced configuration for MySQL in Configuration Tool that was not asking for the database server and schema.</li>
</ul>
<h3 id="Known_Issues_3">Known Issues</h3>
<ul>
<li>Unable to perform a new installation using Java stack with MySql database. As workaround, in Configuration Mode step of Configuration Tool, select option "2 - Advanced Configuration" and enter a space in the "Extra parameters" field.</li>
</ul>
<h2 id="Platform_Server_10.0.405.0">Platform Server 10.0.405.0</h2>
<h3 id="New_in_Platform_Server_10.0.405.0">New in Platform Server 10.0.405.0</h3>
<ul>
<li>Added Session Fixation Protection by default to Web applications</li>
<li>New command-line API to automate the platform installation. Read more about it in <a href="https://success.outsystems.com/Documentation/11/Setting_Up_OutSystems/Unattended_Installation_and_Upgrade" title="https://success.outsystems.com/Support/Enterprise_Customers/Installation/Unattended_Installation_and_Upgrade">the Unattended Installation and Upgrade document</a>.</li>
<li>Improved performance of the Upload step in 1-Click Publish (Service Studio)</li>
<li>Improved the LifeTime API with a REST API for module service that allows listing modules and their details.</li>
</ul>
<h3 id="Bug_Fixing_35">Bug Fixing</h3>
<ul>
<li>Security tab is now shown for mobile apps in Service Center application page. (#1581294)</li>
<li>LifeTime now allows hotfixes to be marked as resolved when the application is not published in the development environment. (#1389742)</li>
<li>Improved the robustness of LifeTime's synchronization of applications with a great number of module versions. (#1522858)</li>
<li>Fixed JavaScript injections (XSS attack) on List Records, TableRecords, and EditableTables. (#1548057)</li>
<li>Fixed some server exceptions that were not being correctly transmitted to Mobile Applications making their detail message blank. (#1463637)</li>
<li>Fixed referenced resources (from Web Responsive to Mobile modules) not being bundled in the application manifest. (#1582961)</li>
<li>Fixed mobile login when the Effective User Provider is different from the module's User Provider. (#1575732)</li>
<li>Fixed the Dropdown widget positioning when opened on a tablet. (#1582969)</li>
<li>Fixed widget validations to refresh elements in a list. (#1582966)</li>
<li>Fixed error with Combo Boxes using entities with non-alphanumeric column names. (#1510165)</li>
<li>Fixed feedback balloon rendering in App Feedback. (#1582967)</li>
<li>ListDuplicate and ListFilter actions are now working properly at runtime with their outputs generated with the right name. (#1582968)</li>
<li>Fixed problem with local variables of Object type that could lead to memory leaks upon multiple navigations. (#1582971)</li>
<li>Fixed runtime errors accessing Multi-Tenant views after performing the first stage of deployment. (#1482334)</li>
<li>Fixed "Is not a constructor" error in the client-side runtime when using type conversions with referenced types in Assigns or List operations. (#1517360)</li>
<li>Fixed compilation error when consuming an Entity with attributes with default values. (#1616853)</li>
<li>Fixed a NullPointerException compilation error when the 'Compiler.CssCompilationStrategy' setting is enabled and using referenced Web Blocks with TableRecords inside the False branch of an If widget. (#1530748)</li>
<li>Fixed Service Center to correctly report incompatible dependencies when a producer fails to publish due to a locked file. (#1211480)</li>
<li>Fixed an error in Service Center while checking Mobile Apps Service with the Force HTTPS setting activated. (#1545874)</li>
<li>Fixed 'HTTPS connection required' error while staging applications in LifeTime when 'Force HTTPS for exposed integrations in Web Applications' is enabled. (#1536900)</li>
<li>Fixed LifeTime for not showing "The requested application doesn't exist." message when in an application detail. (#1435396)</li>
<li>Fixed the synchronization of user information between all environments in LifeTime. (#1510116)</li>
<li>Fixed error when upgrading LifeTime from version 7.0 with some type of staging information. (#1512097)</li>
<li>Fixed in LifeTime showing at the same time a feedback message and the authentication token windows, when a service account was created. (#1582972)</li>
<li>Fixed index functions introspection in Oracle. (#1542859)</li>
<li>Fixed Oracle sequences for entity identifiers of Long Integer data type that were limited to 999999999. (#1574717)</li>
<li>Fixed triggers being disabled in Oracle/MySQL when changes to entities failed in a Service Studio publish. (#1547186)</li>
<li>Fixed SQL syntax error with Oracle and MySQL when accessing the GetUserLoginAttempts page in Service Center to troubleshoot login attempts. (#1574719)</li>
<li>Fixed image flickering when an aggregate is refreshed. (#1582965)</li>
<li>Fixed an error when upgrading mobile applications from 10.0.200.0 to a newer version. (#1633811)</li>
<li>Fixed the visibility to select an older tagged version, when tagging a web responsive application in LifeTime. (#1543766)</li>
<li>[.NET Only] Fixed upgrade to 10.0.200.0 when using MS SQL 2008R2. (#1531016)</li>
<li>[.NET Only] It is now possible to access the Mobile Apps Service via an authenticated proxy. Define the proxy authentication in the Environment Configuration screen of Service Center. (#1506881)</li>
<li>[.NET Only] Fixed some 1-Click Publish errors related with file locks in .sql files. (#779059)</li>
<li>[.NET Only] Fixed variable values that were lost inside 'On Notify' destination actions if the Web Block or Web Screen was not rendered. (#1433626)</li>
<li>[.NET Only] Fixed OSP Tool crash when started without arguments. (#1582963)</li>
<li>[Java Only] Fixed source code download vulnerability when the using WildFly 8.2.0 WebServer. (#1520940)</li>
<li>[Java Only] Increased security against JavaScript injection in Web screens in some scenarios. (#1520939)</li>
<li>[Java Only] Improved the Configuration Tool feedback message when it fails to contact JBoss/Wildfly. (#663990)</li>
<li>[Java Only] Applied Oracle patch to ojdbc.jar to fix an error when fetching a blob with a length of 4193 characters. (#1531758)</li>
<li>[Java Only] Fixed Binary Data parameters in server actions that sometimes received empty data (0 bytes) when called from client actions using JPEG mime type content. (#1510111)</li>
<li>[Java Only] Fixed an erroneous behavior when WebLogic is installed in a path other than the default one or with a user other than the default one. (#1360428)</li>
<li>[Java Only] Fixed an 'No such file or directory' error when exporting data to Excel and the '/tmp/poifiles' directory has been deleted. (#1523762)</li>
</ul>
<h2 id="Platform_Server_10.0.303.0">Platform Server 10.0.303.0</h2>
<h3 id="Bug_Fixing_36">Bug Fixing</h3>
<ul>
<li>[.NET Only] Fixed an issue that was causing the upgrade of eSpaces via Service Center to get hanged. (#1584384)</li>
</ul>
<h3 id="Known_Issues_4">Known Issues</h3>
<ul>
<li>When publishing an eSpace that consumes a Local Entity with a Text attribute that has a default value filled in, an error will occur during the compilation stage. To workaround this issue, the pattern must be avoided.</li>
</ul>
<h2 id="Platform_Server_10.0.302.0">Platform Server 10.0.302.0</h2>
<div class="info">
<p>Released on Jan 03, 2017</p>
</div>
<h3 id="New_in_Platform_Server 10.0.302.0">New in Platform Server 10.0.302.0</h3>
<ul>
<li>New LifeTime Deployment API is now available. This API introduces 3 new REST services - Environments, Applications, and Deployments - which allow the automation and orchestration of OutSystems applications deployment incorporated into the processes and tools of an enterprise IT ecosystem. LifeTime Deployment API uses new Service Accounts authentication, which is managed in LifeTime.</li>
<li>Updated OutSystems brand name and image.</li>
<li>Added the ability to customize the error page to show Internal Network errors.</li>
<li>Added a "Continue with errors" link in the bottom of LifeTime deployment screen to force deployment with reference errors.</li>
<li>Changed the warnings of solution deployments with "Incompatible Consumer" to ask for confirmation before proceeding to deploy.</li>
<li>Improved performance of 1-Click Publish in development mode.</li>
<li>Improved error message when a List is overwritten in the middle of an iteration during the execution of client-side logic.</li>
</ul>
<h3 id="Side_Effects">Side Effects</h3>
<ul>
<li>EnvironmentManagementService and ApplicationManagementService SOAP Services in LifeTime Services API are now deprecated and will become officially unsupported in a future release. Applications using EnvironmentManagementService and ApplicationManagementService SOAP Services must be updated to use the REST services of the new LifeTime Deployment API instead.</li>
</ul>
<h3 id="Bug_Fixing_37">Bug Fixing</h3>
<ul>
<li>Single character names are now allowed for mobile Apps identifiers (e.g. com.example.O). (#1526042)</li>
<li>Service Center is now correctly reporting incompatible dependencies when a producer failed to publish due to a file being locked. (#1211480)</li>
<li>Fixed a compilation issue when publishing solutions containing extensions, which was skipping the recompilation of the extensions. (#1520309)</li>
<li>LifeTime now takes into account if a module has switched between applications when evaluating if the application should be published in a deployment. (#982941)</li>
<li>Fixed a compilation error when a module has Decimal values in Integer attributes of Static Entities. (#1092660)</li>
<li>Fixed 1-Click Publish not detecting changes to the Entity Model when following a publish attempt that failed due to errors in the deployment of SQL scripts. This problem was occurring only in development mode. (#1215547)</li>
<li>Changed Button Group animations to be triggered before the action's execution. (#1526047)</li>
<li>Improved runtime error message when trying to execute an outdated role action. (#1004435)</li>
<li>Fixed possible deadlock while initializing database access. (#1526046)</li>
<li>Fixed an issue with LifeTime authentication token when server name was different in LifeTime and ServiceCenter. (#1406571)</li>
<li>Fixed an issue when upgrading modules with "Run As" configuration from versions lower than 6.1 that was causing the fail of deployment. (#1412935)</li>
<li>Improved LifeTime synchronization process to tolerate inconsistencies in public elements for older module versions. (#1417317)</li>
<li>Fixed an issue in DbCleaner API to drop tables for Entities that are still in the metamodel but were already physically dropped from the database (e.g. after deleting and republishing the same application module). (#1415054)</li>
<li>Fixed an issue with Blocks' event OnParametersChanged being called twice after a query refresh in Blocks with Lists or Record parameters. (#1383456)</li>
<li>Fixed an issue of On Render event not being fired under certain circumstances. (#1526045)</li>
<li>Fixed issues during Service Studio 1-Click Publish when using an authentication plugin. (#1423585)</li>
<li>Fixed a problem in Editable Tables that allowed editing in non-editable cells when navigating with the Tab key. (#1415141)</li>
<li>Fixed an issue with back navigation, occurring when doing a back navigation immediately after an upgrade and the previous screen was deleted or renamed.</li>
<li>Fixed a communication problem when there are local variables of type Object in screens or blocks, and there are also data actions or screen data sets. (#1526039)</li>
<li>Fixed "is not a constructor" error in client side runtime when using type conversions with referenced types in Assigns or List operations. (#1517360)</li>
<li>Fixed connection problems to Mobile App Service. (#1432894)</li>
<li>Removed the "HMAC Validation Failed in Login Screen" entry that was being logged in General Logs for every Service Center login screen request. (#1526038)</li>
<li>Fixed an authentication error while deploying through LifeTime using an external authentication provider. (#1477255)</li>
<li>Fixed an error while publishing LifeTimeCore related to duplicate values trying to create unique constraint. (#1471503)</li>
<li>Fixed database permission errors when using Notify Widget action between modules deployed in different database catalogs. (#1437555)</li>
<li>Fixed preview error in Aggregates when comparing values of different numeric types (e.g. Integer and Decimal). (#1526061)</li>
<li>Fixed translations in default values of referenced input parameters. (#1340151)</li>
<li>[.NET Only] OutSystems services paths are now enclosed in quotes, thus preventing "Microsoft Windows Unquoted Service Path Enumeration" vulnerability. (#1410015)</li>
<li>[.NET Only] Fixed error when connecting to LDAP over SSL. (#1432836)</li>
<li>[.NET Only] Fixed 1-Click Publish errors due to file locks in *.sql files. (#1149429)</li>
<li>[.NET Only] Fixed runtime error when consuming a web reference with XML attributes of type unsigned long and invoking methods using this type without explicitly passing a value. (#1435431)</li>
<li>[Java Only] Fixed high CPU spikes and instability during high server load scenarios. (#1425634)</li>
<li>[Java Only] The correct exception is now being logged if it occurs when trying to obtain a lock in the Users table. (#1471536)</li>
<li>[Java Only] Fixed a compilation error in modules having SOAP Web Services with a structure output parameter containing a single element. (#1200629)</li>
<li>[Java Only] Default Java proxy configuration is now correctly applied to REST requests. (#1498750)</li>
<li>[Java Only] Fixed Configuration Tool exit code when an error occurs publishing extensions on unattended installation. (#1526049)</li>
<li>[Java Only] Fixed a concurrency issue that could cause applications to become slower or unresponsive at runtime. (#1526051)</li>
<li>[Java Only] Fixed a null pointer exception that would occasionally occur during the execution of Configuration Tool when using the WebLogic stack. (#1526043)</li>
</ul>
<h3 id="Known_Issues_5">Known Issues</h3>
<ul>
<li>When publishing an eSpace that consumes a Local Entity with a Text attribute that has a default value filled in, an error will occur during the compilation stage. This issue is resolved in <a href="http://www.outsystems.com/home/downloadsdetail/104/1950/" title="http://www.outsystems.com/home/downloadsdetail/104/1950/">version 10.0.404.0</a>.</li>
<li>[.NET Only] This version has an issue that may cause the upgrade of eSpaces via Service Center to get hanged. This is issue is resolved in <a href="http://www.outsystems.com/home/downloadsdetail/104/1948/" title="http://www.outsystems.com/home/downloadsdetail/104/1948/">version 10.0.303.0</a>.</li>
</ul>
<h2 id="Platform_Server_10.0.200.0">Platform Server 10.0.200.0</h2>
<div class="info">
<p>Released on Nov 07, 2016</p>
</div>
<h3 id="New_in_Platform_Server 10.0.200.0">New in Platform Server 10.0.200.0</h3>
<ul>
<li>"Take Offline" and "Bring Online" application operations in Service Center have been renamed to "Disable" and "Enable", to remove ambiguity regarding offline capabilities of mobile runtime applications.</li>
<li>Added UTF-8 flag to Java when compiling extensions. This adds support for database table and column names containing specific characters sets like Shift-JIS.</li>
<li>Cache header included by default in all supported application servers. Including "Cache-Control" header brings performance enhancements to application requests for static content.</li>
<li>Added support for Content Security Policies (CSP) for mobile runtime applications.</li>
<li>Added support for HTTP Strict Transport Security (HSTS) for mobile runtime applications.</li>
<li>Improved end-user experience when new mobile application versions are available.</li>
<li>[Java Only] Added TLSv1.1 and TLSv1.2 to the default cryptographic protocols in Java. This allows communication to be established using all versions of TLS protocol (1.0, 1.1, and 1.2).</li>
</ul>
<h3 id="Side_Effects">Side Effects</h3>
<ul>
<li>Some Javascript Nodes may become invalid after upgrading: Validation of JavaScript values when assigned to JavaScript node output parameters was fixed. Some unsupported values were being accepted, which may cause unexpected behaviors in the application. Invalid values assigned to output parameters will now throw an error at the end of the JavaScript node execution. </li>
</ul>
<h3 id="Bug_Fixing_38">Bug Fixing</h3>
<ul>
<li>Fixed differential compilation problem when changing the Module property of "Default Transition" (development-mode environments). ( #1435461)</li>
<li>Fixed offline support of mobile applications for scenarios where reference entity/structure definitions originating from extensions are used in client-side logic. (#1337277) </li>
<li>Fixed a problem that could cause native mobile applications to enter a permanent loop when attempting to get their version rolled back. (#1435463)</li>
<li>Fixed differential compilation problem when using reference exception flows in global exception handlers (development-mode environments). (#1435445)</li>
<li>Fixed pre-bundling of mobile runtime applications during their native shell creation process on Personal Environments. (#1435464)</li>
<li>Fixed a problem when encoding Screen input parameters of mobile native applications containing space characters. (#1435444)</li>
<li>Native mobile applications no longer generate console errors related to promises library when starting-up on Android 4.4.2. (#1435465)</li>
<li>Fixed dropdown widget not being rendered on iOS apps. (#1386439)</li>
<li>Fixed compilation error on mobile modules with client-side expressions using function calls. (#1435466)</li>
<li>Fixed mobile applications upgrade errors not being sent to the server error log on rare scenarios. (#1435467)</li>
<li>Increased strength of authentication mechanisms in mobile applications. (#1435469)</li>
<li>Security improvements in images generated URL. (#1435454)</li>
<li>Fixed several runtime issues when using “Destination” objects and an unhandled error occurs. (#1378655)</li>
<li>Fixed compilation error in mobile modules with calls to server actions in OnApplicationStart and OnApplicationResume events. (#1435471)</li>
<li>Fixed user login getting stuck in rare cases due to a database lock. The lock occurred when logging in with a user that was selected for update or was created in a transaction that was not committed yet. (#1435447)</li>
<li>In some occasions, when syncing a new application, LifeTime could end up creating multiple instances of the same application. This process was changed so that it does not run in parallel to the same application. (#1435472)</li>
<li>BPT Impact Analysis in 2nd stage works even if the module name was changed. (#1300745)</li>
<li>After a deployment that generates a new mobile app, the available download was generated with the previous version. The version of the app is now updated prior to the generation. (#1435473)</li>
<li>Lifetime takes into account if a module has switched between applications when evaluating if the application should be published in a deployment. (#982941)</li>
<li>An application with outdated or broken references shows an application level warning but does not indicate the modules where the issue is located. The warning is now available in every module with issues. (#1383438)</li>
<li>Fixed client-side runtime errors when calling Server Actions that have as output with Entities from other modules. (#1435474)</li>
<li>Fixed problems reading unicode characters in Scripts that are set as a dependency of a module. (#1435446)</li>
<li>Fixed error while creating applications when Mobile App Generation Service is unreachable. (#1415149)</li>
<li>Fixed iDB2 use of dead connections. (#1408336)</li>
<li>Improved security in DB images access. (#1389703)</li>
<li>Fixed Configuration Tool error while upgrading database model. (#1386418)</li>
<li>Fixed 'invalid login' log entry appearing during environment synchronization. (#1378809)</li>
<li>Fixed issue where attributes in the request or response of a web reference were not properly handled in runtime. (#1344068)</li>
<li>Fixed SU/AO count for Silk Universal Template. (#1507615)</li>
<li>Fixed error in lifetime synchronization when an application doesn't have security settings active (#1342984)</li>
</ul>
