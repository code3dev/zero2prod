# Zero To Production

This is my copy of the code from the zero to production book for rust


### Run command:

```shell
cargo watch -x check -x test -x run

TEST_LOG=true cargo test health_check_works | bunyan
```

### CI Steps
```shell
cargo tarpaulin --ignore-tests
cargo clippy
cargo fmt
cargo audit
```

### Cargo Stuff
```shell
cargo install cargo-udeps
cargo install bunyan
```

### Resources:

- [actix-web website](https://actix.rs/)
- [actix-web docs](https://docs.rs/actix-web/4.0.1/actix_web/index.html)
- [actix-web examples](https://github.com/actix/examples)
- [Understanding Serde](https://www.joshmcguigan.com/blog/understanding-serde/)
- [sqlx](https://docs.rs/sqlx/)

### Endpoints

- /health_check


### Services

- https://www.pingdom.com/