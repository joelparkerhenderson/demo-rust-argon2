# Demo Rust Argon2

Demonstration of Rust Argon2 password hashing function.

* [Rust programming language](https://www.rust-lang.org/)

* [Argon2 crate](https://crates.io/crates/argon2)

## Usage

The demo password is "toomanysecrets".

Run:

```sh
cargo run
```

Output:

```stdout
Create: $argon2id$v=19$m=19456,t=2,p=1$QQdc4KLIGRsW1LPQrkrnAg$NMgsFDG6d5dhGn20tbRm/2d/J4TyoE4zhLYmp8Esvmk
Verify: true
```

## PHC String Format

<https://github.com/simonepri/phc-format>

The PHC String Format is an attempt to specify a common hash string format that's a restricted & well defined subset of the Modular Crypt Format.

Example:

```txt
$argon2id$v=19$m=19456,t=2,p=1$QQdc4KLIGRsW1LPQrkrnAg$NMgsFDG6d5dhGn20tbRm/2d/J4TyoE4zhLYmp8Esvmk
```
