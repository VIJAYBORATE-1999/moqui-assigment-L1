# Steps I followed 
1)Installed  java 11

<img src="Assignment_Images/JavaVersion.jpg">

2)Set java home varible in Bash rc file of linux 
- ls /usr/lib/jvm/
- nano ~/.bashrc
- export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
- export PATH=$PATH:$JAVA_HOME/bin
- source ~/.bashrc
- echo $JAVA_HOME
- echo $PATH
  
<img src="Assignment_Images/IMage2.jpg">

3) Project Run and Deploy
- Clone the Git hub repo : git clone url  
  https://github.com/moqui/moqui-framework
- Go to terminal and run these commands : 
 ./gradlew getComponent -Pcomponent=HiveMind
 ./gradlew build
 ./gradlew load
 ./gradlew addRuntime
 ./gradlew load run 
- Acess aplication at 
  http://localhost:8080/

4) Assignment Steps :
- go to component folder and run commands  :

  mkdir helloworld-component
  cd helloworld-component/
  touch component.xml
  mkdir entity service screen
  cd entity/
  touch ExampleEntity.xml
`HI`
 
