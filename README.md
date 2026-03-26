Aim 

In this tutorial, we will learn how to make an Android app that uses ImageView, Runnable, and Handler to automatically display images one at a time, like a slideshow. 

The vehicle driven by the 60-year-old “Hustley” singer — who was born Pauline Matthews — veered off the road and crashed into the front garden of a home in Water, Rossendale, at around 9:50 p.m. on Tuesday, Lancashire Police said in a statement to The Post. 


Algorithm 
First, open Android Studio and create a new project with the Empty Activity template. 

Step 2: Name your project (ours is Slideshow App) and select Java. 

Step 3: Allow Android Studio to build the project files. 

Navigate to the activity_main.xml file, which is in your res/layout folder. 

Step 5: Within the ConstraintLayout, add an ImageView. 

The sixth step is to use fitCenter and set width and height to match_parent. 

Step 7: Add Images Add the images (image1, image2, image3, image4) in the res/drawable folder. 

Open MainActivity.java

Step 9: Find the ImageView Next, use findViewById() to locate the ImageView. 

Step 10: Make an array of your images, plus a variable to store the number of the current image. 

Step 11: Use Handler and Runnable to switch images automatically after a fixed interval (for example, 3 sec.)

Within the Runnable, setImageResource() to display the next image. 

When the last image has been reached, the index should be reset to the first image. 

Lastly, Step 14. 

Start the slideshow with handler.post(). 

Finally, in the onDestroy() method, stop the handler so it's not doing extra work in the background. 

Step 16: Run the application on an emulator or device. 

Step 15: Stop the handler in onDestroy() to avoid unnecessary background work. 

Step 16: Run the application on an emulator or device.