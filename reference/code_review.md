# Salesforce Code Review   

--- 

- Code 가 best Practice 와 pattern 을 따르고 있는가?

  - [PMD](https://pmd.github.io/latest/pmd_rules_apex.html)
  - [AppExchange Solution](https://appexchange.salesforce.com/listingDetail?listingId=a0N30000009xZ3WEAU)
  - [CRM Tool : Code Scanner](https://cloudtoolkit.co)  

- Code 가 Design Principal 을 따르는가? : 자동화 불가. Manual 작업 필요  

  - Code 가 Design Principal 을 따르고 있는가   
  
    - ex) 각 지역단위로 다르게 적용되는 코드의 경우 코드가 Module 로 되어 있는가 또는 Configuration 을 지원하는가  
    - ex) Code 가 Naming Convention 을 따르는가  
    
  - 각각의 코드에 대한 Unit Test 가 Test Class 를 통하여 구성되어 있는가 : Test Class 구성범위 결정 필요  
  
    - ex) Process builder 와 Flow 를 포함할 것인가  
    
  - Batch 작업의 대상이 되는 Object 를 사용하는 경우 Bulk Test 가 포함되어 있는가  
  
- Code 의 Unit Test 가 잘 구현되어 있는가  

  - 위 과정을 통하여 Test Class 의 Unit Test case 들이 잘 구현되었는지 확인하고 Test Class 를 실행하여 Fail 되는 Test Class 없이 Coverage 가 75% 이상임을 확인  




