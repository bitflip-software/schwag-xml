swagger-xml
===========

This package is experimental, to see if it is more efficient to specify an API specification using strongly restricted and schema validated XML, which will then be used to generate code as well as the Swagger 2.0 yaml file.

The problem that we are trying to solve, here, is that yaml and json are weakly validated, making it harder to write a valid document by hand. If we use Xml schema validation, then we can use an XSD-Validating IDE, like *OxygenXML* or *XML Spy*, to validate our document, auto-complete, and generally make our lives easier.
