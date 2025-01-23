package(default_visibility = ["PUBLIC"])

go_toolchain(
    name = "toolchain",
    version = "1.23.4",
)

go_stdlib(name = "std")

export_file(
    name = "modfile",
    src = "go.mod",
)

go_repo(
    licences = ["BSD-3-Clause"],
    module = "golang.org/x/net",
    version = "v0.30.0",
)

go_repo(
    licences = ["BSD-3-Clause"],
    module = "golang.org/x/sys",
    version = "v0.26.0",
)

go_repo(
    licences = ["BSD-3-Clause"],
    module = "golang.org/x/text",
    version = "v0.19.0",
)

go_repo(
    licences = ["Apache-2.0"],
    module = "google.golang.org/genproto/googleapis/rpc",
    version = "v0.0.0-20241015192408-796eee8c2d53",
)

go_repo(
    licences = ["Apache-2.0"],
    module = "google.golang.org/grpc",
    version = "v1.69.4",
)

go_repo(
    licences = ["BSD-3-Clause"],
    module = "google.golang.org/protobuf",
    version = "v1.36.3",
)

go_repo(
    licences = ["Apache-2.0"],
    module = "google.golang.org/grpc/cmd/protoc-gen-go-grpc",
    version = "v1.5.1",
)
