CHANGELOG
=========

v1.0.8 (06.09.2019)
-------------------
- included `limit` and `metrics` service
- ability to expose GRPC stats to Prometheus

v1.0.7 (22.05.2019)
-------------------
- Server and Invoker are final
- added support for pool controller (roadrunner 1.4.0) 
- added strict_types=1

v1.0.4-1.0.6 (26.04.2019)
-------------------
- bugfix, support for imported services in proto annotation by @oneslash 

v1.0.2 (18.03.2019)
-------------------
- added support for `php_namespace` option
- added support for nested namespace resolution in generated code
  (thanks to @zarianec)
- protobuf version bump to 1.3.1

v1.0.1 (30.01.2019)
-------------------
- fixed bug causing server not working with empty payloads
- fixed bug with disabled RPC service
- added elapsed time to the debug log

v1.0.0 (20.10.2018)
-------------------
- initial application release
