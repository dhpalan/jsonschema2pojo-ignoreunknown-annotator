# jsonschema2pojo-ignoreunknown-annotator
This project is used as a dependency on https://github.com/dhpalan/jsonschema2pojo-example

## AbstractAnnotator
- Custom annotator class [IgnoreUnknownAnnotator] (src\main\java\org\jsonschema2pojo\custom\IgnoreUnknownAnnotator.java) will set the class level annotation @JsonIgnoreProperties(ignoreUnknown = true) on generated sources
- It can be used to either suppress serialization of unknown properties, or ignore processing of JSON properties during deserialization.
- On eclipse, choose Run As -> Maven install to successfully compile and Build your Jar
