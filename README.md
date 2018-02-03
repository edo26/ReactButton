# ReactButton
Android Library By Java to Create ReactButton with 6 Emoji Face 

Description :
    
Default Case :

           Text = Like 
           Emoji is black Hand
           If User Click on Button it Text Will still like but emoji will be blue hand
           and if user click long on button it will show dialog to choose one emoji from 6 emojis

How To Initializing ReactButton :

```java
ReactButton reactButton = findViewById(R.id.buttonId);
```

To Get Current Emoji On Button :

```java
String currentEmoji = reactButton.getCurrentEmojiType();

switch(currentEmoji)
{
   case "Like":
       //Text Is Like , Emoji Is Blue Hand
       break;
       
   case "Love":
       //Text Is Like , Emoji Is Red Heart
       break;
       
   case "Smile":
        //Text Is Smile , Emoji Is Smile Hand
       break;
       
   case "Wow":
       //Text Is Wow , Emoji Is Wow Face
       break;
       
   case "Sad":
       //Text Is Sad , Emoji Is Dark Hand
       break;
       
   case "Angry":
       //Text Is Angry , Emoji Is Angry Face
       break; 
       
   default:
       //Text Is Like , Emoji Is Dark Hand
       break;
}
```






