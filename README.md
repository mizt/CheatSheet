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

// (unsigned int *)stb_image::stbi_load("src.png",info,info+1,info+2,4);
// stb_image::stbi_write_png("dst.png",w,h,4,(void const*)dst,w<<2);
```

```
dispatch_group_t _group = dispatch_group_create();
dispatch_queue_t _queue = dispatch_get_global_queue(DISPATCH_QUEUE_PRIORITY_HIGH,0); 
dispatch_group_async(_group,_queue,^{
});
dispatch_group_wait(_group,DISPATCH_TIME_FOREVER);
```

```
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
	</head>
	<body>
		<script async src="https://unpkg.com/es-module-shims@1.6.3/dist/es-module-shims.js"></script>
		<script type="importmap">
			{
				"imports": {
					"three":"https://unpkg.com/three@0.164.1/build/three.module.js",
					"three/addons/":"https://unpkg.com/three@0.164.1/examples/jsm/"
				}
			}
		</script>
		<script type="module">
			
			import * as THREE from "three"
			
		</script>
	</body>
</html>
```
