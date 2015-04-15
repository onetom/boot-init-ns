"Hi" is printed with rc13:

```
onetom@retinatom ~/p/boot-init-ns> boot2-rc13 --version
#https://github.com/boot-clj/boot
#Wed Apr 15 23:09:55 HKT 2015
BOOT_CLOJURE_VERSION=1.6.0
BOOT_VERSION=2.0.0-rc14

onetom@retinatom ~/p/boot-init-ns> boot2-rc13 repl --init-ns test
Retrieving tools.nrepl-0.2.5.jar from http://repo1.maven.org/maven2/
Retrieving tools.nrepl-0.2.8.jar from https://repo1.maven.org/maven2/
nREPL server started on port 59852 on host 127.0.0.1 - nrepl://127.0.0.1:59852
"Hi"
REPL-y 0.3.5, nREPL 0.2.8
Clojure 1.6.0
Java HotSpot(TM) 64-Bit Server VM 1.8.0_25-b17
        Exit: Control+D or (exit) or (quit)
    Commands: (user/help)
        Docs: (doc function-name-here)
              (find-doc "part-of-name-here")
Find by Name: (find-name "part-of-name-here")
      Source: (source function-name-here)
     Javadoc: (javadoc java-object-or-class-here)
    Examples from clojuredocs.org: [clojuredocs or cdoc]
              (user/clojuredocs name-here)
              (user/clojuredocs "ns-here" "name-here")
test=> Bye for now!
```

Nothing printed with rc14:

```
onetom@retinatom ~/p/boot-init-ns> boot2-rc14 --version
#https://github.com/boot-clj/boot
#Wed Apr 15 23:10:15 HKT 2015
BOOT_CLOJURE_VERSION=1.6.0
BOOT_VERSION=2.0.0-pre28
#App version: 2.0.0-rc14

onetom@retinatom ~/p/boot-init-fn> boot2 repl --init-ns test
nREPL server listening: 0.0.0.0:59844
REPL-y 0.3.4, nREPL 0.2.4
Clojure 1.6.0
Java HotSpot(TM) 64-Bit Server VM 1.8.0_25-b17
        Exit: Control+D or (exit) or (quit)
    Commands: (user/help)
        Docs: (doc function-name-here)
              (find-doc "part-of-name-here")
Find by Name: (find-name "part-of-name-here")
      Source: (source function-name-here)
     Javadoc: (javadoc java-object-or-class-here)
    Examples from clojuredocs.org: [clojuredocs or cdoc]
              (user/clojuredocs name-here)
              (user/clojuredocs "ns-here" "name-here")
user=> Bye for now!
```
