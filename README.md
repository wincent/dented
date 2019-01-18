# Dented

[![NPM version](https://badge.fury.io/js/dented.svg)](http://badge.fury.io/js/dented)

```javascript
import {dedent, indent} from 'dented';

const dedented = dedent`
  <something>
    nested
  </something>
`;

const indented = indent(dedented, 8);
```
