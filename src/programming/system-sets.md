Warning: this page has not been updated for Bevy 0.10 yet!

# System Sets

{{#include ../include/links.md}}

System Sets allow you to easily apply common properties to multiple systems,
for purposes such as [labeling][cb::label], [ordering][cb::system-order],
[run criteria][cb::runcriteria], and [states][cb::state].

```rust,no_run,noplayground
{{#include ../code/src/basics.rs:systemset-labels}}
```
