Aim 
To create an Android app that displays images automatically one by one like a slideshow using ImageView, Handler, and Runnable.

ALGORITHM

Step 1: Open Android Studio and create a new project using Empty Activity.

Step 2: Name the project (e.g., Slideshow App) and select Java.

Step 3: Open activity_main.xml and add an ImageView inside ConstraintLayout.

Step 4: Set width and height to match_parent and use fitCenter.

Step 5: Add images (image1, image2, image3, image4) in the res/drawable folder.

Step 6: Open MainActivity.java and connect ImageView using findViewById().

Step 7: Create an array of images and a variable to track the current image.

Step 8: Use Handler and Runnable to change images every few seconds.

Step 9: Use setImageResource() to display images.

Step 10: Reset index to 0 after the last image.

Step 11: Start slideshow using handler.post().

Step 12: Stop handler in onDestroy().

Step 13: Run the app on emulator or device.