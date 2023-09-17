# password-manager
mini project
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/ic_launcher_background"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:Id="@+Id/signuptitle"
        android:text="Sign up"
        android:textSize="45dp"
        android:textStyle="bold"
        android:gravity="center"
        android:layout_margin="30dp" />

    <EditText
        android:id="@+id/signuptitle"
        android:layout_width="match_parent"
        android:layout_height="298dp"

        android:layout_below="@id/signuptitle"
        android:layout_marginStart=""
        android:layout_marginTop=""
        android:layout_marginEnd=""
        android:layout_marginBottom=""
        android:background="#30fffff"
        android:hint="Username"
        android:padding="20dp"
        android:textColour="@color/White"
        android:textColourHint="@color/White"
        android:textSize="40dp"
        android:textStyle="bold" />

    <EditText

        android:layout_width="match_parent"
        android:layout_height="298dp"
        android:id="@+id/email"
        android:layout_below="@id/username"
        android:layout_marginStart="10dp"
        android:layout_marginTop="80dp"
        android:layout_marginEnd="67dp"
        android:layout_marginBottom="15dp"
        android:background="#30fffff"
        android:hint="Email"
        android:padding="20dp"
        android:textColour="@color/White"
        android:textColourHint="@color/White"
        android:textSize="40dp"
        android:textStyle="bold"
        />
    <EditText

        android:layout_width="match_parent"
        android:layout_height="298dp"
        android:id="@+id/Password"
        android:layout_below="@id/email"
        android:layout_marginStart="20dp"
        android:layout_marginTop="45dp"
        android:layout_marginEnd="45dp"
        android:layout_marginBottom="180dp"
        android:background="#30fffff"
        android:hint="Password"
        android:padding="20dp"
        android:textColour="@color/White"
        android:textColourHint="@color/White"
        android:textSize="40dp"
        android:textStyle="bold"
        />
</RelativeLayout>
