# Keywords

Keywords in CASC can be devided into hard-reserved and soft-reserved,
the former one will always regarded as keyword, which is not allowed to
be used as [identifier](./identifier.md); while the latter one will only
regarded as keyword in specific context, which is allowed to be used in 
most context.

## Hard-reserved keywords

The following list contains the hard-reserved keywords defined in CASC:

```rust
package
use
class
impl
comp
pub
prot
intl
priv
mut
true
false
null
fn
if
else
for
return
as
is
new
self
super
ovrd
```

## Soft-reserved keywords

The following section contains the soft-reserved keywords defined in CASC.

### Reversed Built-in type names

CASC introduced some built-in types, and these type names are soft-reserved keywords:

```rust
unit
bool
char
str
i8
i16
i32
i64
f32
f64
```
