# Website to Android App

This is an Android studio project that allows you to create an Android App from an existing     
website or local HTML. It is intended as a skeleton for later making an automated site.

---

## Getting started

Clone this repository and open with Android Studio.

`git clone https://github.com/vluz/WebsiteToAndroidApp.git`

---

### Using a remote source

1. Open `app/res/values/strings.xml` and edit `app_name` and `web_url` strings.

	```xml
    <string name="app_name">Victor Luz</string>
    <string name="web_url">https://vluz.eu/</string>
	```

---

2. Open the `app/java/com.example.app/MyWebViewClient.java` file and replace `example.com`      
   with your hostname.

	```java
	String hostname = "vluz.eu";
	```

--- 

3. If you want to change package name, go to `Graddle Scripts/build.gradle` for Module :app      
   and change it.

```java
	applicationId "eu.vluz.webapp"
```

---

### Using a local source

If you want to create a local HTML5 android app put all your files      
including your `index.html` in the `app/assets` directory.     
Delete the `local_index_goes_here` placeholder.

---

## Icons

To change your app icon, replace files in `app/res/mipmap-*` with your icons.
