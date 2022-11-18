# gomapinfer

add Microsoft Bing Map API  

because [rtreego](https://github.com/dhconnelly/rtreego) change its api [rtreego.Rect* to rtreego.Rect](https://github.com/dhconnelly/rtreego/commit/2008b37524910b3e54046f1f7b12139316a0461d), so the [orginal repository](https://github.com/mitroadmaps/gomapinfer) will get an error `*edgeSpatial does not implement rtreego.Spatial (wrong type for Bounds method)`. You can use IronSublimate/gomapinfer instead of mitroadmaps/gomapinfer  

You can `go get` like this:

    go get github.com/IronSublimate/gomapinfer/bingmaps
