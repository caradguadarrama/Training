/** Challenge:

Create a function which answers the question "Are you playing banjo?".
If your name starts with the letter "R" or lower case "r", you are playing banjo!

The function takes a name as its only argument, and returns one of the following strings:

name + " plays banjo" 
name + " does not play banjo"

Names given are always valid strings.

#Strings #Fundamentals 
*/

// My Solution:
public class Banjo {
  public static String areYouPlayingBanjo(String name) {
    
    char[] myArray = name.toCharArray();
    
    if(myArray[0] == 'r'|| myArray[0] =='R'){
       return name + " plays banjo";
    } else {
      return name + " does not play banjo";
    }
  }
}
