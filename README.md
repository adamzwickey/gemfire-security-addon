=============
Gemfire Auth/Authz Addon
=============

A Security Addon for Gemfire that will import client certificates into a configured truststore

### Deploying

* Create a BOSH Release
```
$ bosh create release --force
```

* Upload the release to BOSH
```
$ bosh upload release
```

* Create a runtime config and upload to BOHS (see sample in manifest directory)
```
$ bosh update runtime-config runtime-config.yml
```

* Run a BOSH deploy to apply the add-on config
```
$ bosh deploy
```
