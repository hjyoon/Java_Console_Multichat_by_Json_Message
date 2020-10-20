# Java_Console_Multichat_by_Json_Message

multithreaded chat in console

## Environment
- OpenJDK 11
- Gson 2.8.6

## Build

### Linux
`javac --module-path mlib -d mods --module-source-path src $(find src -name "*.java")`

### Windows
`javac --module-path mlib -d mods --module-source-path src --module me.hjyoon.multichat`

## Execute
`java -p mlib;mods -m me.hjyoon.multichat/me.hjyoon.multichat.Main`