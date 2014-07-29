mvn-repo
========

## What?

__mvn-repo__ is a central maven repository for anyone to use.

## How to use

Simply add the repository to your build.gradle file:
```groovy
repositories {
	jcenter()
	maven { url 'https://github.com/leonardocardoso/mvn-repo/raw/master/maven-deploy' }
}
```

And you can use the artifacts like this:
```groovy
dependencies {
	compile 'com.leocardz:link-preview:1.1@aar'
	// ...
}
```

### List of libraries on this repository

&bull; [Android Link Preview](https://github.com/LeonardoCardoso/Android-Link-Preview "It makes a preview from an url, grabbing all informations. Such as title, relevant texts and images."). Usage: 'com.leocardz:link-preview:1.1@aar'


## License:
The licenses are provided by the individual library owner.

This "mvn-repo" utilizes these libaries and won´t provide any support, responsibility or licenses itself.
