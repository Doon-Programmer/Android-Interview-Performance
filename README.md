# Android-Interview-Performance
Here we can found latest Android interview questions and also performance tips while developing Android Application

1. How to create singleton class in Kotlin and what is singlton design pattern in programming
   
   Code question :
   val nameList = emptyList<String>()
   val ageList = emptyList<Int>()
   println(nameList===ageList)

   Explaination of singleton class and above code question in below link:    
   https://youtu.be/H_BCG0hGhaw

3. Coroutine scope code interview question
   
   import kotlinx.coroutines.*  
   fun main() = runBlocking{  
   GlobalScope.launch{  
    delay(1000)  
    println("Work1 Finish")  
   }  
   GlobalScope.launch{    
     delay(1000)  
    println("Work2 Finish")  
   }  
     println("Finished Work")  
     
  }  

  Link for above code with explaination :  
  https://youtu.be/gI9ZE5sHLVQ  

   
