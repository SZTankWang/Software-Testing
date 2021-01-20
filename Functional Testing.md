#### Functional Testing

+ specification-based or black-box testing
+ Some test cases are better than others, some reveals faults and others do not.



##### partition testing 

A testing method that divides the infinite set of possible test cases into a finite set of classes, with the purpose of drawing one or more test cases from each classes.

**When partitions are chosen according to information in specification rather than the design or implementation, it is called ** **specification-cased testing**, or <u>functional testing</u>.



Partitioning by any means, is always based on experience and judgment that leads one to believe that certain classes of test cases are "more alike" than others.



##### Identify independently testable features

Systems -> distinct features, such as searching/ registering/ ...

Independently testable features are described by identifying all the inputs that form their execution environments.

Trying to identify inputs may help in distinguishing different functions.



##### Identify Representative Classes of Values or Derive a Model

+ identified directly from informal specifications expressed in natural language
+ selected indirectly through a model

Most methods that can be applied to informal specifications rely on explicit enumeration of representative values by the test designer.

+ identify different categories of expected values
+ boundary
+ exceptional/ erroneous values.



##### generate test case specifications

If representative values were explicitly enumerated in the  previous step, thenss test case specifications will be elements of the Cartesian product of values elected for each input. **Brute force enumeration is not satisfactory**.

Selection of a practical subset of legal combination can be done by adding information that reflects the hazard of the different combinations as perceived by the test designer or by following combinatorial considerations. 

##### generate test vases and instantiate tests

