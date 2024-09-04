# Conky
### Date, Local IP and Temperature

This script shows a minimalist frame that contain a date field, the local ip address and the cpu temperature. The font myConkySymbols provided must be installed first. 

![date,ip,temp](img/date_ip_temperature_01.png "date, ip and temperature")

### To-Do: 
For use the **todo.conf**, a file named **~/dotfiles/conky/todo.md** must be created with the following structure.

* one or more joined characters from the myConkySymbols font
* a space  separation followed by one or more words. This sentence will be split by '**;**'. if there are no '**;**' the  font weight of the sentence will be normal, if there are one or two '**;**' the first part will be bold, the second normal and if a third part is formed it will display as characters of myConkySymbols again.

Este script esta limitado a 10 items.

**E.g:**

```
v Math: Study equations
u Workout: 3 series of push-ups 
u Walk 
```

![Todo example](img/todo_and_description_from_file_02.png  "Todo example")

### hour_temp_minimalist:  
This script shows a minimalist clock and temperature monitor.  The temperature indicator color is white if the temperature is lower than 46º, the color change to orange if the temperature is between 46º and 55º, and change to red if it is greater than 55º.

![Hour temperature example](img/hour_temperature_01.png "Hour and temperature example")
