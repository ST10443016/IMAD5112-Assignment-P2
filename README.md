
## Spiffo's Tamagotchi App

I have designed and created an app that allows users to interact with a virtual pet called Spiffo. The app includes various activities to engage with Spiffo, such as feeding, playing with, and washing Spiffo to keep him happy and healthy. 

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(page1userinterface)
The user interface on page one consists of one button to proceed to page two, along with a text view and image view to display Spiffo welcoming you.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(page2userinterface)
The user interface on page two consists of three buttons for feeding, playing and washing, along with a status text view and an image view to display Spiffo's current state.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(mainactivitycode)
This code facilitates basic navigation from MainActivity to MainActivity2. I achieve this by making use of "import android.content.Intent" which is used to navigate between different components of an Android application and setting a click listener on the button.

"val intent = Intent(this, MainActivity2::class.java)" Creates an intent to navigate to MainActivity2. The Intent constructor takes two parameters; the context (this) and the target activity class (MainActivity2::class.java) and the "startActivity(intent)" starts the MainActivity2 using the intent, initiating the navigation to the next screen.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(mainactivity2codepart1)
The hunger, happiness, and cleanliness are integer variables representing the Spiffo's attributes. They are initialized with a value of 10 and spiffoimage is an ImageView variable that will hold a reference to the image view displaying Spiffo.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(mainactivity2codepart2)
Click listeners are set for the feed, play, and wash buttons. Each listener invokes a corresponding function "feed(), play(), wash()", updates the status text view, and updates the Spiffo's image.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(mainactivity2codepart3)
Private Helper Functions:"feed(), play(), and wash()" modify Spiffo's attributes and image based on the corresponding action while "updateStatus()" updates the status text view with the current values of hunger, happiness, and cleanliness.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(appsecondpagedefault)
This is the default second page before feed, play and watch are clicked 

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(appsecondpagedeeating)
This is after clicking on the "Eat" button. The hunger has increased (The larger the number the better, the lower the number the worse) while the other attributes have decreased and the picture has updated according to the eat button.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(appsecondpageplaying)
After clicking on the "Play" button. The happiness has increased while the other attributes have decreased and the picture has updated to Spiffo playing.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)(appsecondpagewashing)
After clicking on the "Wash" button. The cleanliness has increased while the other attributes have decreased and the picture has updated to Spiffo washing.
## Conclusion

This code creates a Tamagotchi-like application where users can interact with buttons to feed, play with, and wash Spiffo. Spiffo's attributes (hunger, happiness, cleanliness) are updated based on these actions, and the UI is updated accordingly with the status displayed in a TextView and Spiffo's image changing dynamically.
## Referencing

The IIE. 2024. Introduction to Programming Logic [IPRG1111 Module Manuell. The Independent Institution of Education: Unpublished.] 

Simpson, C., Hodgetts, A., Siu-Chong, M. and Cowen, N. 2011. Project Zomboid[Online Digital Game], PC, Mac and Linux. United Kingdom, and Canada: The Indie Stone.