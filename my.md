# my

English papers
nyu.edu

ArrayDeclarationListener.java 保存HashMap<String, Symbol> symbolMap;
lingCodeGenListener.java 代码生成，构造函数需要HashMap<String, Symbol> symbolMap;
lingSyntaxCheckListener.java 类型检查

```shell
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Starting frontendtest.Test with p4test5
~~~~~~~~~~~~~~~~~~~~~~~~~~~

-----Starting scanner and parser checking----
-----Finished scanner and parser checking----
-----Starting syntax checking-----
SUCCESS ! The global var:tp, type:TUPLE,2 on line 3 has been declared
SUCCESS ! The global var:a, type:INT_LIT on line 13 has been declared
SUCCESS ! The global var:b, type:INT_LIT on line 14 has been declared
SUCCESS ! The global var:bb, type:TUPLE,2 on line 21 has been declared
SUCCESS ! The global var:xx, type:TUPLE,2 on line 22 has been declared

<---Entering a function---->
SUCCESS! var:x has been add as a local var in function on line 24
Return Type Infered! The return type is INT_LIT for func:sss on line 27
<--------------Symbol Table size:2---------------->
cc : TUPLE,2
x : UNDEFINED
<----------------Table__End--------------------->
```

```
Token (scanner)
    Word (scanner)
        KeyWord (scanner)
        Identifier (scanner)
    GreedyOperator (scanner)
    NonGreedyOperator (scanner)
    Number (scanner)
```
