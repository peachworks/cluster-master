# Changelog

## v1.0.0

 - added listener for `SIGTERM` which triggers graceful shutdown (like `SIGINT`) if `signals` is true (default)
 - added unique env `CLUSTER_IDX` with zero based index for each worker. It can be used to assign separate ports or resources.
