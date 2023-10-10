# Temperature-Converter xml 
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Temperature converter"
        android:textSize="25dp"
        android:textColor="#ffff"
        android:textAlignment="center"
        android:layout_marginTop="30dp"/>

    <EditText
        android:id="@+id/enterTemp"
        android:layout_width="250dp"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:hint="Enter Temperature"
        android:inputType="numberDecimal"
        android:ems="10"
        android:textAlignment="center"
        android:textSize="25dp"
        android:layout_marginTop="25dp"/>

    <Button
        android:id="@+id/cToF"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Celsius To Fahrenheit"
        android:textAlignment="center"
        android:textSize="25dp"
        android:layout_gravity="center"
        android:layout_marginTop="25dp"
        android:textAllCaps="false"/>

    <Button
        android:id="@+id/fToC"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Fahrenheit To Celsius"
        android:textAlignment="center"
        android:textSize="25dp"
        android:layout_gravity="center"
        android:layout_marginTop="25dp"
        android:textAllCaps="false"/>

    <TextView
        android:id="@+id/result"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="0 Degrees"
        android:textAlignment="center"
        android:textSize="25dp"
        android:layout_gravity="center"
        android:layout_marginTop="25dp"/>
</LinearLayout>
