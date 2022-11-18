# gomapinfer

add Microsoft Bing Map API  

because [rtreego](https://github.com/dhconnelly/rtreego) change its api rtreego.Rect* to rtreego.Rect, so the [orginal repository](https://github.com/mitroadmaps/gomapinfer) will get an error `*edgeSpatial does not implement rtreego.Spatial (wrong type for Bounds method)`. You can use IronSublimate/gomapinfer instead of mitroadmaps/gomapinfer  

You can `go get` like this:

    go get github.com/IronSublimate/gomapinfer/bingmaps
