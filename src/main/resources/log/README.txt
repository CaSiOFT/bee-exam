Run class:
org.teasoft.exam.bee.test.TestCache.java
org.teasoft.exam.bee.test.TestNormal.java

First Reference Version Result:
bee-exam(v1.7.2)-cache-2020-03-04 10.53.46.681.txt
bee-exam(v1.7.2)-normal-2020-03-04 10.52.58.70.txt

test SuidRich add two new methods:
public <T> int updateBy(T entity,String whereFieldList,Condition condition);
public <T> int update(T entity,String updateFieldList,Condition condition);
bee-exam(v1.7.2)-normal-2020-04-22 16.10.41.797.txt
bee-exam(v1.7.2)-cache-2020-04-22 16.16.31.829.txt

test use nocache:
bee-exam(v1.7.2)-cache-2020-04-22 16.33.07.919.txt

test use setAdd,setMultiply in Condition:
bee-exam(v1.7.2)-normal-2020-04-22 22.00.11.844.txt

PearFlowerIdTest,SerialUniqueIdTest
test for global unique id number in distributed environment.