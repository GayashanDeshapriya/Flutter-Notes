# Flutter-Notes

Widgets:-
 > Each element on a screen of the Flutter app is a widget. 
(The view of the screen completely depends upon the choice and sequence of the widgets used to build the apps. The structure of the code of an app is a tree of widgets.)

# Flutter-Notes
#Accessibility: These are the set of widgets that make a Flutter app more easily accessible.

#Animation and Motion: These widgets add animation to other widgets.

#Assets, Images, and Icons: These widgets take charge of assets such as display images and show icons.
Async: These provide async functionality in the Flutter application.
Basics: These are the bundle of widgets that are necessary for the development of any flutter application.
Cupertino: These are the iOS-designed widgets.
Input: This set of widgets provides input functionality in a flutter application.
Interaction Models: These widgets manage touch events and route users to different views in the application.
Layout: This bundle of widgets helps place the other widgets on the screen as needed.
Material Components: This is a set of widgets that mainly follow material design by Google.
Painting and effects: This is the set of widgets that apply visual changes to their child widgets without changing their layout or shape.
Scrolling: This provides scrollability to a set of other widgets that are not scrollable by default.
Styling: This deals with the app's theme, responsiveness, and sizing.
Text: This displays text.


# Fundamentals Recap:

- Pseudo-elements — these selectors target elements in the DOM that we haven't explicitly created with HTML tags.

- Use rems for typography due to the accessibility benefits. Users may higher their default browser font size.


# Rendering Logic 1:

- Browser treats inline elements as typography, hence line-height is applied to those elements.

- Inline-block elements internally act like block elements, but externally act like inline elements. The parent container will treat it as an inline element, since it's external. But the element itself can be styled like a block.

- Fit-content behaves like max-content, though if the content is too wide to fit in the parent, it add line-breaks as-needed.

- There are 7 layout modes in CSS, such as Grid and Flexbox layout. In Flow layout, the default layout mode, every element will use a display value of either inline, block, or inline-block. 

- Only vertical margins collapse. Margin collapse is unique to Flow layout. Nesting elements doesn't prevent collapsing. Margins can collapse in the same direction. More than two margins can collapse.

- Be aware of how you use margins. Don't set the specifically on components, in such cases it is better to use layout components. For reusable components, we want them to be as unopinionated as possible.
