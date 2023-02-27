<!-- ![App Brewery Banner](Documentation/AppBreweryBanner.png) -->

# Flash-Chat

## What is Flash Chat

Flash Chat is an internet based messaging app similar to WhatsApp, the popular messaging app that was bought by Facebook for $22 billion. We will be using a service called Firebase Firestore as a backend database to store and retrieve our messages from the cloud.

## Important Steps

* Integrate third party libraries in your app using Cocoapods and Swift Package Manager.
* Store data in the cloud using Firebase Firestore.
* Query and sort the Firebase database.
* Use Firebase for user authentication, registration and login.
* Work with UITableViews and how to set their data sources and delegates.
* Create custom views using .xib files to modify native design components.
* Embed View Controllers in a Navigation Controller and understand the navigation stack.
* Create a constants file and use static properties to store Strings and other constants.
* Create animations using loops.
* Learn about the App Lifecycle and how to use viewWillAppear or viewWillDisappear.
* Create direct Segues for navigation.

## Screens

### Welcome Screen
<img src='Documentation/welcome.png' height=400>

### Login Screen
<img src='Documentation/login.png' height=400>

### Sign Up Screen
<img src='Documentation/signup.png' height=400>

### Chat Screen
<img src='Documentation/chat.png' height=400>

### Chat Screen with Keyboard
<img src='Documentation/chatKeyboard.png' height=400>

## Constants
```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}
 
