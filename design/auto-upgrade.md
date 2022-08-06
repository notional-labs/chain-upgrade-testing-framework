# Auto upgrade (Migration Testing) (part of System Testing)

The upgrade will happen by upgrading the current running binary version to newer binary version. This processes ensure that migration will happend seemlessly without error.

Assuming that v1 is old version, v2 is new version.

1. Running a network of 4 validators on v1
1. Downloading and installing binary v2
1. Create a governance proposal for software upgrade
1. Vote yes on all four validators
1. Restart all v1 nodes
1. Upgrade happens

## Cosmovisor testing
