```
double then = CFAbsoluteTimeGetCurrent();
NSLog(@"%f",CFAbsoluteTimeGetCurrent()-then);
```

```
#define STB_IMAGE_WRITE_IMPLEMENTATION
#define STB_IMAGE_IMPLEMENTATION
#define STBI_ONLY_PNG
namespace stb_image {
    #import "stb_image.h"
    #import "stb_image_write.h"
}
#endif

// stb_image::stbi_load("src.png",&w,&h,&bpp,4);
// stb_image::stbi_write_png("dst.png",w,h,4,(void const*)dst,w<<2);
```

```
dispatch_group_t _group = dispatch_group_create();
dispatch_queue_t _queue = dispatch_get_global_queue(DISPATCH_QUEUE_PRIORITY_HIGH,0);
                
dispatch_group_async(_group,_queue,^{
});

dispatch_group_wait(_group,DISPATCH_TIME_FOREVER);]
```
