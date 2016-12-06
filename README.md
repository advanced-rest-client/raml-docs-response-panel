[![Build Status](https://travis-ci.org/advanced-rest-client/raml-docs-response-panel.svg?branch=master)](https://travis-ci.org/advanced-rest-client/raml-docs-response-panel)  

# raml-docs-response-panel

`<raml-docs-response-panel>` Element that displays response documentation for RAML

This element is used in `<raml-docs-method-viewer>` element.
See it's demo for demo.

### Example
```
<raml-docs-response-panel responses="[[raml.responses]]"></raml-docs-response-panel>
```

The `raml.responses` is a list of responses for current method. It can be
obtained using a `raml-path-to-object` element or by passing method Definition
from RAML's JSON structure.
Note, you have to use ARC's `<raml-js-parser>` since it is also responsoble
for transformind parser JSON output to internal data structure.

### Styling
`<raml-docs-response-panel>` provides the following custom properties and mixins for styling:

Custom property | Description | Default
----------------|-------------|----------
`--raml-docs-response-panel` | Mixin applied to the element | `{}`
`--raml-docs-response-code-color-200` | Color of the 200 status code | `rgba(56, 142, 60, 1)` |
`--raml-docs-response-code-color-300` | Color of the 200 status code | `rgba(56, 142, 60, 0.12)` |
`--raml-docs-response-code-color-400` | Color of the 200 status code | `rgba(48, 63, 159, 1)` |
`--raml-docs-response-code-color-500` | Color of the 200 status code | `rgba(48, 63, 159, 0.12)` |
`--raml-docs-response-code-bgcolor-200` | Background color of the 200 status code | `rgba(48, 63, 159, 1)` |
`--raml-docs-response-code-bgcolor-300` | Background color of the 200 status code | `rgba(48, 63, 159, 0.12)` |
`--raml-docs-response-code-bgcolor-400` | Background color of the 200 status code | `rgba(211, 47, 47, 1)` |
`--raml-docs-response-code-bgcolor-500` | Background color of the 200 status code | `rgba(211, 47, 47, 0.12)` |

