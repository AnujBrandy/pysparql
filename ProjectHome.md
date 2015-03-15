It performs SELECT and ASK queries on an endpoint which implements the HTTP (GET or POST) bindings of the SPARQL Protocol.

Typed literals are converted to their equivalent Python types. If isodate module is present, date strings are parsed, and if rdflib is present, the URI literals are converted to URIRef objects, otherwise both types are treated as unicode strings.

The API is based on SPARQL JavaScript Library by Lee Feigenbaum and Elias Torres.