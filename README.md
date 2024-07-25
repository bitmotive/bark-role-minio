BARK: MINIO
=========

Install MinIO with sane defaults.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**MINIO_ACCESS_KEY**:

The MinIO root user access key

**MINIO_SECRET_KEY**:

The MinIO root user secret key

**MINIO_PORT**:

The port MinIO should run on.


Dependencies
------------

Currently dependent on Debian/Ubuntu due to reliance on `apt` and filepath 
assumptions. 

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com 
