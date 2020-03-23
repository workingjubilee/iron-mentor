# iron-mentor

This is iron-mentor, a project developed to simplify mentoring the Rust track
on [exercism.io]. It is a web extension which dispatches requests to a local
application, the server. The server then is permitted to execute various tasks,
some of which are actually quite dangerous to the user, like compiling and
executing code. This extension should not be used at all without careful thought

## Dependencies

This extension is being alpha-tested against Mozilla Firefox and Rust 1.42.

In order to run it requires:

 * A [browser which supports all used Web Extension APIs][firefox]
 * The [exercism CLI][exercism-cli]
 * [Rust with Cargo][rustup]

Optionally, for development:

 * [web-ext]
 * GNU [Make]

## Build

~~If you have Make it's as simple as `make all && make install.~~

[Make]: https://www.gnu.org/software/make/
[exercism-cli]: https://exercism.io/getting-started
[exercism.io]: https://exercism.io
[firefox]: https://www.mozilla.org/en-US/firefox/new/
[rustup]: rustup.rs/
[web-ext]: https://extensionworkshop.com/documentation/develop/getting-started-with-web-ext/