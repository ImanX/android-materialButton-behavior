# Android Material Button Behavior on RecyclerView

### Preview
<img src="https://raw.githubusercontent.com/ImanX/android-materialButton-behavior/master/preview.gif" alt="sample"/>

### Getting Started
Download `MaterialButtonBehavior` and copy or put your project.
add `MaterialButton` component in your `xml` layout that parent it should be `CoordinatorLayout`

`android:layout_width` size of expande

`android:minWidth` size of collapse

`app:layout_behavior` for set `MaterialButtonBehavior` 

### Example
```xml
  <android.support.design.widget.CoordinatorLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent">
        .
        .
        .
        
           <android.support.design.button.MaterialButton
            android:id="@+id/btn_add"
            android:layout_width="160dp"
            android:layout_height="65dp"
            android:elevation="3dp"
            android:gravity="center"
            android:maxLines="1"
            android:text="@string/new_ticket"
            android:textColor="@android:color/white"
            android:textSize="16sp"
            android:minWidth="55dp"
            app:backgroundTint="@color/colorAccent"
            app:cornerRadius="28dp"
            app:icon="@drawable/ic_add"
            app:layout_anchor="@id/recycler"
            app:layout_anchorGravity="bottom|left|end"
            app:layout_behavior="<Your Package>.MaterialButtonBehavior"
            />
```
