# CustodianLibrary
A library of my personal custom views

## CircularImageView

Contains all the functionality of the standard ImageView
To make the image circular use the ```app:circularSrc``` attribute

```
<com.sejo.custodianlibrary.CircularImageView>
  android:layout_width="60dp"
  android:layout_height="60dp"
  app:circularSrc="@drawable/img.jpg"
</com.sejo.custodianlibrary.CircularImageView>
```

## Dotloader
Spinning loader made up of dots
Able to change the color of the dots using the ```app:loaderColor``` attribute

```
<com.sejo.custodianlibrary.DotLoader>
  android:layout_width="60dp"
  android:layout_height="60dp"
  app:loaderColor="@color/sea_blue"
</com.sejo.custodianlibrary.DotLoader>
```

## Usage 
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.Sejo9:CustodianLibrary:v1.0'
	}
