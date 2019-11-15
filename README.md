# Okimochi

Spread your hashed okimochi messages, Manage them safely.

1. Enter your okimochi in `okimochi hash` to get your hashed okimochi.
2. Spread and tweet your okimochi hash. 
3. You can view your original okimochi with `okimochi show "<hash of okimochi>"`.
4. Your friends can verify your original okimochi by hashing it.

## Setup

### Dependencies

- `pass`: http://www.passwordstore.org/
    - `gpg` or `gpg2` (pass depends on them)
- `shasum`

### Initialization

Run `okimochi init [-p <path_of_store>] "<your gpg-id>"`

+ `<path_of_store>` defaults to `~/.okimochi-store`
+ Your gpg-id is a 64bit value in hex. Run `gpg --list-keys` to find it.

You can also run `okimochi git` to make your storage a git repo.
A new commit will be made every time you add a new okimochi.

## Usage

### Add a new okimochi

Run `okimochi hash`, then type a your okimochi.

### Recover okimochi

`okimochi show <hash of okimochi>` 

### Discover more

See `okimochi help` for more details.

