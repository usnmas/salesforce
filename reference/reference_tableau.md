# Reference Site for Tableau    

## Tableau Overall

- [Tableau Help](https://www.tableau.com/support/help)  
- [Tableau Prep - Connect to Data](https://help.tableau.com/current/prep/en-us/prep_connect.htm#salesforce_data)  
- [Extracts / Live Connections / Cloud Data](https://www.tableau.com/about/blog/2016/4/tableau-online-tips-extracts-live-connections-cloud-data-53351)  
- [Extracts-1: Understanding Data Extracts](https://www.tableau.com/about/blog/2014/7/understanding-tableau-data-extracts-part1)  
- [Extracts-2: Why use Data Extracts](https://www.tableau.com/about/blog/2014/7/why-use-tableau-data-extracts-32187)   
- [Extracts-3: Tips, Tricks and Best Practices](https://www.tableau.com/tableau-data-extracts-part3)  
- [Join Your Data](https://help.tableau.com/current/pro/desktop/en-us/joining_tables.htm)  
- [Tableau's Order of Operations](https://help.tableau.com/current/pro/desktop/en-us/order_of_operations.htm)  

## Tableau Server  

- [Tableau Server: Communicating with the Internet](https://help.tableau.com/current/server/en-us/plan_network.htm)  
- [Tableau Server on Windows: Everybody's Install Guide / Connecting to Data Sources](https://help.tableau.com/current/guides/everybody-install/en-us/everybody_admin_data.htm)  
- [Sign in to Tableau Services Manager Web UI](https://help.tableau.com/current/server/en-us/sign_in_tsm.htm)  
- [Tableau Server on Windows: Manage Data](https://help.tableau.com/current/server/en-us/manage_data_section.htm)  
- [Backup and Restore](https://help.tableau.com/current/server/en-us/db.htm)  

## Tableau Server User & License  

- [Add Users to Tableau Server](https://help.tableau.com/current/server/en-us/users_add.htm)  
- [Add Capacity to Tableau Server](https://help.tableau.com/current/server/en-us/capacity_add.htm)  
- [Zero Downtime Licensing](https://help.tableau.com/current/server/en-us/license_zero_downtime.htm)  
- [Add or Delete Sites](https://help.tableau.com/current/server/en-us/sites_delete.htm)  
- [Manage Site Role Limits](https://help.tableau.com/current/server/en-us/site_role_limit.htm)  
- [Troubleshoot Licensing](https://help.tableau.com/current/server/en-us/unlicensed.htm)  
- [Set Users’ Site Roles](https://help.tableau.com/current/server/en-us/users_site_roles.htm)  
- [Set the User Authentication Type for SAML](https://help.tableau.com/current/server/en-us/users_set_auth_type.htm)  
- [Unable to Change a User's Site Role to A Server Administrator When Site-SAML is Enabled](https://kb.tableau.com/articles/issue/unable-to-change-a-user-s-site-role-to-a-server-administrator-when-site-saml-is-enabled)  
- [CSV Import File Guidelines](https://help.tableau.com/current/server/en-us/csvguidelines.htm)  

## Salesforce Integration  

- [Tableau Server on Windows: Server Admin Cheatsheet: Salesforce Integration](https://help.tableau.com/current/server/en-us/tableau_admin_salesforce_integration.htm)  
- [Supported Connectors - Salesforce](https://help.tableau.com/current/pro/desktop/en-us/examples_salesforce.htm)  
- [Cross-database join limitations with Salesforce (multi-connection data source)](https://help.tableau.com/current/pro/desktop/en-us/examples_salesforce.htm)
  - Live connection / Extract Filters / Incremental updates to the extract / Viewing the data in the data grid 가 지원 안 됨
  - Field with over 4096 Characters & Calculated Field 는 extract 에 include 안 됨
  - Extract 는 columnar database store 이므로 column 이 많아지면 성능 저하  
- [Salesforce Fields Do Not Appear As Expected](https://kb.tableau.com/articles/issue/salesforce-fields-do-not-appear-as-expected)  
- [Configure SAML with Salesforce](https://help.tableau.com/current/online/en-us/saml_config_salesforce.htm)  
- [Introducing a new way to bring Tableau analytics into Salesforce](https://www.tableau.com/about/blog/2020/9/introducing-tableau-viz-lightning-web-component-salesforce)  
- [Embed Tableau Dashboard in Salesforce Records Using an iframe](https://aaronwinters.com/embed-tableau-dashboard-in-salesforce-records-using-visualforce/)  
- [Configure SSO from Salesforce to Tableau Online](https://help.salesforce.com/articleView?id=identity_provider_examples_tableau_online.htm&type=0)  
- [How to configure Tableau SAML SSO with Salesforce Identity](https://alexeskinasy.medium.com/how-to-configure-tableau-online-saml-sso-with-salesforce-identity-53bdf0f9b3f2)  
- [Dashboard Starters for Cloud-based Data](https://help.tableau.com/current/pro/desktop/en-us/starters.htm)  
- [Download a Starter Dashboard](https://www.tableau.com/products/dashboard-starters-downloads)  
- [Refresh Extracts](https://help.tableau.com/current/pro/desktop/en-us/extracting_refresh.htm)  
- [Schedule Extract Refreshes as You Publish a Workbook](https://help.tableau.com/current/pro/desktop/en-us/publish_workbooks_schedules.htm)  
- [Keep Data Fresh](https://help.tableau.com/current/online/en-us/to_keep_data_fresh.htm#refresh-options)  
  
## Build Charts and Analyze Data  

- [Start Building a Visualization by Dragging Fields to the View](https://help.tableau.com/current/pro/desktop/en-us/buildmanual_dragging.htm)  
- [How To Apply Multiple Filters To The Same Dimension Simultaneously](https://kb.tableau.com/articles/howto/How-To-Apply-Multiple-Filters-To-The-Same-Dimension-Simultaneously) 
- [Create an OR Condition Between Two Filters](https://kb.tableau.com/articles/HowTo/Create-an-OR-Condition-Between-Two-Filters)  
- [How To Filter Data In AND Logic When Selecting Multiple Dimension Members](https://kb.tableau.com/articles/HowTo/How-To-Filter-Data-In-AND-Logic-When-Selecting-Multiple-Dimension-Members)  
  - Multiple Filter 를 Worksheet 에 사용하게 되면 Default 는 AND 조건으로 연결이 됩니다.
  - 1개의 Dimension 에서 2개 이상의 Filter 를 걸고자 한다면, 그 Dimension 을 Duplicate 해서, 원래 Dimension 에 Filter1 을 걸고, Duplicate 된 "Dimension (Copy)" 에 Filter2 를 걸면 적용이 됩니다.
  - Multiple Filter 를 Worksheet 에 적용할 때 OR 조건으로 해야 한다면, 조건을 설정하는 Parameter 를 각각 생성하고, 그 Parameter 들을 OR 로 합치는 Calculated Field 를 생성하여 이 Calculation 을 Filter 에 True 로 넣으면, Parameter 선택에 따른 조건을 OR 조건으로 사용할 수 있습니다.
  - Tableau 에서 "Long Text Area" field type 은 Extract 시 4096 character limit 이 있습니다. 그래서 Tableau 에서 나오지 않습니다.
  - Tableau Custom SQL : select Name, Id from Account where Id in (Select SalesPartner__c from Opportunity) 
- [Create Relative Date Filters](https://help.tableau.com/current/pro/desktop/en-us/qs_relative_dates.htm)  
- [Filter Data from Your Views](https://help.tableau.com/current/pro/desktop/en-us/filtering.htm#ShowFilter)  
- [Create Sets](https://help.tableau.com/current/pro/desktop/en-us/sortgroup_sets_create.htm)  
- [Analyze Data](https://help.tableau.com/current/pro/desktop/en-us/analyze.htm)    
- [When to Use Filters, Groups & Sets in Tableau](https://interworks.com/blog/kwagner/2014/06/30/when-use-filters-groups-sets-tableau/)  

## Tableau Blueprint  

- [Tableau Blueprint Overview](https://help.tableau.com/current/blueprint/en-us/bp_overview.htm)  
- [Visual Best Practices](https://help.tableau.com/current/blueprint/en-us/bp_visual_best_practices.htm)  

