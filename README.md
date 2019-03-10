# SQL-Inverse-Multiplexer
The project is proposed by a company called iCognition.

The objective of this project is to improve the functionality of an existing software (Content Manager, developed by MicroFocus), to allow the collation of results from multiple database instances, and return them through a single query within the CM software.

## Project Members
| Name            | E-mail                      | Role(s)                               |
| ---------------:|:---------------------------:| -------------------------------------:|
| Donghoon Chang  | u5342047@anu.edu.au         | Tester                                |
| Willy Ghozali   | u6272951@anu.edu.au         | Middleware Developer, Researcher      |
| Rahil Vora      | Rahil.Vora@anu.edu.au       | Researcher                            |
| Scarlet Qin     | Sijia.Qin@anu.edu.au        | Middleware Developer                  |
| Siddarth Thakur | Siddharth.Thakur@anu.edu.au | Middleware Developer, Project Manager |
| Melissa Turner  | u6350995@anu.edu.au         | Tester                                |
| Daniel Turner   | u5562347@anu.edu.au         | Tester                                |

## Key Stakeholders
*   The Australian National University: a national research university located in Canberra, the capital of Australia.
*   iCognition: a techniqual company helping clients to maximise the value of their information assets, while minimising cost and risk.

## Solutions
We are required to develop software that intercepts calls from the Content Manager application and distribute those calls to all related databases.

To address this issue, multiple potential solutions have been made:
*   Developing a MiddleWare that interacts with both the CM and database server
*   DLL Injection
*   Designing an intermediate database that holds other related databases
*   SQL Proxy

It is important to note that the possibilities of these solutions are not definite.

## Project Impact
Rather than rely on the applications to implement this functionality, we are improving the software which can intercept calls to the database from the application and distribute those calls to several databases, collate the results and returns those results to the application. The software would be transparent to the application and would not require any changes to the application’s existing SQL.

## Resources
*   Content Manager SDK: <https://github.com/content-manager-sdk/Community>
*   TDS Bridge: <https://github.com/MindFlavor/TDSBridge>
