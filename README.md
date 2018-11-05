Virtual Machine Used : Cloudera-Training-VM-4.2.1.p-vmware_CAPStudent.part01

Files and Directories Used in this Exercise -

Eclipse project: writables

Java files:
StringPairWritable–implements a WritableComparable type
StringPairMapper –Mapper for test 
jobStringPairTestDriver –Driver for test job

Java File Location - src/stubs

Data file: ~/training_materials/developer/data/nameyeartestdata (small set of data for the test job)

Exercise directory: ~/workspace/writables

Compiling - The compilation was done in Eclipse by converting the entire file into a jar file.
Running - hadoop jar writ.jar stubs.StringPairTestDriver /user/training/ny1 part100
hadoop fs -cat part100/part-r-00000

