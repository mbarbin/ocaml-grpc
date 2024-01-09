## 0.2.1-preview.2 2024-01-09

This is an experimental release meant to ease testing of the new typed
API. It is not meant for public consumption.

- Experiment with a typed API
  ([#48](https://github.com/dialohq/ocaml-grpc/pull/22)) ([@mbarbin](https://github.com/mbarbin))
- More PR merged since 0.2.0 (undocumented, see git history for more
  details).

## 0.2.0 2023-10-23

- Report HTTP2 error status when it's not OK
  ([#22](https://github.com/dialohq/ocaml-grpc/pull/22)) ([@quernd](https://github.com/quernd))
- Fix message extraction behavior for batched messages
  ([#33](https://github.com/dialohq/ocaml-grpc/pull/33)) ([@quernd](https://github.com/quernd))
- Async server implementation
  ([#27](https://github.com/dialohq/ocaml-grpc/pull/27)) ([@tmcgilchrist](https://github.com/tmcgilchrist))
- Eio server and client implementation
  ([#21](https://github.com/dialohq/ocaml-grpc/pull/21)) ([@quernd](https://github.com/quernd))
- Getting started documentation
  ([#25](https://github.com/dialohq/ocaml-grpc/pull/25)) ([@tmcgilchrist](https://github.com/tmcgilchrist))
- Fix a race condition where gRPC status was not reported
  ([#26](https://github.com/dialohq/ocaml-grpc/pull/26)) ([@doctor-pi](https://github.com/doctor-pi))
- OPAM packages for `grpc-examples` and `grpc-bench`
  ([#24](https://github.com/dialohq/ocaml-grpc/pull/24)) ([@tmcgilchrist](https://github.com/tmcgilchrist))

## 0.1.0 2022-10-23

Initial public release: Message transport, Lwt server and client ([@jeffa5](https://github.com/jeffa5)), Async client ([@mbacarella](https://github.com/mbacarella))
Contributions by: [@ansiwen](https://github.com/ansiwen) [@doctor-pi](https://github.com/doctor-pi) [@quernd](https://github.com/quernd) [@wokalski](https://github.com/wokalski)
