<p align="center">
<p align="center">
  <a href="https://github.com/i-rin-eam">
    <img src="https://avatars.githubusercontent.com/u/154800878?s=400&u=5d18880cc28646190a19a971bfcdbc54644eab07&v=4" alt="Logo" width="100" height="100">
  </a> 
<h1 align='center'>Practice Challenge 4 Soltuion</h1>
<h3 align='center'>
   Visit my youtube channel <a href="https://www.youtube.com/@LearnWithYeamin">Learn With Yeamin</a>
</h3>
</p>

## Step 1: Download `drawable` images <a href="https://www.dropbox.com/s/udqzfgvthip5fpv/Shohoz%20Icon(pc-4).zip">from Here</a>

## Step 2: Here is `activity_main.xml` code.
```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/head"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentTop="true"
        android:src="@drawable/head" />


    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_above="@+id/bottom_view"
        android:layout_below="@+id/head"
        android:gravity="center"
        android:orientation="vertical"
        android:weightSum="3">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_above="@+id/bottom_view"
            android:layout_below="@+id/head"
            android:layout_weight="1"
            android:gravity="center"
            android:orientation="horizontal"
            android:weightSum="2">


            <androidx.cardview.widget.CardView
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_margin="10dp"
                android:layout_weight="1"
                app:cardCornerRadius="5dp"
                app:cardElevation="10dp">


                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:orientation="vertical"
                    android:padding="10dp">

                    <ImageView
                        android:layout_width="50dp"
                        android:layout_height="50dp"
                        android:scaleType="fitXY"
                        android:src="@drawable/burger" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="30dp"
                        android:text="Food"
                        android:textColor="#00BCD4"
                        android:textSize="20sp"
                        android:textStyle="bold" />


                </LinearLayout>

            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_margin="10dp"
                android:layout_weight="1"
                app:cardCornerRadius="5dp"
                app:cardElevation="10dp">


                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:orientation="vertical"
                    android:padding="10dp">

                    <ImageView
                        android:layout_width="50dp"
                        android:layout_height="50dp"
                        android:scaleType="fitXY"
                        android:src="@drawable/bus" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="30dp"
                        android:text="Bus"
                        android:textColor="#00BCD4"
                        android:textSize="20sp"
                        android:textStyle="bold" />


                </LinearLayout>

            </androidx.cardview.widget.CardView>

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_above="@+id/bottom_view"
            android:layout_below="@+id/head"
            android:layout_weight="1"
            android:gravity="center"
            android:orientation="horizontal"
            android:weightSum="2">


            <androidx.cardview.widget.CardView
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_margin="10dp"
                android:layout_weight="1"
                app:cardCornerRadius="5dp"
                app:cardElevation="10dp">


                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:orientation="vertical"
                    android:padding="10dp">

                    <ImageView
                        android:layout_width="50dp"
                        android:layout_height="50dp"
                        android:scaleType="fitXY"
                        android:src="@drawable/truck" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="30dp"
                        android:text="Truck"
                        android:textColor="#00BCD4"
                        android:textSize="20sp"
                        android:textStyle="bold" />


                </LinearLayout>

            </androidx.cardview.widget.CardView>

            <androidx.cardview.widget.CardView
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_margin="10dp"
                android:layout_weight="1"
                app:cardCornerRadius="5dp"
                app:cardElevation="10dp">


                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:orientation="vertical"
                    android:padding="10dp">

                    <ImageView
                        android:layout_width="50dp"
                        android:layout_height="50dp"
                        android:scaleType="fitXY"
                        android:src="@drawable/sheep" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="30dp"
                        android:text="Launch"
                        android:textColor="#00BCD4"
                        android:textSize="20sp"
                        android:textStyle="bold" />


                </LinearLayout>

            </androidx.cardview.widget.CardView>

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_above="@+id/bottom_view"
            android:layout_below="@+id/head"
            android:layout_weight="1"
            android:gravity="center"
            android:orientation="horizontal"
            android:weightSum="2">


            <androidx.cardview.widget.CardView
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_margin="10dp"
                android:layout_weight="2"
                app:cardCornerRadius="5dp"
                app:cardElevation="10dp">


                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:orientation="vertical"
                    android:padding="10dp">

                    <ImageView
                        android:layout_width="50dp"
                        android:layout_height="50dp"
                        android:scaleType="fitXY"
                        android:src="@drawable/bike" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="30dp"
                        android:text="Ride"
                        android:textColor="#00BCD4"
                        android:textSize="20sp"
                        android:textStyle="bold" />


                </LinearLayout>

            </androidx.cardview.widget.CardView>

        </LinearLayout>

    </LinearLayout>

    <ImageView
        android:id="@+id/bottom_view"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:src="@drawable/app_download_home" />

</RelativeLayout>
```
## Authors

**MD YEAMIN** - Android Software Developer <a href="https://www.youtube.com/@LearnWithYeamin">**(Learn With Yeamin)**</a> 

<h1 align="center">Thank You ❤️</h1>
