# oswe-learning-plan


### Vulns to study

- Deserialization 
    - Java
      - https://www.youtube.com/watch?v=VviY3O-euVQ
      - https://i.blackhat.com/eu-19/Thursday/eu-19-Zhang-New-Exploit-Technique-In-Java-Deserialization-Attack.pdf
      - https://owasp.org/www-community/vulnerabilities/Deserialization_of_untrusted_data
      - https://foxglovesecurity.com/2015/11/06/what-do-weblogic-websphere-jboss-jenkins-opennms-and-your-application-have-in-common-this-vulnerability/
      - [Deserialization-cheatsheet](https://github.com/GrrrDog/Java-Deserialization-Cheat-Sheet/blob/master/README.md)
      - https://www.youtube.com/watch?v=oZPZLiY2PeA
      - https://securitylab.github.com/research/in-memory-data-grid-vulnerabilities
    - NODEJS
        - https://www.exploit-db.com/docs/english/41289-exploiting-node.js-deserialization-bug-for-remote-code-execution.pdf
        - https://blog.websecurify.com/2017/02/hacking-node-serialize.html
        - https://www.youtube.com/watch?v=t-zVC-CxYjw
        - [nodejs deserialization cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Nodejs_Security_Cheat_Sheet.html)
    - C#
        - https://www.youtube.com/watch?v=eDfGpu3iE4Q
        - https://www.youtube.com/watch?v=Xfbu-pQ1tIc
     - PHP
        - https://vkili.github.io/blog/insecure%20deserialization/pop-chains/
- php Type Juggling
- Advanced SQLi techniques

## Playground
- [CTF.LIVE](https://www.ctf.live/)
- [Hackthebox](https://www.hackthebox.eu/)

### Skill

- Source Code Review 
    - [OWASP Secure Code Review Guide](https://owasp.org/www-pdf-archive/OWASP_Code_Review_Guide_v2.pdf)
    - https://medium.com/swlh/secure-code-review-and-penetration-testing-of-node-js-and-javascript-apps-41485b1a9518
- Exploit development automation in prefered language
- dynamic analysis of web application


### HTB Boxes

- [Archam](https://www.youtube.com/watch?v=krC5j1Ab44I)		: Java Deserialization 
- [Falafel](https://www.youtube.com/watch?v=CUbWpteTfio&t=1 )		: PHP Type Juggling 
- [Zipper](https://www.youtube.com/watch?v=RLvFwiDK_F8&t=75)		: API to RCE ( )
- [HackBack](https://www.youtube.com/watch?v=B9nozi1PrhY&t=1)	    : API to RCE
- [Holiday](https://www.youtube.com/watch?v=FvHyt7KrsPE&t=1)			: NodeJS Command Injection
- [Fighter](https://www.youtube.com/watch?v=CW4mI5BkP9E&t=55)			: Boolean SQLi to RCE
- [Writeup](https://www.youtube.com/watch?v=GKq4cwBfH24&t=64)			: Time Base SQLI to RCE
- [Unattended](https://www.youtube.com/watch?v=2SATzCQY0Zw&t=60)		: Time Base SQLI to RCE
- [Help](https://www.youtube.com/watch?v=XB8CbhfOczU&t=49)			    : Time Base SQLI to RCE /File upload
- [Ghoul](https://www.youtube.com/watch?v=kE36IGAU5rg&t=89)	  		    : File upload


### Other labs

- [JavaDeserH2HC](https://github.com/joaomatosf/JavaDeserH2HC)
- [NodeGoat](https://github.com/OWASP/NodeGoat)
- [DSerlab](https://github.com/NickstaDB/DeserLab)
- [SQLi to Shell](https://pentesterlab.com/exercises/from_sqli_to_shell/course)
- [XSS to RCE](https://pentesterlab.com/exercises/xss_and_mysql_file/course)
- [pipe](https://www.vulnhub.com/entry/devrandom-pipe,124/)
- [XVNA](https://github.com/vegabird/xvna)
    

### Tools
- ysoserial
  - Jar : https://github.com/frohoff/ysoserial
  - .NET : https://github.com/pwntester/ysoserial.net
  - about payload : http://gursevkalra.blogspot.com/2016/01/ysoserial-commonscollections1-exploit.html
  - burp plugin : https://github.com/summitt/burp-ysoserial
- [GadgetProbe](https://portswigger.net/daily-swig/gadgetprobe-new-tool-simplifies-the-exploitation-of-java-deserialization-vulnerabilities)
- [NodeJSscan](https://github.com/ajinabraham/NodeJsScan)
- [Frida-node](https://github.com/frida/frida-node)

### Books
- [You don't know JS](https://github.com/getify/You-Dont-Know-JS)


### other refs
https://github.com/wetw0rk/AWAE-PREP

https://medium.com/swlh/secure-code-review-and-penetration-testing-of-node-js-and-javascript-apps-41485b1a9518

https://forum.hackthebox.eu/discussion/2646/oswe-exam-review-2020-notes-gifts-inside
https://github.com/lirantal/awesome-nodejs-security

