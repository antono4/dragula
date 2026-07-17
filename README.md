# Dragula

> **Created by Antono**

Drag and drop so simple it hurts.

Browser support includes every sane browser and **IE7+**. Framework support includes vanilla JavaScript, Angular, and React.

## Features

- Super easy to set up
- No bloated dependencies
- **Figures out sort order** on its own
- A shadow where the item would be dropped offers **visual feedback**
- Touch events!
- Seamlessly handles clicks *without any configuration*

## Installation

You can get it on npm:

```shell
npm install dragula --save
```

Or use a CDN:

```shell
<script src='https://cdnjs.cloudflare.com/ajax/libs/dragula/$VERSION/dragula.min.js'></script>
```

## Usage

```javascript
import dragula from 'dragula';

const drake = dragula([document.querySelector('#left'), document.querySelector('#right')]);

drake.on('drop', (el, target, source, sibling) => {
  console.log('Dropped:', el);
});
```

## Framework Support

- Official [Angular bridge](https://github.com/valor-software/ng2-dragula) for dragula
- Official [React bridge](https://github.com/bevacqua/react-dragula) for dragula

## Demo

Try out the [demo](https://bevacqua.github.io/dragula/)!

## License

MIT License

---

> **Created by Antono**
