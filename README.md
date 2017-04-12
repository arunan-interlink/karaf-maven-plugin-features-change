This demonstrates different behaviours between the Karaf Maven plugin in 4.0.x and 4.1.x

The main difference is that Karaf 4.0.8 & 4.0.9 will add a "bundle" element to the generated feature file, while 4.1.0 & 4.1.1 will not.

The 4.1.x versions also don't add a "name" attribute to the top level "features" element.
