# comsumeApi
Demostrate how to consume REST and SOAP API

SOAP branch demostrates consuming of SOAP API

Includes WSDL file, copy the WSDL xml file from 
https://www.dataaccess.com/webservicesserver/numberconversion.wso?WSDL

The WSDL file defines the operations.

Code Generation:

1. add Maven POM file for Jaxb Maven Plugins and pointing to the wsdl file.
2. Click on Excute Maven Goal, and generate sources
3. Check the generated file under target/generated-sources/xjc