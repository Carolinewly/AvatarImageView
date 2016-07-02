# AvatarImageView

you can set any style avatar by this view .


The effect：

<img src="http://fanrunqi.github.io/images/AvatarImageView/AvatarImageView.JPG" width = "352" height = "585"  />

# Usage

## Step 1

> Copy [AvatarImageView.java](https://github.com/fanrunqi/AvatarImageView/blob/master/app/src/main/java/cn/fanrunqi/avatarimageview/AvatarImageView.java) to your project.


## Step 2

> use like this.

```
<cn.fanrunqi.avatarimageview.AvatarImageView
            android:layout_width="100dp"
            android:layout_height="100dp"
            android:background="@drawable/oval_shape"
            <!--android:background="@drawable/bg_a"-->
            android:src="@drawable/c"
            />
```

> "android:background" attribute is Use to define the shape of the image.you can use the shape.xml

```
<?xml version="1.0" encoding="utf-8"?>
<shape
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="oval"
    android:useLevel="false">
    <solid android:color="#fff"/>
    <corners android:radius="25dip" />
    <size android:width="200dp"
          android:height="100dp"/>

</shape>
```

> or ,use a picture like [xxx.png](https://github.com/fanrunqi/AvatarImageView/blob/master/app/src/main/res/drawable/bg_a.png)

"android:src" attribute is Use to define the picture you want to show.

