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

// stb_image::stbi_load([FileManager::path(@"test.png") UTF8String],&w,&h,&bpp,4);
// stb_image::stbi_write_png([path UTF8String],w,h,4,(void const*)dst,w<<2);
```