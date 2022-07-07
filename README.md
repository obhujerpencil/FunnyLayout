# FunnyLayout 😂
Checkmate Boredom: playing with android layouts, scrolls, image &amp; buttons.

## Screenshot
![Screenshot (312)](https://user-images.githubusercontent.com/63474307/177710156-ba432173-cc3c-4e1c-a68b-952915f8a0be.png)

## Video
https://user-images.githubusercontent.com/63474307/177711380-030b0f3d-2588-49df-b24e-ad956e982a67.mp4

## Cheat codes
Jet pack on<br>
Hash code for amber: #FFBF00 <br>
Attack:
```bash
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">
    <!-- Google Image -->
    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:srcCompat="@drawable/google" />
    <!-- Start of Horizontal Button Layout-->
    <HorizontalScrollView
        android:layout_width="match_parent"
        android:layout_height="wrap_content">
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal">
            <androidx.appcompat.widget.AppCompatButton
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:background="@color/amber"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="10dp"
                android:text="YES"
                android:textStyle="bold"
                android:textSize="30dp">
            </androidx.appcompat.widget.AppCompatButton>
            <androidx.appcompat.widget.AppCompatButton
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:background="@color/amber"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="10dp"
                android:text="NO"
                android:textStyle="bold"
                android:textSize="30dp">
            </androidx.appcompat.widget.AppCompatButton>
            <androidx.appcompat.widget.AppCompatButton
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:background="@color/amber"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="10dp"
                android:text="YES"
                android:textStyle="bold"
                android:textSize="30dp">
            </androidx.appcompat.widget.AppCompatButton>
            <androidx.appcompat.widget.AppCompatButton
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:background="@color/amber"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="10dp"
                android:text="NO"
                android:textStyle="bold"
                android:textSize="30dp">
            </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="100dp"
            android:layout_height="70dp"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="YES"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="100dp"
            android:layout_height="70dp"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="NO"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="100dp"
            android:layout_height="70dp"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="YES"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="100dp"
            android:layout_height="70dp"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="NO"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        </LinearLayout>
    </HorizontalScrollView>
    <!-- End of Horizontal Button Layout-->

    <!-- Start of Text View Layout-->
    <ScrollView
        android:layout_width="match_parent"
        android:layout_height="350dp">
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="vertical">
            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_margin="10dp"
                android:text="@string/myText"
                android:textSize="20dp">
            </TextView>
        </LinearLayout>
    </ScrollView>
    <!-- End of Text view Layout-->

    <!-- Start of vertical Button Layout-->
    <ScrollView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_margin="10dp">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="YES"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="NO"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="YES"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="NO"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="YES"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
        <androidx.appcompat.widget.AppCompatButton
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/amber"
            android:layout_marginLeft="10dp"
            android:layout_marginTop="10dp"
            android:text="NO"
            android:textStyle="bold"
            android:textSize="30dp">
        </androidx.appcompat.widget.AppCompatButton>
    </LinearLayout>
    </ScrollView>
    <!-- End of vertical Button Layout-->
</LinearLayout>  
```
## Bye bye...
![hello](https://user-images.githubusercontent.com/63474307/177713097-df720f46-75b8-44b3-953e-85d72e8310c2.gif)
