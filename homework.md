/**
 * We declare a package-level function main which returns Unit and takes
 * an Array of strings as a parameter. Note that semicolons are optional.
 */

fun main(args: Array<String>) {
      
     var isRainy = true
 if(isRainy)    
    println("Нужен зонт") 
    else 
    println("Зонт не нужен")
    
 isRainy=false
 
val text = if (isRainy) 
    "Нужен зонт" 
    else 
    "Зонт не нужен"
    println(text)
    
 var dayNumber = 4

 val dayName = when (dayNumber) {
    1 -> "Понедельник"
    2 -> "Вторник"
    3 -> "Среда"
    4 -> "Четверг"
    5 -> "Пятница"
    6 -> "Суббота"
    7 -> "Воскресенье"
    else -> "Несуществующий день"
}

    println(dayName)
    if (dayName == "Четверг") 
    isRainy = true
    println (isRainy)
    
 dayNumber+=1
 
val isRainbowVisible = if((dayNumber-1)==4) true else false
if(isRainbowVisible) println ("Радуга") else println ("=(")
    
    
}
