# Flutter-Notes

# Widgets:-
-  Each element on a screen of the Flutter app is a widget. 
(The view of the screen completely depends upon the choice and sequence of the widgets used to build the apps. The structure of the code of an app is a tree of widgets.)

# mainly 14 categories widgets:

- Assets, Images, and Icons: These widgets take charge of assets such as display images and show icons.
- Async: These provide async functionality in the Flutter application.
- Basics: These are the bundle of widgets that are necessary for the development of any Flutter application. 
- Cupertino: These are the iOS-designed widgets.
- Input: This set of widgets provides input functionality in a Flutter application.
- Interaction Models: These widgets manage touch events and route users to different views in the application.
- Layout: This bundle of widgets helps place the other widgets on the screen as needed.
- Material Components: This is a set of widgets that mainly follow material design by Google.
- Painting and effects: This is the set of widgets that apply visual changes to their child widgets without changing their layout or shape.
- Scrolling: This provides scrollability to a set of other widgets that are not scrollable by default.
- Styling: This deals with the app's theme, responsiveness, and sizing.
- Text: This displays text.

# Writing a widget in code:
![Imgur](https://github.com/GayashanDeshapriya/Flutter-Notes/blob/main/Writing%20a%20widget%20in%20code1.png)

- When creating widgets, there is only one requirement enforced by the widget superclass. It must have a build method.
![Imgur](https://github.com/GayashanDeshapriya/Flutter-Notes/blob/main/Writing%20a%20widget%20in%20code.png)

- You can add methods and properties to the widget classes.
![Imgur](https://github.com/GayashanDeshapriya/Flutter-Notes/blob/main/Writing%20a%20widget%20in%20code%203.png)

# Stateless Widget:
- A StatelessWidget is a widget that you (as the developer) are okay with being destroyed. In other words, no information is kept within it that, if lost, will matter.




# Stateful Widget:
- Importantly:
--The StatefulWidget class must implement the createState method.
--The State object must implement the build method.
--The StatefulWidget is immutable.
--The State object is mutable.

