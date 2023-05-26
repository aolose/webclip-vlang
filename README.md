# online webClip
[Demo](https://ivi.cx)

### build from source
- `git clone https://github.com/aolose/webclip-vlang.git`
- `v .`


### run
generate unsigned webClip file
```
./webclip-vlang
```

generate signed webClip file
```
./webclip-vlang -c xxx.crt -k xxx.key -a chain.pem -p 7001
```
open `http://127.0.0.1:7001`
