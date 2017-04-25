# wp cache decr

<small>[Commands](/commands/) &raquo; [cache](/commands/cache/) &raquo; decr</small>

`wp cache decr` - Decrement a value in the object cache.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Acache-decr+sort%3Aupdated-desc">Github issues</a></small>

<hr />

Errors if the value can't be decremented.

### OPTIONS

&lt;key&gt;
: Cache key.

[&lt;offset&gt;]
: The amount by which to decrement the item's value.
\---
default: 1
\---

[&lt;group&gt;]
: Method for grouping data within the cache which allows the same key to be used across groups.
\---
default: default
\---

### EXAMPLES

    # Decrease cache value.
    $ wp cache decr my_key 2 my_group
    48


