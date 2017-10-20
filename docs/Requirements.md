# Requirements

## Package Naming & Namespacing

* Package names SHOULD BE short an concise

The project will not aim to vendor everything, but it should contain rather smaller packages/modules that can be assemled and reused in any form, then bigger ones.

Follow the simple guideline, that a tool (in our case a library) should do one thing, and one thing only, but this thing very well & it should play well with others.

* Package source files MUST always be scoped in the `TryPhp` namespace and SHOULD BE short and concise

It is not necessary to name a class for example like `TryPhp\Validation\Validator` with a function `validate()`. `TryPhp\Validato` will suffice. If not it can always be changed in the future if it comes to name collisions.

Aswell functions can be assigned directly to the `TryPhp` namespace. Same reasoning as with classes.

## Platform requirements

* Every package should depend on `>=7.0`