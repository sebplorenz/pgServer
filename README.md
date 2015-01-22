qualitype_pgserver
==================

Contains
- Postgresql 9.4  (port : 5432)
- pgBouncer 1.5.4 (port : 6543)

To add this cartridge on OpenShift, use the following url :
- http://reflector-getupcloud.getup.io/github/Qualitype/pgServer

To use the connection pooling connect via the port 6543

example :	
	psql -U user_name -p 6543 database_name

Otherwise connect to postgres on the default port 5432. (you know how uhn :P ) 

Plus :
-	All the contrib modules are enabled.

