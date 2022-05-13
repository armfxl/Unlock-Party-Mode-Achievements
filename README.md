- [Video Tutorial](https://www.youtube.com/watch?v=l5em6TEtkJk)

### Console command
```js
const fModule = (item) => window.webpackChunkdiscord_app.push([
    [Math.random()], {}, (req) => {
        for (const m of Object.keys(req.c).map((x) => req.c[x].exports).filter((x) => x)) {
            if (m && m[item] !== undefined) return m;
        }
    }
]);
const tak2 = fModule("getPoggermodeAchievementData");

for (let [key, val] of Object.entries(tak2.PoggermodeAchievementId)) {
    fModule("unlockAchievement").unlockAchievement(val)
}
```

### settings.json option
```js
"DANGEROUS_ENABLE_DEVTOOLS_ONLY_ENABLE_IF_YOU_KNOW_WHAT_YOURE_DOING": true
```
