# hyper-tabs-enhanced [![npm](https://img.shields.io/npm/v/hyper-tabs-enhanced.svg?maxAge=86400?style=flat-square)](https://www.npmjs.com/package/hyper-tabs-enhanced) [![npm](https://img.shields.io/npm/dm/hyper-tabs-enhanced.svg?maxAge=86400?style=flat-square)](https://www.npmjs.com/package/hyper-tabs-enhanced)

> Enhanced Tabs Plugin for [Hyper](https://hyper.is). Matches any theme.

![](screen.png)


## Install

Add following to your `~/.hyper.js` config.

```javascript
module.exports = {
  ...
  plugins: ['hyper-tabs-enhanced']
  ...
}
```


## Config

Add following to `~/.hyper.js`.

### Enable Border
![](screen_border.png)

Default value is `false`

```javascript
module.exports = {
  config: {
    ...
      hyperTabs: {
        border: true,
      }
    ...
  }
}
```

### Disable Tab Icons
![](screen_icons.png)
Default value is `true`

```javascript
module.exports = {
  config: {
    ...
      hyperTabs: {
        tabIcons: false,
      }
    ...
  }
}
```

### Enable Colored Tab Icons
![](screen_colored.png)
Default value is `false`

```javascript
module.exports = {
  config: {
    ...
      hyperTabs: {
        tabIconsColored: true,
      }
    ...
  }
}
```

### Change Activity Color
Expected value is `CSS colors`

```javascript
module.exports = {
  config: {
    ...
      hyperTabs: {
        activityColor: 'salmon',
      }
    ...
  }
}
```

### Disable Activity Pulse
Default value is `true`

```javascript
module.exports = {
  config: {
    ...
      hyperTabs: {
        activityPulse: false,
      }
    ...
  }
}
```


## Recommended Themes

* [hyper-chesterish](https://github.com/henrikdahl/hyper-chesterish)
* [hyper-oceans16](https://github.com/henrikdahl/hyper-oceans16)
* [hyper-hybrid-theme](https://github.com/alexfedoseev/hyper-hybrid-theme)


## License

MIT © Henrik
