# EMOJIQUERY

This minimal JQuery library add the ability to transform any emoji string into the corresponding image

## How to use this library

Just select which portion of the of your html you want to transform and apply the emojify method (you must provide the path where the emoji are stored):

```javascript
$('.my-selector').emojify({emoji_dir: "http://my-path-to/emoji"});
```

### Options

The available options are:

* **emoji_dir:** location of your emoji (http://localhost/images/emoji default).
* **width:** width of the image (64px default).
* **height:** height of the image (64px default).

```javascript
$(.my-selector').emojify({
  width: '24px',
  height: '24px',
  emoji_dir: 'http://my-path-to/emoji'
});
```

## Feedback and Issues

If you find any issue, please [report it](/issues). Also you can improve the code and create a pull request.
