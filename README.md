# okimochi

Spread your hashed okimochi messages, Manage them safely.

1. Enter your okimochi in `okimochi hash` to get your hashed okimochi.
2. Spread (or maybe tweet) your okimochi hash. 
    + You can decrypt and view your original okimochi with `okimochi show "<hash of okimochi>"`.
    + Your friends can verify your original okimochi by hashing it (if you want them to).
    + You can keep your original okimochi secret forever if you want to.

## Setup

### Dependencies

- `pass`: http://www.passwordstore.org/
    - `gpg` or `gpg2` (pass depends on them)
- `shasum`

### Initialization

Run `okimochi init "<your gpg-ids>"`

You can also run `okimochi git init` to make your storage a git repo.
A new commit will be made every time you add or remove an okimochi.

## Examples of usage

### Add a new okimochi

Run `okimochi hash` to hash your okimochi.

### Decrypt okimochi

Run `okimochi show <hash of okimochi>`.

### Discover more

See `okimochi help` for more details.
