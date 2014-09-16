# VError that won't fail

A clone of [VError v1.4.0](https://github.com/davepacheco/node-verror/tree/v1.4.0) that converts undefined and null arguments to strings so sprintf will not throw an Error.
This is particularly important when you are handling errors as it'll just mask the root cause of the problem.

Credit to [David Pacheco](https://github.com/davepacheco) from Joyent for [VError v1.4.0](https://github.com/davepacheco/node-verror/tree/v1.4.0) this was cloned from

See [VError documentation](https://github.com/davepacheco/node-verror/blob/v1.4.0/README.md) to understand how VError works
