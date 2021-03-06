# Envygram

View popular Instagram photos for your envy.

This is an Android application for displaying a stream of recent, popular Instagram photos using the [Instagram API](http://instagram.com/developer/).

Time spent: 8 hours spent in total

Completed user stories:

 * [x] *Required*: User can scroll through current popular photos from Instagram
 * [x] *Required*: For each photo displayed, user can see: Graphic, Caption, Username
 * [x] *Optional*: Add pull-to-refresh for popular stream with [SwipeRefreshLayout](http://guides.codepath.com/android/Implementing-Pull-to-Refresh-Guide)
 * [x] *Optional*: Show latest comment for each photo (bonus: show last 2 comments)
 * [x] *Optional*: Display each user profile image using a RoundedImageView
 * [x] *Optional*: Display a nice default placeholder graphic for each image during loading
 * [x] *Optional*: Improve the user interface through styling and coloring
 * [x] *Optional*: Like count, user profile image

Also implemented ViewHolder pattern for fast lookups.

**Walkthrough of all user stories:**

![Video Walkthrough](images/envygramwalkthrough.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

Splash screen stock photo credited to [Unsplash](http://unsplash.com/).

**Libraries**

This app leverages two third-party libraries:

 * [Android AsyncHTTPClient](http://loopj.com/android-async-http/) - For asynchronous network requests
 * [Picasso](http://square.github.io/picasso/) - For remote image loading
