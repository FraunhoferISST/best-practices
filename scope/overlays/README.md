# Using DCP to authenticate Dataspace Protocol Requests

The Dataspace Protocol has `Policy` objects that (among other purposes) serve as access control rules. In order for a
client to satisfy such a `Policy`, it is essential that the Client presents their credentials
1. via a protocol like DCP
2. with a commonly known semantic structure of the VCs presented.

There will usually be a mapping between claims contained in `Verifiable Credential`s and `Constraint`s that are part of
the `Policy` objects that DSP imports from the ODRL vocabulary. Both are JSON-LD, ergo JSON. An actor like a
Verfiable Data Registry should publish a set of common mappings between the VCs and Constraints.