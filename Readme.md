# Example to reproduce https://github.com/dmak/jaxb-xew-plugin/issues/50

To reproduce, simply run 'mvn package'.

The exception only occurs when using `maven-jaxb2-plugin` >= version 0.12.2 and the schema contains an `annotation` element.
