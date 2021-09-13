# Reference Site for Salesforce Development    

## Developer Documentation  

### Introduction   

- [Developer Experience (**DX**)](https://developer.salesforce.com/developer-centers/developer-experience/)  
- [Lightning Web Component Reference](https://developer.salesforce.com/docs/component-library/overview/components) 
- [Apex Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.230.0.apexcode.meta/apexcode/apex_dev_guide.htm) 
- [Developer Console](https://help.salesforce.com/articleView?id=sf.code_system_log.htm&type=5#code_system_log)
- [Salesforce Extensions for Visual Studio Code](https://developer.salesforce.com/tools/vscode/)
- [Code Editor in the Salesforce User Interface](https://help.salesforce.com/articleView?id=sf.code_define_package.htm&type=5#code_define_package)  
- [Mobile Publisher](https://dreamevent.secure.force.com/articleView?id=sf.s1_branded_apps.htm&type=5)  
- [Object Reference for Salesforce and Lightning Platform](https://developer.salesforce.com/docs/atlas.en-us.224.0.object_reference.meta/object_reference/sforce_api_objects_concepts.htm)  

### Samples & References  

- [Components Reference](https://developer.salesforce.com/docs/component-library/overview/components)  
- [Code Samples and SDKs](https://developer.salesforce.com/code-samples-and-sdks)  
  - [Apex-Recipes](https://github.com/trailheadapps/apex-recipes#installing-the-app-using-an-unlocked-package)  
    - [Quick Start: Explore the Apex Recipes Sample App](https://trailhead.salesforce.com/content/learn/projects/quick-start-explore-the-apex-recipes-sample-app)  
    - [Quick Start: Tour the Sample App Gallery](https://trailhead.salesforce.com/content/learn/projects/quick-start-tour-the-sample-app-gallery)  

### Others  

- [Triggers and Order of Execution](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_triggers_order_of_execution.htm)  
- [Using Certificates to use two-way SSL authentication](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_callouts_client_certs.htm)
- [Architectural Considerations for Group and Professional Editions](https://developer.salesforce.com/docs/atlas.en-us.216.0.packagingGuide.meta/packagingGuide/dev_packages_for_pe_ge.htm) : GE / PE / EE / UE / PXE (tiered offering)  
- [Metadata Coverage](https://developer.salesforce.com/docs/metadata-coverage/51) : For change-tracking, refer to this report  

---
## Implementation 

- [Salesforce Implementation Introduction & Use Cases](https://www.youtube.com/playlist?list=PLwDkE0LEAzzGbzqF_8gr1tXA3igEdQswM) : SF Korea YouTube Video  

---
## Interface  

### General  

- [Streaming API](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm) : Events using push and receive in near real-time  
- [Intro to Marketing Cloud APIs](https://developer.salesforce.com/docs/atlas.en-us.mc-apis.meta/mc-apis/index-api.htm) : REST vs SOAP  
- [REST VS SOAP: When Is REST Better?](https://stormpath.com/blog/rest-vs-soap)  
- [Getting started with Salesforce integration patterns using MuleSoft](https://developer.mulesoft.com/tutorials-and-howtos/quick-start/getting-started-with-salesforce-integration-patterns-using-mulesoft/?utm_source=email&utm_medium=referral&utm_campaign=anypoint-onboarding-nurture&mkt_tok=NTY0LVNaUy0xMzYAAAF8HgHgm8BDPosP49-vPl-Gk8G60ZwYtrQQIC-cWqkbu2TdYNQnX_YoMu2KUD3S6H5Jm9C8XfiF7M5MKCmL6_BuwXxyHvqgSYGFHd7dxwDcSwuev4U) : Migration / Broadcast / Aggregation / Bidirectional synchronization / Correlation - Hands-on examples  
- [Get Started with Open CTI](https://developer.salesforce.com/docs/atlas.en-us.api_cti.meta/api_cti/sforce_api_cti_intro.htm)  
- [Ant Migration Tool](https://developer.salesforce.com/docs/atlas.en-us.daas.meta/daas/meta_development.htm)  
- [Saving CSV/Excel file as UTF-8 Encoded](https://www.webtoffee.com/how-to-save-csv-excel-file-as-utf-8-encoded/)  
- [How to check and monitor SSL certificates expiration](https://songrgg.github.io/operation/how-to-check-and-monitor-tls-jks-certificates-with-telegraf/)  
- [OAuth Authorization Flows](https://help.salesforce.com/s/articleView?id=sf.remoteaccess_oauth_flows.htm&type=5)  
- [Upcoming Certificate Changes](https://trailhead.salesforce.com/trailblazer-community/feed/0D54S00000C382XSAR)  
- [Upcoming Certificate Changes Group Join](https://trailhead.salesforce.com/trailblazer-community/groups/0F9300000001oAFCAY?tab=members)  

### Integration (Authentication)    

- [Connect REST API Quick Start](https://developer.salesforce.com/docs/atlas.en-us.232.0.chatterapi.meta/chatterapi/quickstart.htm)  
- [Create a Connected App](https://help.salesforce.com/s/articleView?id=sf.connected_app_create.htm&type=5)  
  - [Enable OAuth Settings for API Integration](https://help.salesforce.com/s/articleView?id=sf.connected_app_create_api_integration.htm&type=5)  
  - [Integrate Service Providers as Connected Apps with SAML 2.0](https://help.salesforce.com/s/articleView?id=sf.connected_app_create_saml_sso.htm&type=5) : Tableau Server Connection    
  - [Generate an Initial Access Token](https://help.salesforce.com/s/articleView?id=sf.remoteaccess_oidc_initial_access_token.htm&type=5)  
  - [Configure Remote Site Settings](https://help.salesforce.com/s/articleView?id=sf.configuring_remoteproxy.htm&type=5)  
- [Know more about all the SSL certificates that are supported by Salesforce](https://help.salesforce.com/s/articleView?id=000326722&type=1)  
- [Generate a Certificate Signed by a Certificate Authority](https://help.salesforce.com/s/articleView?id=sf.security_keys_uploading_signed_cert.htm&type=5)  
- [[Forum] Self Signed Certificate Expires](https://developer.salesforce.com/forums/?id=9060G000000BghEQAS) : Self Signed Certificate Replace & IdP 
- [Do I need to convert .CER to .CRT](https://stackoverflow.com/questions/642284/do-i-need-to-convert-cer-to-crt-for-apache-ssl-certificates-if-so-how) : vs CSR (certificate signing request)    
- [Certificate Decoder](https://www.sslshopper.com/certificate-decoder.html)  

---
### Experience Cloud

- [Customize the Theme of Your Experience Builder Site](https://help.salesforce.com/s/articleView?id=sf.community_builder_theme_customize.htm&type=5)   

---
### Heroku  

- [Add Heroku dynos to IP allowlist ](https://help.heroku.com/JS13Y78I/i-need-to-add-heroku-dynos-to-our-allowlist-what-are-ip-address-ranges-in-use-at-heroku)  


