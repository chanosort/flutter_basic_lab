. GitHub Repository Link

https://github.com/chanosort/flutter_basic_lab.git

//Last Three build() Called Lines from Activity 2

Paste the last three build() called lines from the Debug Console here after running Activity 2.

Activity 2: StatefulWidget

When I changed _glasses outside setState(), the screen did not update immediately because Flutter was not notified to rebuild the UI. When I used setState(), the screen updated.

Activity 3: Row and Expanded

When I removed Expanded from a StatBox, the layout became uneven because the widgets no longer shared the available space as intended. After restoring Expanded, the layout worked properly.

Activity 5: Theme and Dark Mode

I changed the button corner radius from 8 to 20, making the buttons more rounded. When I turned on dark mode, the app changed to a dark theme.

//////////////////////////////////////////////////////////////
activity 2 : build() called: 4 glasses
             build() called: 5 glasses
             build() called: 6 glasses

ACTIVITY 5 ANSWER : The difference is that the border radius of the containers and buttons has been increased from 8 to 20, making the corners noticeably more rounded.

//////////////////////////////////////////////////////////////
Review questions

1. StatelessWidget is immutable and static while the StatefulWidget is dynamic and can be change

2. to separate the immutable configuration from mutable data

3. the number change but the screen dit not update immediately

4. build() method is called when the app first displays the screen and whenever setState() is called to update the UI. In Activity 2, it runs again when I tap the + button to add a glass of water

5. In a Row, items go horizontally. In a Column, items go vertically.

6. When I removed Expanded, the StatBoxes did not share the space equally and the layout looked uneven. Expanded helps widgets use the available space evenly.

7.because it displays menu items in a grid and allows scrolling.

8. Stack lets widgets overlap, while Positioned places the Best seller badge where we want it.

9. ThemeData changes the style of the whole app, while a widget style changes only one widget.

10. ThemeDemoApp holds the state. When I turn on dark mode, setState() updates the theme and changes the app to dark mode.