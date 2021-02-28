# Notes
* Q1 - company that makes the SIEM for your case investigationw ork
* Q2 - likely source IP of scan to imreallynotbatman.com
  
  ```
  imreallynotbatman.com src_ip="a.b.c.d"
  ```
* Q3 - company that created web vulnerability scanner used in the attack
  * reviewed HTTP headers
    ```
    [removed]-Product: WVS/10.0 ([removed] Web Vulnerability Scanner - Free Edition)
    ```
* Q4 - what CMS is imreallynotbatman.com likely using
  * reviewed uri and uri_path
* Q5 - 
* Q6 - 
* Q7 - what IP is tied to domains for the attack
  * reviewed top sources
    ```
    imreallynotbatman.com| top limit=20 src
    ```
* Q8 -
* Q9 - what IP brute forced imreallynotbatman.com
  * reviewed top sources
    ```
    imreallynotbatman.com| top limit=20 src
    ```