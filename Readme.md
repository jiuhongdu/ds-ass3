//if you want to use them please tell me via email: 2261928980@qq.com

//Do not use them for your assignment/exam/practial/homework

//Run the test

//finished by Jiuhong Du

## compile：

    Go to the project root directory(PaxosImpl)
### Compiling in Terminal（Use the following command）：
    
    javac -classpath ./src -d ./build ./src/paxos/bean/* ./src/paxos/doer/* ./src/paxos/main/Main.java  ./src/paxos/util/*

## Run the program：

### All members have immediate respsonses to voting queries

```
java -Dfile.encoding=UTF-8 -cp build/ paxos.main.Main immediate
```

### M2，M3 may delay and go offline 

```
java -Dfile.encoding=UTF-8 -cp build/ paxos.main.Main
```
