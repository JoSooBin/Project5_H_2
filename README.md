# Project5_H_2
메인XML만 수정하여 리니어 레이아웃으로 레이아웃 나누고 색상변경

![Project5_H_2](https://user-images.githubusercontent.com/37572367/88131566-3e04ba00-cc18-11ea-843e-0426db60c805.PNG)
![Project5_H_3](https://user-images.githubusercontent.com/37572367/88131568-3e9d5080-cc18-11ea-9aa3-2168281ada11.PNG)
<LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="2."
        android:orientation="horizontal" >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:orientation="vertical" >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:background="#EAF30F" >
</LinearLayout>

    <LinearLayout
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:layout_weight="1"
    android:background="#000000" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:orientation="horizontal" >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:background="#0000FF" >
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:background="#06EA41" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:background="#FF0000" />

    </LinearLayout>

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_weight="2"
        android:orientation="horizontal"
        android:background="#04DCD4" />


</LinearLayout >
