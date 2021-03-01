# jQuery Tristate WebJar (jquery-tristate)

[jQuery Tristate](https://github.com/vanderlee/tristate) by [Martijn van der Lee](https://github.com/vanderlee)
adds a tristate (indeterminate) checkbox with pseudo selectors and optional value modification and .val()
overwrite to jQuery. It is licensed with the [MIT License](https://opensource.org/licenses/MIT).
This [WebJar](https://webjars.org) includes the corresponding JavaScript file.

[jQuery](https://jquery.com/) is provided the [OpenJS Foundation](https://openjsf.org/) under the
[MIT License](https://jquery.org/license/).

WebJars are usually built using a plain Maven POM. This WebJar uses the
[Wagon Maven Plugin](https://www.mojohaus.org/wagon-maven-plugin/) to download the jQuery Tristate file from
[jsDelivr](https://www.jsdelivr.com/) and puts it into the Java archive.

## Usage

Just include this WebJar into your project. For Maven, you can use the following snippet:

```xml
<dependency>
    <groupId>org.webjars</groupId>
    <artifactId>jquery-tristate</artifactId>
    <version>1.2.1</version>
</dependency>
```

And here is a Gradle snippet for you:

```groovy
implementation 'org.webjars:jquery-tristate:1.2.1'
```

## Building

Just call

    mvn clean install

and the Jar is built. You can check the output in the target folder. Please make sure that all
required files are included and have proper content.

## Contributing

I highly welcome your updates and improvements. Please open a pull request if you want to contribute
to the jQuery Tristate WebJar. Thanks in advance!
