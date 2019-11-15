# okimochi

Spread your hashed okimochi messages, Manage them safely.

1. Enter your okimochi in `okimochi hash` to get your hashed okimochi.
2. Spread and tweet your okimochi hash. 
    + You can view your original okimochi with `okimochi show "<hash of okimochi>"`.
    + Your friends can verify your original okimochi by hashing it.
    + You can 

## Setup

### Dependencies

- `pass`: http://www.passwordstore.org/
    - `gpg` or `gpg2` (pass depends on them)
- `shasum`

### Initialization

Run `okimochi init "<your gpg-id>"`

+ `<path_of_store>` defaults to `~/.okimochi-store`
+ Your gpg-id is a 64bit value in hex. Run `gpg --list-keys` to find it.

You can also run `okimochi git init` to make your storage a git repo.
A new commit will be made every time you add a new okimochi.

## Usage

### Add a new okimochi

Run `okimochi hash`, then type a your okimochi.

### Decrypt okimochi

`okimochi show <hash of okimochi>` 

### Discover more

See `okimochi help` for more details.
