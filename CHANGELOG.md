v1.0.6
----------
 * use trigram tokenizer instead of filter to allow for phrase queries on urn paths
 * store both a keyword and tokenized version of locations (without any path)

v1.0.5
----------
 * Fix Travis goreleaser releases

v1.0.4
----------
 * Put rp-indexer binary in root dir

v1.0.3
----------
 * Fix goreleaser config

v1.0.2
----------
 * index groups by uuid for each contact
 * add case insensitive location query in unit test
 * add test for contact with multiple tel urns

v1.0.1
----------
 * Add changelog, move to fancy revving
