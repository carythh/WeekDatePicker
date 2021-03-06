# WeekDatePicker

WeekDatePicker is a lightweight implementation of week date picker for Android. It is based on a View instead of ViewGroup. That gives it benefit of being memory efficient, fast and adds ability of infinite scrolling.

Date implementation is based on Java 8 Date Time backport [threeten](http://www.threeten.org/)

## Example
![Example screenshot](images/example_screenshot.gif)

Source code with examples is included in repository.

## Dependencies
### Gradle
```
compile "solar.blaz:week-date-picker:1.2"
```

## Usage
```xml
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <solar.blaz.date.week.WeekDatePicker
        android:id="@+id/date_picker"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:paddingTop="5dp"
        android:paddingBottom="5dp"
        android:textSize="18sp"
        android:textColor="@color/date_picker_text_color"
        app:wdp_labelTextSize="12sp"
        app:wdp_labelPadding="5dp"
        app:wdp_dayBackground="@drawable/date_picker_day_bg"
        app:wdp_indicatorDrawable="@drawable/date_picker_indicator"
        app:wdp_firstDayOfWeek="monday"/>

</LinearLayout>

```
