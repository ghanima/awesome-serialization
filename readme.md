# awesome-serialization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> So many formats, so little bandwidth.

## Contents

- [API](#api)
- [Big Data](#big-data)
- [Graph](#graph)
- [Object](#object)
- [Programming](#programming)
- [Academic](#academic)

## API

Serialization suitible for API RPC networked services.

- [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) - Comma Separated Values. Textual.
- [JSON](https://www.json.org) - Lightweight data-interchange format. Textual.
- [Avro](https://avro.apache.org) - Scheme embedded, dynamic rich data structures. Textual/Binary.
- [Thrift](http://thrift.apache.org) - Scalable code generation, schema evolution binary format. Binary.
- [protobuf](https://github.com/protocolbuffers/protobuf) - Google's data interchange format. Binary.
- [msgpack](https://msgpack.org) - Efficient JSON-like binary serialization format. Binary.
- [bson](http://bsonspec.org) - Binary schemeless JSON encoding. Binary.
- [XML](https://www.w3.org/XML/) - Extensible Markup Language. Genuinely Horrible. Textual.
- [Plist](https://en.wikipedia.org/wiki/Property_list) - Property List representation. Apple. Textual.
- [YAML](https://yaml.org) - Identation based data serialization standard. Textual.

## Big Data

Serialization suitble for big data at rest systems, from Hadoop family of solutions.

- [parquet](https://parquet.apache.org) - Columnar storage for Hadoop workloads. Binary.
- [FlatBuffers](https://google.github.io/flatbuffers/) - Protocol Buffers suitible for larger datasets. Binary.
- [orc](https://orc.apache.org) - Columnar storage for Hadoop workloads. Binary.

## Graph

Serialization formats for representing graph oriented data structures.

- [json-ld](https://json-ld.org) - JSON for Linking Data. Textual.
- [Turtle](https://www.w3.org/TR/turtle/) - Terse RDF Triple Language. Textual.

## Object

Serialization formats for memory based data in transit (aka "live" objects).

- [pickle](https://docs.python.org/3/library/pickle.html) - Ram to Disk serialization. Python specific. Binary.
- [Java Object Serialization](https://docs.oracle.com/javase/8/docs/technotes/guides/serialization/index.html) - Ram to Disk serialization. Java specific. Binary.

## Programming

### Python

- [msgpack-python](https://github.com/msgpack/msgpack-python) - MessagePack serializer implementation for Python.

### Swift

- [MessagePack.swift](https://github.com/a2/MessagePack.swift) - Swift MessagePack Serializer.

## Academic

Research papers discussing types, category theory, benchamrks and co.

- [Type theory](https://en.wikipedia.org/wiki/Type_theory) - studies types, which informally are attributes that objects can possess.
- [Category theory](https://en.wikipedia.org/wiki/Category_theory) - General theory of functions. Axiomatic foundation for mathematics, as an alternative to set theory.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Maxim Veksler has waived all copyright and
related or neighboring rights to this work.
