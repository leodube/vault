# @throws
## Synonyms

`@exception`

## Syntax

-   `@throws free-form description`
-   `@throws {<type>}`
-   `@throws {<type>} free-form description`

## Overview

The @throws tag allows you to document an error that a function might throw. You can include the @throws tag more than once in a single JSDoc comment.

## Examples

Using the @throws tag with a type

```javascript
/**
 * @throws {InvalidArgumentException}
 */
function foo(x) {}
```

Using the @throws tag with a description

```javascript
/**
 * @throws Will throw an error if the argument is null.
 */
function bar(x) {}
```

Using the @throws tag with a type and description

```javascript
/**
 * @throws {DivideByZero} Argument x must be non-zero.
 */
function baz(x) {}
```