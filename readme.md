### Run lizzieyzy in IDEA

1. Download and install IDEA
2. Download and install JDK (Currently I use JAVA SE 17 LTS)
3. Open lizzieyzy root directory as IDEA project
4. View -> Tool Windows -> Maven -> reload
5. add Maven -> Name:`package`, Run:`clean compile package -Dmaven.test.skip=true`
6. run `package`
7. navigate to target directory and java -jar `lizzie-xxx.jar`



### TODO

* Learning the basic usage of maven(run, clean) - 20220923 Done
* Be familiar with all code in the project - 20220930