# botopolis

A hubot clone in Go! botopolis is extendable with plugins and works with different
chat services.

## Usage

See [example_test.go](./example_test.go) or [the example app](./example/) for usage details.

## Configuration

Most configuration of botopolis happens through the addition of plugins.

The one exception is the server. You can set the port of the web server via the
environment variable `PORT`.
