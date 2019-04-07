# go-project-conventions
A reminder of how to setup a go project when using GitHu

#### Folder Structure (Local)
go recommends having a `/go` directory inside `~` aka `Users/username` (Unix)

`~/go` is your workspace

#### src & bin
go uses a src and bin folder layout, `~go/src` & `~go/bin`. With your source code being written in `src/my-project` and your executables being saved to `bin`

#### Source Repositories (GitHub)
If using GitHub, go recommends having a directory structure in your go folder matching your account
`~/go/github.com/username`.
You would clone or make repos within this folder.
`~/go/github.com/username/my-project`

#### Naming Conevntions (Personal)
Prefix go projects with `go-` eg.`go-hello`.
This makes them easy to find on github and minimises repo name clashes.
