# Nuclei Template

I have finally decided to contribute something to the IT Security field, and what a better way to do it than starting by creating templates for Nuclei (nuclei.projectdiscovery.io)

#### Templates
 - **CVE-2021-44848**: Thinfinity VirtualUI is a web remote desktop system, a vulnerability exist in the parameter "username" located in /changePassword that allows user enumeration, depending of the configuration of VirtualUI, the users enumerated may be part of Operating System.
  The HTTP response returns different responses depending on whether the username exists. Usernames must be brute-forced.
  Reference: https://www.tenable.com/cve/CVE-2021-44848
  
 - **CVE-2021-45092**: Thinfinity VirtualUI is a web remote desktop system, a vulnerability exist in a function located in /lab.html reachable by default that could allow IFRAME injection via the "vpath" parameter.
  Reference: https://www.tenable.com/cve/CVE-2021-45092
