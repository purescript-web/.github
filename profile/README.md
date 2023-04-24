Hi! :wave:


Welcome to `purescript-web`. This organization hosts a collection of [PureScript](https://purescript.org) bindings to various web specifications like [HTML5](https://html.spec.whatwg.org/multipage/), [Web Workers](https://html.spec.whatwg.org/multipage/workers.html), and the [Canvas 2D Context](https://www.w3.org/2015/04/2dcontext-lc-sample.html). We hope you find them useful as you build web applications with PureScript.

If you would like to contribute a binding to this organization, please write up your idea on [the PureScript Discourse](https://discourse.purescript.org/) and one of the maintainers will respond to your post. As you put your bindings together, please bear in mind the following guidelines:

- All of the bindings should mirror the web specifications as closely as possible. As most specifications are imperative and stateful, most of the public API should be written using the `Effect` monad (implementing FFI internally via `EffectFnX` but exposing that publicly via `Effect`) unless there's a compelling reason not to.
- Bindings should implement most of a specification before being submitted.
- Original authors are kindly asked to continue reviewing pull requests and issues for their libraries after they've been transferred to the `purescript-web` organization.

Thank you for your interest in `purescript-web` and in the PureScript programming language. 
