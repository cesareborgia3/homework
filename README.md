# 这是一个简易的登录界面
具体实现代码如下：
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:orientation="vertical">

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="60dp"
        android:layout_marginTop="100dp"
        android:layout_gravity="center">

        <ImageView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:src="@mipmap/ic_launcher">

        </ImageView>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:text="@string/welcome"
            android:textSize="40sp"
            android:textStyle="bold">

        </TextView>
    </LinearLayout>

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="70dp"
        android:layout_marginTop="100dp"
        android:layout_marginStart="50dp"
        android:layout_marginEnd="50dp">+

        <TextView
            android:id="@+id/text_1"
            android:layout_width="wrap_content"
            android:layout_height="60dp"
            android:text="@string/username"
            android:textSize="25sp"
            android:textStyle="bold">

        </TextView>

        <EditText
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:layout_toEndOf="@+id/text_1">

        </EditText>

    </RelativeLayout>

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="100dp"
        android:layout_marginTop="5dp"
        android:layout_marginStart="50dp"
        android:layout_marginEnd="50dp">

        <TextView
            android:id="@+id/text_2"
            android:layout_width="wrap_content"
            android:layout_height="60dp"
            android:text="密     码:  "
            android:textSize="25sp"
            android:textStyle="bold">

        </TextView>

        <EditText
            android:layout_width="match_parent"
            android:layout_height="50dp"
            android:layout_toEndOf="@+id/text_2"
            android:inputType="textPassword">

        </EditText>

    </RelativeLayout>

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center">

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="登录">

        </Button>

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="注册">

        </Button>

    </LinearLayout>




</LinearLayout>
