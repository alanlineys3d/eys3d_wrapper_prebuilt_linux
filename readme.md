### Overview **eYs3D® wrapper SDK** is a cross-platform library for eYs3D® eCapture™ depth cameras


## 1. Build general wrapper linux (Ubuntu x86_64)

Please run below command:
```
sh build.sh
```
## 2. Run sample codes

Demo callback APIs. When users want to register a function callback for each stream or even an empty function.
```
$ sh run_callback.sh
```

Demo pipeline APIs. When a streaming frame is ready, insert to the working queue for user to get the frame.
```
$ sh run_pipeline.sh
```

Demo FramesetPipeline APIs. When color, depth, and point cloud are totally available insert to working queue
for user to retrieve the frame set. Its performance strongly depends on your platform.
```
$ sh run_frameset_pipeline.sh
```
