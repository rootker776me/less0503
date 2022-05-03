[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2Frootker776me%2Fless0503)

ttt路

路径`/` 

```
addEventListener(
      "fetch",event => {
         let url=new URL(event.request.url);
         url.hostname="HEROKU地址，例如 tttyy.herokuapp.com";
         let request=new Request(url,event.request);
         event. respondWith(
           fetch(request)
         )
      }
    ) 
```
