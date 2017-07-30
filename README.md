# Android-Activity-Animation-In-manifest

##https://stackoverflow.com/questions/8319465/how-to-change-all-the-activity-transitions-at-once-in-android-application
```
<style name="YourTheme" parent="android:Theme.Translucent">
   ...
    <item name="android:windowAnimationStyle">@style/YourAnimation.Activity</item>
</style>

<style name="YourAnimation.Activity" parent="@android:style/Animation.Activity">
    <item name="android:activityOpenEnterAnimation">@anim/slide_in_right</item>
    <item name="android:activityOpenExitAnimation">@anim/slide_out_left</item>
    <item name="android:activityCloseEnterAnimation">@android:anim/slide_in_left</item>
    <item name="android:activityCloseExitAnimation">@android:anim/slide_out_right</item>
</style>
```
