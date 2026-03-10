# Experiment3

Android app that shows images one after another
Aim
A photo app on Android runs slideshows by itself. One picture comes up, then the next begins. Images flow across the display without tapping. After one fades out, another steps into view. The shift from frame to frame moves like a quiet rhythm. Timing sits comfortably, never rushing. Smooth transitions link each shot in line. A single motion kicks things off, then it moves without stopping. Various dimensions fit because changes happen on their own.

A picture appears when you set up the ImageView right. Placing it takes a few steps but works every time. One thing after another leads to showing graphics clearly. Each part connects without needing extra tools. Setup matters more than size here. What shows up depends on correct settings first. Wrong inputs hide the image fast. Following each step brings results slowly.

A sudden image appears, unannounced. When the previous one fades out, tiny dots shift without sound. Seconds pass - click - another switch happens. Darkness hangs briefly before shades reappear. Edges blur into focus as something new settles in place. A quiet rhythm pushes ahead, hidden gears flipping thoughts like leaves. Each passing second narrows the wait before the display changes. Once still, a fresh instant slides through, silent and unnoticed.

To understand the Handler class, think about repeating tasks on Android. Through its methods, timing loops become easier to handle, giving you say over when things run. Delayed actions work better than immediate ones, especially when updating screens. When set up right, repeated jobs keep order without piling up. Timing shifts with how messages move through the system silently. Accuracy happens when tasks drop into place based on developer-defined gaps

To learn how to use Runnable to perform operations repeatedly.
Inside an app, a picture kept in the drawable folder may show up, based on its link to part of the screen. Often, that link works by naming the file straight out. Where the reference sits could play a bigger role when things are loading. When everything is arranged right, the image appears fast. A lone version of each image appears linked to something visible on screen. Spotting mistakes means checking file locations together with script structure.

Becoming familiar with building a basic auto-playing picture slide show on Android devices begins here. One step leads to another, each part connects without needing extra tools. Slides shift by themselves after setup completes. The process stays straightforward throughout. Each detail fits together like pieces of a quiet morning routine.

When a process ends, handling its pieces matters most. Focus moves to hidden actions behind the scenes. From there, pausing extra jobs keeps things steady. Observing closure points carefully aids better component flow. Keeping extras alive with no purpose fits no need.



Algorithm
Start the computer before opening Android Studio.
Start a new Android project right now by choosing the empty activity choice instead. After that, keep going but skip including additional parts during this step.
Begin with entering an app title - perhaps Slideshow App - as your first step, followed by choosing Java when prompted among language options.

Begin with allowing Android Studio to set up project files automatically.
Open the res/layout folder first thing. There you will find a file named activity_main.xml waiting inside.
A shape appears on screen after inserting an ImageView into ConstraintLayout. Sitting correctly, it carries any graphic given to it. That holder keeps the element fixed as intended. Once tied down using guidelines, positioning locks in. Everything functions only when connections are made within the design.
Stretching across the whole screen begins with match_parent for width. For height, apply match_parent once more. This makes the image cover every part you can see.
Pictures stay fully visible when scaleType uses fitCenter. Smooth positioning happens because nothing gets cropped. Centered alignment shows every part of the image. Stretching adjusts gently to fill available area. Visual balance remains clear inside the container.
Hang on to the layout file. Don’t let it go.
Pictures belong in the res/drawable folder - image1, image2, image3, image4, placed directly inside. Nowhere else works. This specific location keeps them grouped. Each finds its place here, fitting without effort. Exactly these file names remain. Once set, they do not shift. Placement locks their form.
Open MainActivity.java.
Picture an image holder you need to connect. Begin with naming that spot in code so it matches the design piece on screen.

One after another, images stack into a lineup meant for showing slides. Inside this set, each picture takes a spot, prepared to appear when called. Nothing slips out of place because the batch keeps all pieces close. When moving from one view to next, none get lost or left behind. Ready and spaced right, every shot waits - no jumps, no doubles, just smooth steps forward.
Now showing: a small sign points at the current image. Every switch moves that indicator to match.

A clock keeps count once images start changing. Another option? Craft a small tool made only for this task. Running solo, it moves from one view to the next on schedule. After silence, the screen shifts without warning. Ready signals trigger every change. Delays get managed on their own, keeping rhythm steady.
A fresh image appears in the ImageView once the task begins. As soon as the Runnable does what it needs to do, the update shows up.
Inside the Runnable, setting the image happens through setImageResource().
A step gets added to currentIndex, nudging it ahead just once. The next check triggers without prompting, loading the image that comes after.

Last image reached? Reset the count to zero so pictures start over. When the tally finishes at the final entry, loop by returning to nothing. Hitting the end of the line means go back to square one for continuity. Finish the sequence? Begin anew from zero. The moment it points to the last element, bring the number down to start again.

Midway through, a new image takes place. A short wait of three seconds sits between changes. After that pause, the handler nudges the next step forward. Timing holds steady because of the built-in gap. Once the clock runs down, visuals shift without warning. The moment the countdown completes, an update slips in.
Open the app, then locate the ImageView using findViewById().
Start displaying slides using handler.post(slideshowRunnable).
Once the task stops, stop the slide display through onDestroy() override.
Open the app using an Android emulator first thing. Or skip that, go straight to testing it on real hardware.

Three seconds pass before the first change takes place. Following that, every image slides forward by itself. No tap or click pulls the next one in. Movement flows without stopping, repeating as it goes. One scene dissolves while another arrives in its place. They move ahead in even steps, never rushing. After a short pause, again they shift - on and on. A moment goes by, then a new image appears. Without any clicks, it shifts on its own.