<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#fff">


    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="10sp"
        android:scaleType="centerCrop"
        android:src="@drawable/udacitybanner" />

    <ImageView
        android:id="@+id/udacity_logo"
        android:layout_width="75sp"
        android:layout_height="75sp"
        android:layout_centerHorizontal="true"

        android:layout_margin="15sp"
        android:src="@drawable/udacity"/>

    <TextView
        android:id="@+id/udacity_title"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_below="@id/udacity_logo"
        android:fontFamily="sans-serif-light"
        android:layout_margin="0sp"
        android:text="UDACITY"
        android:textStyle="bold"
        android:textColor="#000"
        android:textSize="35sp" />

    <TextView
        android:id="@+id/phone_number"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_margin="20sp"
        android:layout_below="@id/udacity_title"
        android:fontFamily="sans-serif-light"
        android:text="650-555-5555"
        android:textColor="#000"
        android:textSize="15sp" />

    <TextView
        android:id="@+id/url"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_margin="0sp"
        android:layout_below="@id/phone_number"
        android:fontFamily="sans-serif-light"
        android:text="www.udacity.com"
        android:textColor="#000"
        android:textSize="15sp" />

    <TextView
        android:id="@+id/address"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_margin="20sp"
        android:layout_below="@id/url"
        android:fontFamily="sans-serif-light"
        android:text="2465 Latham St Mountain View, CA 94043"
        android:textColor="#000"
        android:textSize="15sp" />

</RelativeLayout>
