# record

##  contents
>in branches

### 【v1】:(copied,not new)`format of module`(ex:success of `get-github-activity-feed`)
- Version v1-1---var getGithubData = require('./index.js')
- Version v1-2---var getGithubData = module.exports  [output](https://i.imgur.com/YM68AaQ.png)


> key point:
>```
>var getGithubData = require('./index.js')
>```     
>=
>```
>    <script> var module = {} </script>
>    <script src="index.js"></script>
>    
>    var getGithubData = module.exports
>```  


