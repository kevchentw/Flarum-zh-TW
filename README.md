# Flarum-zh-TW
[Flarum](http://flarum.org) 繁體中文/Traditional Chinese Language Pack  

## Insall Flarum 安裝Flarum

### Beta

[Install Guide](http://flarum.org/docs/installation/)

### Development Version

- Install Vagrant and VirtualBox.
- Clone the flarum/flarum repository and set up the Vagrant box:

```
$ git clone --recursive https://github.com/flarum/flarum.git
$ cd flarum
$ vagrant up
```
- Add an entry to your /etc/hosts file: 192.168.29.29 flarum.dev
- Visit flarum.dev in a browser.



## Usage 使用方法

覆蓋原目錄，將全部`tw.yml`重新命名至`en.yml`，重新啟動 Flarum
Move all things into Flarum Folder, rename all `tw.yml` into `en.yml`, restart flarum

## Contributing 貢獻

歡迎所有人讓這個語言包變得更好！若有任何bug，或是要新增語言包，請直接送Pull Request或是送Issue過來！   
Pull request is welcome. If you think want to fix bugs or add more language pack, please feel free to send us pull request or issue!

## Translation 翻譯

#### 核心文字
##### 1.待確認之翻譯

* post -> 貼文
* discussion -> 話題

##### 2.未翻譯之文字

* mod
* activity

## License 授權

Licensed under the [MIT license](http://www.opensource.org/licenses/mit-license.php)


