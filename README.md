###Convert sketch to iconfont
> forked from https://github.com/cognitom/symbols-for-sketch

####How to Use
1. clone this to your workspace and `cd your-workspace/symbols-for-sketch`
2. `$ npm install`
3. copy your sketch to folder `/sketch`, note the sketch file must use the `symbol-font-14px.sketch` or `symbol-font-16px.sketch` as template
4. use `$ npm run symbols` to generate font file
5. checkout `/dist`

####Tips
- use `$ npm run symbols watch` can watch sketch file's change and show them in browser in real-time, you must try it while you change your sketch file frequently。
- edit `gulpfile.js` if you wanne change the font file name or iconfont class name