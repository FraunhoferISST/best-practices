# Profiling the Decentralized Claims Protocol

The DCP defines a set of extension points that need to be populated by profiles. Luckily, the spec defines some in the
annex already. Profiles are designated by strings and used in the `CredentialObject` that's part of the `IssuerMetadata`
property.

There's a connection between the `profile` and the `format` property as used in the `CredentialRequestMessage`.