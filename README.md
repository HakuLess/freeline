# Freeline
![Freeline](http://ww4.sinaimg.cn/large/006tNc79gw1f6ooza8pkuj30h804gjrk.jpg)

从Freeline官方fork而来，二次开发增加部分自己需要的功能~

## ChangeLog
* 2017-12-25 子module支持flavor（当前0.8.8官方版本暂不支持） [博客文章](http://hakuless.github.io/2017/12/25/Freeline%E4%BF%AE%E6%94%B9%E7%AC%94%E8%AE%B0/)

## Sample Usage
````
git clone git@github.com:HakuLess/freeline.git
cd freeline
./gradlew install

Then do with your own project

cd your own project
./gradlew initFreeline -Pmirror(Needed for module flavor)
````

## TODO
- Kotlin支持

## Thanks
- [Instant Run](https://developer.android.com/studio/run/index.html#instant-run)
- [Buck](https://github.com/facebook/buck)
- [LayoutCast](https://github.com/mmin18/LayoutCast)
- [Freeline](https://github.com/alibaba/freeline)

## License
BSD3 License







