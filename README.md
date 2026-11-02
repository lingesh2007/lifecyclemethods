# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by:Lingesh.D
Registeration Number :212225280151
package com.example.lifecyclemethods;

import android.os.Bundle;
import android.widget.Toast;

import androidx.activity.EdgeToEdge;
import androidx.appcompat.app.AppCompatActivity;
import androidx.core.graphics.Insets;
import androidx.core.view.ViewCompat;
import androidx.core.view.WindowInsetsCompat;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast= Toast.makeText(getApplicationContext(), "onCreate Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast toast= Toast.makeText(getApplicationContext(), "onRestart Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onPause(){
        super.onPause();
        Toast toast= Toast.makeText(getApplicationContext(), "onPause Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStop(){
        super.onStop();
        Toast toast= Toast.makeText(getApplicationContext(), "onStop Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume(){
        super.onResume();
        Toast toast= Toast.makeText(getApplicationContext(), "onResume Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast toast= Toast.makeText(getApplicationContext(), "onDestroy Called",Toast.LENGTH_LONG);
        toast.show();
    }
}
*/
```

## OUTPUT

<img width="1920" height="1080" alt="m1" src="https://github.com/user-attachments/assets/34382219-d004-4e7d-a8e7-79fcb4591ce2" />

<img width="1920" height="1080" alt="m2" src="https://github.com/user-attachments/assets/42d03898-b0cc-4b43-8b83-2f99f31011c5" />

<img width="1920" height="1080" alt="m3" src="https://github.com/user-attachments/assets/be6174ba-49bd-40b0-9a86-d469f8e015da" />

<img width="1920" height="1080" alt="m4" src="https://github.com/user-attachments/assets/8936d754-eb76-43a8-9217-3882c1546b1c" />


## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
