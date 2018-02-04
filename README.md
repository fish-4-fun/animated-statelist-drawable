# AnimatedStateListDrawable

Experimental concepts using [AnimatedStateListDrawable](https://developer.android.com/reference/android/graphics/drawable/AnimatedStateListDrawable.html) and [ShapeShifter](https://github.com/alexjlockwood/ShapeShifter).

We are lucky as Android developers that vectors and animated vectors are finally now supported. Before this playful API was introduced, acheiving the results below would likely involve subsclassing View, drawing to a canvas, managing animation listeners etc. The resutling code could be plentiful and verbose. For the most part, not even worth the hassle. Now, we can easily add these subtle improvements to our UI's and they are more easily managed to satisfy changing constraints.

Checkbox Example | Realworld Example
------------ | -------------
<img src="https://raw.githubusercontent.com/fish-4-fun/animated-statelist-drawable/master/external-assets/x_2_checkmark.gif" width="320"> | <img src="https://raw.githubusercontent.com/fish-4-fun/animated-statelist-drawable/master/external-assets/realworld-subtle-touch.gif" width="320">
