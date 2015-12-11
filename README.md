# Abendigo-Offset-Scanner
_Java Based CSGO Offset Scanner_

This library is licensed under LGPL 3.0 and was created for use in my game modding platform called Abendigo which you
 can see here: [https://github.com/Jire/Abendigo](https://github.com/Jire/Abendigo)  or you can visit our community here: https://abendigo.org
---

This project is a utility for my CSGO cheat Abendigo. This utility is used to scan the memory using byte-patterns to find the relative memory addresses for our cheat.

### Dependencies

We use some really cool technology to drive Abendigo. Here's a list:

- [Java Native Access (JNA)](https://github.com/java-native-access/jna) as the backbone for interfacing with native libraries

### Plans

As of right now the project is currently not complete. The following are features I plan on adding:
 - Documentation
 - NetVars: Even though the NetVar addresses rarely change, still would be a nice feature
 - txt, xml, JSON: expect the ability to `dump` the offsets to a file format of your choice.