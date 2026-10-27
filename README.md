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
Developed by:R.Manobala
Registeration Number :212225230167

xml:
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:background="#BA6D6D"
        android:text="Lifecycle Activity"
        app:layout_constraintBottom_toTopOf="@+id/textView"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.527"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.683" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:background="#2196F3"
        android:text="Welcome to Android Studio"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.551"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="502dp" />

</androidx.constraintlayout.widget.ConstraintLayout>


java:
package com.example.test;

import android.os.Bundle;
import android.widget.Toast;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onStart() {
        super.onStart();
        Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onPause() {
        super.onPause();
        Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onResume() {
        super.onResume();
        Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onStop() {
        super.onStop();
        Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG).show();
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG).show();
    }
}
*/
```

## OUTPUT
<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/1b12a054-806f-4ac3-a3c9-59bfba4f20bf" />
<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/f66de3e6-e6a9-41dc-8ed0-900c53566c02" />
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/20f7d290-d95a-4bc8-914d-6c19e39c2602" />
<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/7f45a7c8-3fcc-4f7b-983a-6ff920dacdfd" />
<img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/81883fe5-350f-4751-97a3-17ba5649f884" />
<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/f846f29e-b558-45c8-b8ec-7613b9957050" />
<img width="1920" height="1080" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/936fe622-af82-4ae9-9bc4-a20d1a6041c0" />





## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
