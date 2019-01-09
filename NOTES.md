Android getting started:

Android Basics:
Day 1:
* Learning about Views, rectangular pieces in the UI
* Views are using XML with android namespace
* Learned about DP = Density-Independent Pixesl. In case you're wondering, 48dp translates to approximately 9mm in physical size. See more info here
* Touch targets should be 48dp at least
* Material Design: https://material.io/design/typography/#type-scale
* Colorpalette: https://material.io/design/color/#color-usage-palettes
* Reference: https://developer.android.com/

LinearLayout vs RelativeLayout

Learned to build really basic layouts
"Happy Birthday App" with a basic RelativeLayout, two TextViews and an ImageView - so much wow xD


Day 2:
Learned that Udacity suggests that as an experienced Developer you should not do that course but: https://classroom.udacity.com/courses/ud851 Developing Android Apps .... DAFUQ UDACITY THANKS FOR TELLING ME THAT ON DAY 2

So I moved over to the other course: Lesson 1 - again.
Create Project Sunshine :) ... FUCK IT they are having their own repos I can fork ... well goodbye to this repo and continue to work in the fork.

Nothing too new here - this course is quite different working with a lot of todos in existing projects.

Learned a bit more about the basics and then about responsive layouts
The most common ones seem to be FrameLayout, LinearLayout and ConstraintLayout.

FrameLayout: Great when you only have one child view e.g ListView that fills entire content area
LinearLayout: Perfectly for stacking vertically/horizontally different views
ConstraintLayout: Powerful but more complicated than others


Resource Folder Android Doc: https://developer.android.com/guide/topics/resources/providing-resources

Accessing Strings Examples:
Programatically: String myString = getString(R.string.today);
In UI (XML): <TextView text=”@string/today” />

To create a menu:
Override onCreateOptionsMenu within Activity:
public boolean onCreateOptionsMenu(...){
    getMenuInflater().inflate()(R.menu.main, menu);
    return true;
}