OViewPager
==========

This is ViewPager with handling duration page changing

Documantation
=============

```xml
<yourpackage.ui.OViewPager xmlns:android="http://schemas.android.com/apk/res/android"
              android:id="@+id/pager"
              android:layout_width="match_parent"
              android:layout_height="match_parent" />

```

``` java
int position = 15;
int duration = 5000;

OViewPager mPager = (OViewPager) findViewById(R.id.pager);
mPager.setAdapter(mAdapter)
mPager.setCurrentItem(position, duration);
```

## Some Information
  * Tested on Galaxy Nexus
  * Tested with 100 Elements
  * 100% support Android 4.0+
  * Can't garrant with memory issue

##Thanks!
