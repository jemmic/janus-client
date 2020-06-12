# Janus Client

Janus client with TypeScript support. Works for every plugins. WebRTC depency included.

## Installation

`npm install janus-client`
or
`yarn add janus-client`

## Usage

```
import Janus from 'janus-client';

Janus.init({
    callback: () => {
        const janus = new Janus(...options);
    },
});
```