# helloworld-module


# Tutorial
[Java 9+ modularity: How to design packages and create modules, Part 1](https://developer.ibm.com/tutorials/java-modularity-3/)

Compilar
```#bash
javac -d mods/production/eg.com.taman.hello eg.com.taman.hello/src/module-info.java eg.com.taman.hello/src/eg/com/taman/hello/HelloWorldApp.java
```

Executar

```#bash
java --module-path mods/production -m eg.com.taman.hello/eg.com.taman.hello.HelloWorldApp
```
ou

```#bash
java -p mods/production -m eg.com.taman.hello/eg.com.taman.hello.HelloWorldApp
```

Exibir árvore de módulos
```#bash
tree
```



Em caso de compilação padrão pela IDE(código gerado na pasta out)
```#bash
java --module-path out/production -m eg.com.taman.hello/eg.com.taman.hello.HelloWorldApp
```

ou

```#bash
java -p out/production -m eg.com.taman.hello/eg.com.taman.hello.HelloWorldApp
```




