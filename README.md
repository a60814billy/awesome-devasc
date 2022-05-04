# DevAsc 200-901 Exam Study Topics

[Latest Exam Topics](https://developer.cisco.com/certification/exam-topic-associate/)

## 1.0 Software Development and Design (15%)
### Topics
- 1.1 Compare data formats (XML, JSON, YAML)
- 1.2 Describe parsing of common data format (XML, JSON, YAML) to Python data structures
- 1.3 Describe the concepts of test-driven development
- 1.4 Compare software development methods (agile, lean, waterfall)
- 1.5 Explain the benefits of organizing code into methods/ functions, classes, and modules
- 1.6 Identify the advantages of common design patterns (MVC and Observer)
- 1.7 Explain the advantages of version control
- 1.8 Utilize common version control operations with Git:
    - 1.8.a Clone
    - 1.8.b Add/remove
    - 1.8.c Commit
    - 1.8.d Push / pull
    - 1.8.e Branch
    - 1.8.f Merge and handling conflicts
    - 1.8.g diff

### Resources

#### JSON, YAML, XML

#### data format 
- [JSON](https://www.json.org/json-en.html)
- [YAML](https://yaml.org/)
- [XML](https://www.w3.org/TR/xml/)
- [JSON <-> YAML converter](https://www.json2yaml.com/)

#### parsing data format to python data structure
- json
    - [Python json module (build-in)](https://docs.python.org/3/library/json.html)
    - [jsonpickle](https://jsonpickle.github.io/)
    - [jsonschema](https://python-jsonschema.readthedocs.io/en/stable/)
- yaml
    - [pyyaml](https://pyyaml.org/)
    - [ruamel.yaml](https://yaml.readthedocs.io/en/latest/)
    - [yamllint](https://yamllint.readthedocs.io/en/stable/)
- xml
    - [Python XML module - xml.etree.ElementTree](https://docs.python.org/3/library/xml.etree.elementtree.html#module-xml.etree.ElementTree)
    - [Python XML module - xml.dom.minidom](https://docs.python.org/3/library/xml.dom.minidom.html#module-xml.dom.minidom)
    - [lxml](https://lxml.de/)
    - [xmltodict](https://github.com/martinblech/xmltodict)

#### TDD
- [The Art of Agile Development: Test-Driven Development](http://www.jamesshore.com/v2/books/aoad1/test_driven_development)
- [Let's Play: Test-Driven Development](http://www.jamesshore.com/v2/projects/lets-play-tdd)

#### Agile
- [敏捷開發宣言](https://agilemanifesto.org/iso/zhcht/manifesto.html)
- [Scrum Guide 2020](https://scrumguides.org/scrum-guide.html)
- [Atlassian Agile Coach](https://www.atlassian.com/agile)

#### Design Pattern
- [Observer](https://refactoring.guru/design-patterns/observer)
- [Everything you need to know about MVC architecture](https://towardsdatascience.com/everything-you-need-to-know-about-mvc-architecture-3c827930b4c1)

#### Git Study
- [連猴子都能懂的Git入門指南](https://backlog.com/git-tutorial/tw/)
- [Git](https://git-scm.com/)
- [Pro Git 2nd Free Ebook](https://git-scm.com/book/en/v2)

#### 組織程式碼
- function
    > A series of statements which returns some value to a caller. It can also be passed zero or more arguments which may be used in the execution of the body. See also parameter, method, and the Function definitions section.
- method
    > A function which is defined inside a class body. If called as an attribute of an instance of that class, the method will get the instance object as its first argument (which is usually called self). See function and nested scope.
- class
    > A template for creating user-defined objects. Class definitions normally contain method definitions which operate on instances of the class.
- module
    > An object that serves as an organizational unit of Python code. Modules have a namespace containing arbitrary Python objects. Modules are loaded into Python by the process of importing.
- package
    > A Python module which can contain submodules or recursively, subpackages. Technically, a package is a Python module with an __path__ attribute. See also regular package and namespace package.
- regular package
    > A traditional package, such as a directory containing an __init__.py file.

#### 書
- [深入淺出 Python, 2/e (Head First Python: A Brain-Friendly Guide, 2/e)](https://www.tenlong.com.tw/products/9789864769902?list_name=srh)
- [物件導向設計模式－可再利用物件導向軟體之要素 (精裝典藏版) (Design Patterns: Elements of Reusable Object-Oriented Software)
](https://www.tenlong.com.tw/products/9789572054116?list_name=srh)
- [為你自己學 Git](https://gitbook.tw/)
- [Kent Beck 的測試驅動開發：案例導向的逐步解決之道 (Test-Driven Development: By Example)(TDD)](https://www.tenlong.com.tw/products/9789864345618)
- [Learning Agile: Understanding Scrum, XP, Lean, and Kanban](https://www.tenlong.com.tw/products/9781449331924)
- [Lean Software Development: An Agile Toolkit](https://www.amazon.com/Lean-Software-Development-Agile-Toolkit/dp/0321150783/ref=sr_1_1?crid=2DJTF2A2QL1BL&keywords=Lean+Software+Development&qid=1651673367&sprefix=%2Caps%2C230&sr=8-1)
- [The Art of Agile Development](https://www.amazon.com/Art-Agile-Development-James-Shore/dp/1492080691/ref=sr_1_1?keywords=The+Art+of+Agile+Development&qid=1651673525&sr=8-1)

## 2.0 Understanding and Using APIs (20%)
### Topics
- 2.1 Construct a REST API request to accomplish a task given API documentation
- 2.2 Describe common usage patterns related to webhooks
- 2.3 Identify the constraints when consuming APIs
- 2.4 Explain common HTTP response codes associated with REST APIs
- 2.5 Troubleshoot a problem given the HTTP response code, request and API documentation
- 2.6 Identify the parts of an HTTP response (response code, headers, body)
- 2.7 Utilize common API authentication mechanisms: basic, custom token, and API keys
- 2.8 Compare common API styles (REST, RPC, synchronous, and asynchronous)
- 2.9 Construct a Python script that calls a REST API using the requests library

### Resources
- [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
- [HTTP Response code](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [HTTP Authentication](https://developer.mozilla.org/en-US/docs/Web/HTTP/Authentication)
- [HTTP Content negotiation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation)
- [SOAP](https://www.w3.org/TR/soap/)
- [Producing a SOAP web service in Spring Framework](https://spring.io/guides/gs/producing-web-service/)
- [JSON RPC](https://www.jsonrpc.org/)
- [XML-RPC](http://xmlrpc.com/)
- [RESTful Web API 設計](https://docs.microsoft.com/zh-tw/azure/architecture/best-practices/api-design)
- [REST API Tutorial](https://restfulapi.net/)
- [REST API Design: Filtering, Sorting, and Pagination](https://www.moesif.com/blog/technical/api-design/REST-API-Design-Filtering-Sorting-and-Pagination/)
- [RateLimit Header Fields for HTTP](https://www.ietf.org/archive/id/draft-polli-ratelimit-headers-02.html)

## 3.0 Cisco Platforms and Development (15%)
- 3.1 Construct a Python script that uses a Cisco SDK given SDK documentation
- 3.2 Describe the capabilities of Cisco network management platforms and APIs (Meraki, Cisco DNA Center, ACI, Cisco SD-WAN, and NSO)
- 3.3 Describe the capabilities of Cisco compute management platforms and APIs (UCS Manager, UCS Director, and Intersight)
- 3.4 Describe the capabilities of Cisco collaboration platforms and APIs (Webex Teams, Webex devices, Cisco Unified Communication Manager including AXL and UDS interfaces, and Finesse)
- 3.5 Describe the capabilities of Cisco security platforms and APIs (Firepower, Umbrella, AMP, ISE, and ThreatGrid)
- 3.6 Describe the device level APIs and dynamic interfaces for IOS XE and NX-OS
- 3.7 Identify the appropriate DevNet resource for a given scenario (Sandbox, Code Exchange, support, forums, Learning Labs, and API documentation)
- 3.8 Apply concepts of model driven programmability (YANG, RESTCONF, and NETCONF) in a Cisco environment
- 3.9 Construct code to perform a specific operation based on a set of requirements and given API reference documentation such as these:
    - 3.9.a Obtain a list of network devices by using Meraki, Cisco DNA Center, ACI, Cisco SD-WAN, or NSO
    - 3.9.b Manage spaces, participants, and messages in Webex Teams
    - 3.9.c Obtain a list of clients / hosts seen on a network using Meraki or Cisco DNA Center

## 4.0 Application Deployment and Security (15%)
- 4.1 Describe benefits of edge computing
- 4.2 Identify attributes of different application deployment models (private cloud, public cloud, hybrid cloud, and edge)
- 4.3 Identify the attributes of these application deployment types
    - 4.3.a Virtual machines
    - 4.3.b Bare metal
    - 4.3.c Containers
- 4.4 Describe components for a CI/CD pipeline in application deployments
- 4.5 Construct a Python unit test
- 4.6 Interpret contents of a Dockerfile
- 4.7 Utilize Docker images in local developer environment
- 4.8 Identify application security issues related to secret protection, encryption (storage and transport), and data handling
- 4.9 Explain how firewall, DNS, load balancers, and reverse proxy in application deployment
- 4.10 Describe top OWASP threats (such as XSS, SQL injections, and CSRF)
- 4.11 Utilize Bash commands (file management, directory navigation, and environmental variables)
- 4.12 Identify the principles of DevOps practices

- [Where is the edge in edge computing?](https://blogs.cisco.com/internet-of-things/where-is-the-edge-in-edge-computing)
- [What Is Edge Computing?](https://www.cisco.com/c/en/us/solutions/computing/what-is-edge-computing.html#~revenue-opportunities)
- [【5G IN Computex】邊緣運算為什麼會是 5G 最重要的命題之一？](https://www.inside.com.tw/article/16526-5g-in-computex-edge-computing)
- [AWS Private 5G](https://aws.amazon.com/private5g/?nc1=h_ls)
- [AWS Edge computing](https://aws.amazon.com/tw/edge/)
- [微軟推Azure Edge Zones部署5G邊緣運算](https://www.ithome.com.tw/news/136729)
- [What is a CI/CD pipeline?](https://www.redhat.com/en/topics/devops/what-cicd-pipeline)
- [Understanding DevOps](https://www.redhat.com/en/topics/devops)
- [Bash Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
- [學習 Shell Scripts](https://linux.vbird.org/linux_basic/centos7/0340bashshell-scripts.php)
- [The NIST Definition of Cloud Computing](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-145.pdf)
- [Cisco IOx in Cisco Live 2014: Showcasing “fog computing” at work](https://blogs.cisco.com/digital/cisco-iox-in-cisco-live-2014-showcasing-fog-computing-at-work)
- [Cloud Computing](https://www.atlassian.com/microservices/cloud-computing)
- [Continuous delivery](https://www.atlassian.com/continuous-delivery/principles)
- [DevOps](https://www.atlassian.com/devops)
- [OWASP Top Ten](https://owasp.org/www-project-top-ten/)
- [GitLab CI/CD](https://docs.gitlab.com/ee/ci/)
- [Jenkins Pipeline](https://www.jenkins.io/doc/book/pipeline/)
- [pytest](https://docs.pytest.org/en/7.1.x/)
- [Python unittest built-in module](https://docs.python.org/3/library/unittest.html)

## 5.0 Infrastructure and Automation (20%)
- 5.1 Describe the value of model driven programmability for infrastructure automation
- 5.2 Compare controller-level to device-level management
- 5.3 Describe the use and roles of network simulation and test tools (such as VIRL and pyATS)
- 5.4 Describe the components and benefits of CI/CD pipeline in infrastructure automation
- 5.5 Describe principles of infrastructure as code
- 5.6 Describe the capabilities of automation tools such as Ansible, Puppet, Chef, and Cisco NSO
- 5.7 Identify the workflow being automated by a Python script that uses Cisco APIs including ACI, Meraki, Cisco DNA Center, or RESTCONF
- 5.8 Identify the workflow being automated by an Ansible playbook (management packages, user management related to services, basic service configuration, and start/stop)
- 5.9 Identify the workflow being automated by a bash script (such as file management, app install, user management, directory navigation)
- 5.10 Interpret the results of a RESTCONF or NETCONF query
- 5.11 Interpret basic YANG models
- 5.12 Interpret a unified diff
- 5.13 Describe the principles and benefits of a code review process
- 5.14 Interpret sequence diagram that includes API calls

- [Cisco Modeling Labs](https://www.cisco.com/c/en/us/products/cloud-systems-management/modeling-labs/index.html)
- [pyATS](https://developer.cisco.com/docs/pyats/)
- [Detailed Description of Unified Format](https://www.gnu.org/software/diffutils/manual/html_node/Detailed-Unified.html)

## 6.0 Network Fundamentals (15%)
- 6.1 Describe the purpose and usage of MAC addresses and VLANs
- 6.2 Describe the purpose and usage of IP addresses, routes, subnet mask / prefix, and gateways
- 6.3 Describe the function of common networking components (such as switches, routers, firewalls, and load balancers)
- 6.4 Interpret a basic network topology diagram with elements such as switches, routers, firewalls, load balancers, and port values
- 6.5 Describe the function of management, data, and control planes in a network device
- 6.6 Describe the functionality of these IP Services: DHCP, DNS, NAT, SNMP, NTP
- 6.7 Recognize common protocol port values (such as, SSH, Telnet, HTTP, HTTPS, and NETCONF)
- 6.8 Identify cause of application connectivity issues (NAT problem, Transport Port blocked, proxy, and VPN)
- 6.9 Explain the impacts of network constraints on applications