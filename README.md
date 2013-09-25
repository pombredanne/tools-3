## install
```
curl -k https://github.com/rackerlabs/tools/raw/master/install | bash
```
or, specifying branch
```
(echo set -- <branch>; curl -k https://github.com/rackerlabs/tools/raw/master/install) | bash
```

### the following symlinks will be made:
```
/etc/xensource/scripts/fix_vif_reordering_after_resize      -> /opt/rackspace/rackerlabs-tools/fix_vif_reordering_after_resize
/etc/xensource/scripts/prevent_vif_reordering_before_resize -> /opt/rackspace/rackerlabs-tools/fix_vif_reordering_after_resize
```

## useful links
http://docs.vmd.citrix.com/XenServer/6.1.0/1.0/en_gb/api/

## Licensing

[License](LICENSE)
