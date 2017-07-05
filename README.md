# Tips
My tips. Because I'm lazy to type it again

## Use NVM

Use [nvm](https://github.com/creationix/nvm) to manage node versions.

Quick usuage:

- Install NVM: https://github.com/creationix/nvm#install-script
- Install Node 8: `nvm install 8`
- Alias Node 8 as default `nvm alias default 8`
- Move global packages from one version to another: `// TODO`

## Avoid `sudo` to install global packages

Because it breaks stuff for everyone using it. 
I have no ideas how to configure it manually because I'm using nvm and you should do it too.

## JS Perfs

### Object iterate 

```

```

### Array map 

- DO

![](https://files.slack.com/files-pri/T3NM0NCDC-F647500QJ/screen_shot_2017-07-05_at_9.58.06_am.png)
```js
function map(arr, fn) {
  if (arr == null) {
      return [];
  }

    var i=0, len=arr.length, out=[];

  for (; i < len; i++) {
    out[i] = fn(arr[i], i);
  }

  return out;
}
```

- DON'T

```
Array.prototype.map
```
