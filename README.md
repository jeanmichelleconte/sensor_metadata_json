# sensor_metadata_json
Tools, schemas and example files for metadata for ocean platforms and sensors

Follows Argo float, sensor, paramater, and configuration schemes as well as identifying [NVS](https://vocab.nerc.ac.uk/) controlled vocabulary terms using their Indentifier URN (e.g., [SDN:R25::FLUOROMETER_CHLA](http://vocab.nerc.ac.uk/collection/R25/current/FLUOROMETER_CHLA/)).

| Directory | Description|
| --- | --- |
| **code** | Demonstration Python code to validate and parse JSON metadata instances againt the schema as well as validate controlled vocabulary terms using NVS server REST API.|
| **examples** | Some spare example files, probably redundant|
| **json_platforms** | Schema-compliant examples for platforms|
| **json_sensors** | Schema-compliant examples for sensors|
| **json_floats** | Schema-compliant examples for floats, made using make_float_json_from_floatdef.m|
| **schemas** | JSON Schemas for sensors, platforms, and floats.  Needed by validating JSON parsers.|
| **txt_floatdefs** | Example text floatdef files that define a float being made up of one platform and multiple sensors|
| **nc_meta** | Fairly complete Argo meta.nc files made from the json_float files, made using make_argo_metanc_from_floatdef_json.m|

Current effort involves @SBS-EREHM (Eric Rehm, Sea-Bird Scientific) Jean-Michel Leconte, RBR, and @BrianKingNOC (Brian King, NOC)

