# IMAD5112Assignment1
Assignment 1 of Introduction to Mobile Application Development

This app was created using Android Studio
Program language is Kotlin
Code is in .xml and .kt

GitHub repository link
https://github.com/suqdawg/IMAD5112Assignment1

YouTube video link
https://youtu.be/yeTjXjKKTG4

How To Use App?
Type time of day in the text box and recieve different meal choices based on time of day, e.g., 'morning' or 'breakfast.
You can also type in time, e.g., 09:00 but theapp will handle this as an error and prompt you to correct your input.

1. open app and iimediately add text input to the text bar
2. insert "morning or breakfast" to get the morning meal suggestions.
3. insert "lunch or afternoon" to get the lunch meal suggestions.
4. insert "dinner or evening" to get dinner meal suggestions.
5. insert "09:00 or 14:00 or 20:00 to get hints
6. insert "eggs, ham or chicken" hints to get full preparation method for the 1st meal
7. do not insert random number as the text result will be "invalid hour entered"
8. do not insert random numbers as the text result will be "invalid hour entered" error
9. any mispelled words will give you the "Couldn't recognise the time" error

Suggestions
morning
breakfast
lunch
afternoon
dinner
evening
(results in top 3 meal suggestions)

Hints
eggs
ham
chicken
(results in top most easy to prepare method)

Error Handling for Time input
0-10 = eggs
11-17 = ham
18-23 = chicken

Proper time cannot result in a meal suggestion because, hints will replace it then preparation methods take its place.

It is important to remember that the app has limited functionality and cannot switvh activity views.
It is only one activity view with a user interface and minimal user experience.

Screenshots
![Home](https://github.com/user-attachments/assets/df96f6fa-b097-48e9-9b9b-f8254d178f32) 
(Home Page) This is the home page of the app.

![type Morning](https://github.com/user-attachments/assets/df753907-4130-48f4-a401-ce930efe2a4f) 
When you type "Morning or Breakfast", this suggestion will appear, showing you 3 meal options

![type Lunch](https://github.com/user-attachments/assets/9474859f-b1d6-409f-b1aa-cee7f57644b5)
When yu type "Lunch or Afternoon", this suggestion will appear, showing you 3 luch options

![type ham](https://github.com/user-attachments/assets/bb14434d-2663-4fa6-8635-2cad7b24ee5d)
If you type Ham, you will get the full method of how to prepare your easiest lunch option

![type chicken](https://github.com/user-attachments/assets/ee4a00fe-ac47-4181-9f98-834da95d04a9)
Type Chicken and you will get the full method of how to prepare your easieast dinner option

![type wrong numbers](https://github.com/user-attachments/assets/5794a220-4187-408f-a93b-c00861258c20) 
type wrong numbers and get this hint "Invalid hour entered"

![type random let, get Couldnt recognise](https://github.com/user-attachments/assets/a05ec70d-2a53-47f6-b985-0ab5b983d2f5)
type random letters, get 'Couldn't recognise the time"

![type invalid time](https://github.com/user-attachments/assets/889598b2-4c96-4b49-8d69-728b53aea443)
type invalid time get, "Invalid hour entered"

![click reset](https://github.com/user-attachments/assets/827e0ceb-2eb9-42e6-805d-fe3496d6fe04)
Click reset notification

![click search](https://github.com/user-attachments/assets/ff931ade-3381-4d87-867a-5d6ac66f234b)
Click search notification

![gradient BckGrnd](https://github.com/user-attachments/assets/a6bd2855-1a52-49cf-84d6-b5d4079da832)
Gradient Background of the App

![type 11, get Ham hint](https://github.com/user-attachments/assets/dfafc5f5-d494-4ebd-a803-c658c762e16b)
Type 11 get Ham hint

![type 21, get Chicken hint](https://github.com/user-attachments/assets/38dd49a8-6f4a-4dc6-8999-87c77e3466ae)
type 21 get Chicken hint
