#### lauarwithes6

24
```
npm install -g webpack babel-loader
```
create webpack.config.js
```
module.exports={
entry:'./script.js',
output:{filename:'bundle.js'},
module:{
loaders:[
{test:/\.js?/,loader:'bable-loader',exclude:/node_modules/}
]
}
};
```
run
```
webpack
```
