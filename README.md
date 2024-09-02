# splitwise-algo
I have created a method which just do it.
"findPath(parm)"

Create a HashMap Variable
"static HashMap parm = new HashMap()"

Add the Expense in below formate

      "parm.put("Name", Amoun)"

For Example,

    parm.put("A", -5.0);  
    parm.put("B", 25.0);  
    parm.put("C", -20.0);  
    parm.put("D", 25.0);  
    parm.put("E", -20.0);  
    parm.put("F", -5.0);  
Passing values to find the Net Amount to be Paid with Person Name -Cash Flow / Shortest Path

  findPath(parm);  
Out Put
C needs to pay B:20.0
E needs to pay D:20.0
A needs to pay B:5.0
F needs to pay D:5.0
