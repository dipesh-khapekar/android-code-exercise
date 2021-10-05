# android-code-exercise
Skeleton project for the coding exercise for Android candidates

Step 1: import dependency in Build.gradle file

implementation "androidx.constraintlayout:constraintlayout:${versions.constraintLayout}"
implementation "com.github.bumptech.glide:glide:${versions.glide}"

Step 2: We will use constraint Layout for designing recycler view item.

Step 3: Update User data class arguments as per required fields.

Step 4: We will bind the list item xml view with Recycler View Adapter. And for loading user profile image we will use Glide library with some customization (like radius)

Step 5: For adding divider in recycler view items, we will write extention function on Recycler view to decorate items. 

Step 6: We will keep common dimensions and standard pixcels in dimens file and colors in color file

Step 7: Build the code and Run... Enjoy!!

