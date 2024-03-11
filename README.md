# corcojs-qrcode-logo

Typescript React component to generate a customizable QR Code.

## Installation

```bash
npm install --save corcojs-qrcode-logo
```
## Usage

```javascript
import * as React from 'react';
import { QRCode } from 'corcojs-qrcode-logo';

React.render(
  <QRCode value="https://github.com/gcoro/corcojs-qrcode-logo" />,
  mountNode
);
```