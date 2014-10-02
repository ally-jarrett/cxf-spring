CXF-Spring
==========

Simple Spring / CXF Demo

There is a simple hellowold implementation and a slightly more advanced 'Products' implementation. 

Helloworld can be accessed via:
http://localhost:8080/cxf-spring/services/helloServices/helloworld/name

Which will produce something like: '_Hello ${name}_'

Products Service can be accessed via: 
http://localhost:8080/cxf-spring/services/productServices/product/12345

Which will produce something like: '_{"id":"12345","name":"MAC Book Air","type":"Electronics"}_'

