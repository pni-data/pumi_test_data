# Example BIDS dataset with three subjects for testing purposes

The dataset is primarily used for testing [PUMI](https://github.com/pni-lab/PUMI).

This is a Git-annex sibling of a Datalad dataset. Does NOT contain the actual data.
Data can only be accessed with valid sciebo credentials.

```
export WEBDAV_USERNAME=XXXX
export WEBDAV_PASSWORD=XXXX-XXXX-XXXX-XXXX
datalad install -s git@github.com:pni-data/pumi_test_data.git pumi_test_data
datalad siblings -d pumi_test_data enable -s sciebo.sfb289
datalad get pumi_test_data/*
```

