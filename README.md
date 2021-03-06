# Thoughts

## Potential Projects

### Quick
Could be an exercise for an afternoon or a few days

### Complicated
Projects which would take longer than a week. Also, I kind of know how I'd approach it.

- Elixir Library for Basic Linear Algebra Subroutines (BLAS)
  * Underlying implementations would be C (Rust?)
  * NIFs for speed, maybe [Rustler](http://rustler.rustbridge.io/rustler/) for Rust and Safety?
- Elixir Library for dataframes (a.k.a. pandas for Elixir)
  * Would probably use the elixir BLAS implementation mentioned above.
- Pairing Organization Application
  * Utility to help groups of people randomly pair amongst themselves.
  * Collects data on pairs
- Ruby/Elixir library for tracking test failures/sucesses
  * Collects data whenever a user runs tests to determine which tests are most
    often failing and which never fail.
  * Could be used to identify tests that aren't actually useful
  * Could build some metrics around these failing or not failing tests
  * Identifies tests that are maybe not useful because they only fail when other tests
    also fail

### Pie in the Sky
Projects that'd be cool, but I don't even know where to start. Maybe you do!

- tmate + vim + independent cursors and buffers.
  * Rather than simply having one cursors shared, each user would have their own cursors.
  * Would be absolute chaos, but could be cool.
