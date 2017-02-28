# jsonp
Patches to https://java.net/projects/jsonp branched from a586e706aea82dc80fb05bdf59f2a25150ee1801 (1.0.4 release)

Hopefully this is not going to be a regular thing but I found a need to patch the 1.0.4 release, 1.1 is in progress and looks to be a substantial change.

## Change History

1. Patch javax.json.JsonObjectBuilder for NPE when invoking isNull of a property that does not exist
