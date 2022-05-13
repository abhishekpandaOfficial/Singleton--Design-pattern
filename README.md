# Singleton--Design-pattern
Singleton Design pattern using C#.NET , Implementations, Explanations and Notes

// SINGLETON DESIGN PATTERNS
  ------------------------------ Creational Design patterns
      
  Defn : When we ensure that only One instance of a Particular class is going to be created and then provide Global access to that instance for that entire application. 

      OR
              
Defn : A Class Object is having only One instance and able to Perform all tasks .

                                   ----- RULES -----
1. A Single Constructor should be Private and parameterless --> (bcz It is not allowed theclass to be instantiated from outside the class 
                    but only within the class .
2. Class should be Sealed ==> Means it cant be inherited further .

3. Create Private Static Variable ==> Which will hold the reference of instance of class 

4. Create Public static property / Method == > which will return he single-created instance of the singleton class .
 This method or property first check if an instance of the singleton class is available or not. 
            If the singleton instance is available, then it returns that singleton instance otherwise 
            it will create an instance and then return that instance.

