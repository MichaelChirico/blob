# blob 1.1.1.9001

- Indexing a vector of blobs out of bounds now raises an error. Use `NA` as index to create a `NULL` blob.
- New `validate_blob()`.
- The `blob` class is now based on `list_of(raw())` from the vctrs package (#11).


# blob 1.1.1 (2018-03-24)

- Now suggesting *pillar* instead of importing *tibble*, and using colored
  formatting with the *prettyunits* package with `B` instead of `b` as units
  (#7, #9).

- The blob class can now be used for S4 dispatch.

- Calling `c()` on blob objects returns a blob.


# blob 1.1.0 (2017-06-17)

- New maintainer: Kirill Müller.

- Added `as.blob.blob()`and `as.data.frame.blob()` methods (#3).

- Size of very large blobs is displayed correctly.


# blob 1.0.0

- Initial release.
