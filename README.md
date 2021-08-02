# Polyfill for the [Sanitizer API](https://github.com/WICG/sanitizer-api/) specification.

The polyfill might provide a shim on top of
[DOMPurify](https://github.com/cure53/DOMPurify/), that mainly rewrites the
specified configuration object into a DOMPurify configuration.

DOMPurify is more interesting than other libraries, as it relies on the
current browser's HTML parsing behavior (it is built on top of the
[NodeIterator](https://developer.mozilla.org/en-US/docs/Web/API/NodeIterator)
interface).
