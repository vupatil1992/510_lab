# 510_lab
[ UML Design of classes ]

Client
  
+readData()
+processData()
+printData()


BankRecords


robjs[] : new BankRecords[600]
array: ArrayList<List<String>> 

-id:string
-age:int
-sex:String
-region:String
-income:double
-married:String
-children:int
-car:String
-save_act:String
-current_act:String
-mortgage:String
-pep:String

+getId():String
+getAge():Int
::
+setId(id:String)
+setAge(age:int)
::

+readData()
+processData()
+printData()
