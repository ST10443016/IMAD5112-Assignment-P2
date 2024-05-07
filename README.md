
## Spiffo's Tamagotchi App

I have designed and created an app that allows users to interact with a virtual pet called Spiffo. The app includes various activities to engage with Spiffo, such as feeding, playing with, and washing Spiffo to keep him happy and healthy. 

## Screenshots

![page1userinterface](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/0ac8a86a-b10e-437e-961d-6cb27d088b18)

The user interface on page one consists of one button to proceed to page two, along with a text view and image view to display Spiffo welcoming you.

![page2userinterface](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/a3c320d8-733e-4ab9-9901-75eb8645f7e4)

The user interface on page two consists of three buttons for feeding, playing and washing, along with a status text view and an image view to display Spiffo's current state.

![mainactivitycode](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/2ba5d7ff-d0bb-4d12-82e0-d52996086b95)

This code facilitates basic navigation from MainActivity to MainActivity2. I achieve this by making use of "import android.content.Intent" which is used to navigate between different components of an Android application and setting a click listener on the button.

"val intent = Intent(this, MainActivity2::class.java)" Creates an intent to navigate to MainActivity2. The Intent constructor takes two parameters; the context (this) and the target activity class (MainActivity2::class.java) and the "startActivity(intent)" starts the MainActivity2 using the intent, initiating the navigation to the next screen.

![mainactivity2codepart1](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/86c14bd0-f766-4f16-8c44-c32e0a5060ae)

The hunger, happiness, and cleanliness are integer variables representing the Spiffo's attributes. They are initialized with a value of 10 and spiffoimage is an ImageView variable that will hold a reference to the image view displaying Spiffo.

![mainactivity2codepart2](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/5b3564f8-7d98-45c7-bab9-2ae56bd3d0db)

Click listeners are set for the feed, play, and wash buttons. Each listener invokes a corresponding function "feed(), play(), wash()", updates the status text view, and updates the Spiffo's image.

![mainacivity2codepart3](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/7e7a7c82-a6ce-4e15-b1d1-92678f827df0)

Private Helper Functions:"feed(), play(), and wash()" modify Spiffo's attributes and image based on the corresponding action while "updateStatus()" updates the status text view with the current values of hunger, happiness, and cleanliness.

![appsecondpagedefault](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/64725cb6-f061-440d-81fc-1585fe0573a8)

This is the default second page before feed, play and watch are clicked 

![appsecondpageeating](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/9d146f4b-8ade-469f-b107-44ae42dd862c)

This is after clicking on the "Eat" button. The hunger has increased (The larger the number the better, the lower the number the worse) while the other attributes have decreased and the picture has updated according to the eat button.

![appsecondpageplaying](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/5b5a1395-6bdd-4621-bc6f-862b46ca3cef)

After clicking on the "Play" button. The happiness has increased while the other attributes have decreased and the picture has updated to Spiffo playing.

![appsecondpagewashing](https://github.com/ST10443016/IMAD_Assignment2/assets/161335532/ddf8736b-0afc-4a2f-b1b2-4fd0b0e13e1e)

After clicking on the "Wash" button. The cleanliness has increased while the other attributes have decreased and the picture has updated to Spiffo washing.
## Conclusion

This code creates a Tamagotchi-like application where users can interact with buttons to feed, play with, and wash Spiffo. Spiffo's attributes (hunger, happiness, cleanliness) are updated based on these actions, and the UI is updated accordingly with the status displayed in a TextView and Spiffo's image changing dynamically.
## Referencing

The IIE. 2024. Introduction to Programming Logic [IPRG1111 Module Manuell. The Independent Institution of Education: Unpublished.] 

Simpson, C., Hodgetts, A., Siu-Chong, M. and Cowen, N. 2011. Project Zomboid[Online Digital Game], PC, Mac and Linux. United Kingdom, and Canada: The Indie Stone.
