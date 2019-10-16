# tut4
 Remove log  Raw log 

0.17s
0.00s
0.08s
1
0.18s
0.01s
0.00s
0.00s
system_info
56
Build system information
156
157
0.03s
0.00s
0.01s
0.44s
0.00s
0.00s
0.00s
0.01s
0.01s
0.12s
0.00s
0.96s
0.00s
0.00s
0.07s
0.00s
2.82s
0.00s
2.30s
docker_mtu
resolvconf
git.checkout
158
0.50s
$ git clone --depth=50 --branch=master https://github.com/QinSu-a/tut4.git QinSu-a/tut4
168
169
0.01s
$ java -Xmx32m -version
170
openjdk version "11.0.2" 2019-01-15
171
OpenJDK Runtime Environment 18.9 (build 11.0.2+9)
172
OpenJDK 64-Bit Server VM 18.9 (build 11.0.2+9, mixed mode)
173
$ javac -J-Xmx32m -version
174
javac 11.0.2
install
175
12.85s
$ mvn install -DskipTests=true -Dmaven.javadoc.skip=true -B -V
754
5.97s
$ mvn clean test
755
[INFO] Scanning for projects...
756
[INFO] 
757
[INFO] -------------------------< com.test:AddandSub >-------------------------
758
[INFO] Building AddandSub 0.0.1-SNAPSHOT
759
[INFO] --------------------------------[ jar ]---------------------------------
760
Downloading from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/plugins/maven-clean-plugin/2.5/maven-clean-plugin-2.5.pom
761
Downloaded from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/plugins/maven-clean-plugin/2.5/maven-clean-plugin-2.5.pom (3.9 kB at 12 kB/s)
762
Downloading from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/plugins/maven-clean-plugin/2.5/maven-clean-plugin-2.5.jar
763
Downloaded from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/plugins/maven-clean-plugin/2.5/maven-clean-plugin-2.5.jar (25 kB at 483 kB/s)
764
[INFO] 
765
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ AddandSub ---
766
[INFO] Deleting /home/travis/build/QinSu-a/tut4/target
767
[INFO] 
768
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ AddandSub ---
769
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
770
[INFO] skip non existing resourceDirectory /home/travis/build/QinSu-a/tut4/src/main/resources
771
[INFO] 
772
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ AddandSub ---
773
[INFO] Changes detected - recompiling the module!
774
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
775
[INFO] Compiling 1 source file to /home/travis/build/QinSu-a/tut4/target/classes
776
[INFO] 
777
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ AddandSub ---
778
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
779
[INFO] skip non existing resourceDirectory /home/travis/build/QinSu-a/tut4/src/test/resources
780
[INFO] 
781
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ AddandSub ---
782
[INFO] Changes detected - recompiling the module!
783
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
784
[INFO] Compiling 1 source file to /home/travis/build/QinSu-a/tut4/target/test-classes
785
[INFO] 
786
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ AddandSub ---
787
[INFO] Surefire report directory: /home/travis/build/QinSu-a/tut4/target/surefire-reports
788
Downloading from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/surefire/surefire-junit4/2.12.4/surefire-junit4-2.12.4.pom
789
Downloaded from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/surefire/surefire-junit4/2.12.4/surefire-junit4-2.12.4.pom (2.4 kB at 93 kB/s)
790
Downloading from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/surefire/surefire-providers/2.12.4/surefire-providers-2.12.4.pom
791
Downloaded from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/surefire/surefire-providers/2.12.4/surefire-providers-2.12.4.pom (2.3 kB at 42 kB/s)
792
Downloading from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/surefire/surefire-junit4/2.12.4/surefire-junit4-2.12.4.jar
793
Downloaded from google-maven-central: https://maven-central.storage-download.googleapis.com/repos/central/data/org/apache/maven/surefire/surefire-junit4/2.12.4/surefire-junit4-2.12.4.jar (37 kB at 998 kB/s)
794
795
-------------------------------------------------------
796
 T E S T S
797
-------------------------------------------------------
798
799
Results :
800
801
Tests run: 0, Failures: 0, Errors: 0, Skipped: 0
802
803
[INFO] ------------------------------------------------------------------------
804
[INFO] BUILD SUCCESS
805
[INFO] ------------------------------------------------------------------------
806
[INFO] Total time:  4.064 s
807
[INFO] Finished at: 2019-10-16T09:31:09Z
808
[INFO] ------------------------------------------------------------------------
809
The command "mvn clean test" exited with 0.
810
811
812
Done. Your build exited with 0.
