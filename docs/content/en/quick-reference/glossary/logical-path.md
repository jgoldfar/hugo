---
title: logical path
reference: /methods/page/path/#examples
---

{{< new-in 0.123.0 />}}

A _logical path_ is a page or page resource identifier derived from the file path, excluding its extension and language identifier. This value is neither a file path nor a URL. Starting with a file path relative to the `content` directory, Hugo determines the logical path by stripping the file extension and language identifier, converting to lower case, then replacing spaces with hyphens.
