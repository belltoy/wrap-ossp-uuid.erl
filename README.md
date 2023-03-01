# wrap-ossp-uuid

An example OTP library to wrap an old C NIF library w/ rebar 2 build tool.

## Build

```shell
$ rebar3 compile
```

## Run

```shell
$ rebar3 shell

1> ossp_uuid:make(v4, text).
```

## License

Licensed under [Apache License Version 2.0](LICENSE).
