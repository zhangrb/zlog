# Pending

* be/ceph: added support for controlling omap vs bytestream storage
* be/ceph: remove protocol buffers dependency from cls_zlog
* cli: basic cli infrastructure added
* be/lmdb: store unique id in the database to avoid duplicate ids
* be/bench: added simple direct backend benchmark / workload generator

# v0.4.0

The first release in a serious effort to move towards a v1.0.0 release. This
version focused on code simplification and stability. In particular, this
release contains a simplified async I/O implementation, single-writer only (i.e.
no sequencer), simplified stripe and view handling, and a reworked Ceph storage
backend.
