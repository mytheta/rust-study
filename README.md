# RUSTの勉強リポジトリ

## how to install rust in Mac ???????
```
$ curl https://sh.rustup.rs -sSf | sh
```
`Rust is installed now. Great!` みたいなのが出るはず．

```
$ source $HOME/.cargo/env
$ rustc --version
rustc 1.34.1 (fc50f328b 2019-04-24)
```

で完了．

## 実行方法
```
$ rustc main.rs
$ ./main
```