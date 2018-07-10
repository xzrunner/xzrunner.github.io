# Struct

* utility

cu, fs, logger, ds, guard

* tools

sm, memmgr, tasks, multitask, glp, stat

* assets

camera25, gtxt, polymesh, ps, mtrail, rigging, uniaudio, anim, emitter

* preprocess tools

pimg, texpack

* scene graph

sprite series: sprite2, flatten

node series: node0, node2, node3

* render

unirender, RapidVG, ShaderLab, dtex2, dtex, cooking, painting2, painting3, terr, vtex

* serializer

gimg, bs, js, playdb, lexer

sprite series: bimp, timp, simp, s2serializer, s2loader, s2storer

node series: nserializer

* wrapper

gum, facade, moon

* editor framework

easyeditor, easyeditor0, easyeditor2, easyeditor3

* editors

easycomplex, easyanimation, easyscale9, easyone

* game framework

dustengine

* port game

quake

* demo

sample3rd

# Projects

## Utility

* [cu](https://github.com/xzrunner/cu)
Cpp utility.

* [fs](https://github.com/xzrunner/fs)
Cross-platform file system.

* [logger](https://github.com/xzrunner/logger)
Cross-platform logger system.

* [ds](https://github.com/xzrunner/ds)
Some data struct for C.

* [guard](https://github.com/xzrunner/guard)
Assert and exception for diagnose.

## Toools

* [sm](https://github.com/xzrunner/sm)
Spatial math library.

* [memmgr](https://github.com/xzrunner/memmgr)
Memory allocator.

* [tasks](https://github.com/xzrunner/tasks)
A pthread wrapper.

* [multitask](https://github.com/xzrunner/multitask)
Task scheduling.

* [glp](https://github.com/xzrunner/glp)
Game loop.

* [stat](https://github.com/xzrunner/stat)
Statistic data.

## Assets

* [camera25](https://github.com/xzrunner/camera25)
2.5 camera.

* [gtxt](https://github.com/xzrunner/gtxt)
Text layout and renderer.

* [polymesh](https://github.com/xzrunner/polymesh)
Polygon mesh.

* [ps](https://github.com/xzrunner/ps)
Particle system.

* [mtrail](https://github.com/xzrunner/mtrail)
Motion trail effect.

* [rigging](https://github.com/xzrunner/rigging)
Skeletal animation, support mesh deformation.

* [uniaudio](https://github.com/xzrunner/uniaudio)
An audio api wrapper. Support OpenAL and OpenSLES.

* [anim](https://github.com/xzrunner/anim)
Animation.

* [emitter](https://github.com/xzrunner/emitter)
Emitter cpp wrapper, include p3d, p2d and mtrail.

## Preprocess tools

* [pimg](https://github.com/xzrunner/pimg)
Image preprocessor.

* [texpack](https://github.com/xzrunner/texpack)
Texture packer.

## Scene Graph

* [sprite2](https://github.com/xzrunner/sprite2)
Scene node manager. Node has Symbol, Sprite and Actor 3 levels.

* [flatten](https://github.com/xzrunner/flatten)
Flatten scene node tree, make it faster.

* [node0](https://github.com/xzrunner/node0)
Scene graph base. No inheritance in SceneNode, only use components, simpler than sprite2.

* [node2](https://github.com/xzrunner/node2)
2D scene graph.

* [node3](https://github.com/xzrunner/node3)
3D scene graph.

## Render

* [unirender](https://github.com/xzrunner/unirender)
A renderer api wrapper. Only support opengl now, will support vulkan and metal later.

* [RapidVG](https://github.com/xzrunner/RapidVG)
SVG renderer.

* [ShaderLab](https://github.com/xzrunner/ShaderLab)
Shader manager.

* [dtex2](https://github.com/xzrunner/dtex2)
Merge texture runtimes, decrease render status changes, such as draw call.

* [dtex](https://github.com/xzrunner/dtex)
Old version with c.

* [cooking](https://github.com/xzrunner/cooking)
Use draw list for deferred rendering, used for decrease status changes and multithread rendering.

* [painting2](https://github.com/xzrunner/painting2)
Utility for 2d render.

* [painting3](https://github.com/xzrunner/painting3)
Utility for 3d render3

* [terr](https://github.com/xzrunner/terr)
Terrain render.

* [vtex](https://github.com/xzrunner/vtex)
Virtual texture, clipmap.

## Serializer

* [bimp](https://github.com/xzrunner/bimp)
Old serializer's utility.

* [timp](https://github.com/xzrunner/timp)
Old texture serializer.

* [simp](https://github.com/xzrunner/simp)
Old sprite2 serializer.

* [gimg](https://github.com/xzrunner/gimg)
Image loader and storer.

* [bs](https://github.com/xzrunner/bs)
Utility for binary serialize.

* [js](https://github.com/xzrunner/js)
Utility for json serialize.

* [s2serializer](https://github.com/xzrunner/s2serializer)
Sprite2 serializer. Middle data for sprite2's node.

* [s2loader](https://github.com/xzrunner/s2loader)
Loader for sprite2.

* [s2storer](https://github.com/xzrunner/s2storer)
Storer for sprite2.

* [nserializer](https://github.com/xzrunner/nserializer)
Node scene tree's serializer.

* [playdb](https://github.com/xzrunner/playdb)
A lightweight database, using for assets load and hot update.

* [lexer](https://github.com/xzrunner/lexer)
Used to parse a particular type of text.

## Wrapper

* [gum](https://github.com/xzrunner/gum)
A facade to high level, use sprite2 as scene tree.

* [facade](https://github.com/xzrunner/facade)
A facade to high level, use node as scene tree.

* [moon](https://github.com/xzrunner/moon)
Lua wrapper.

## Editor framework

* [easyeditor](https://github.com/xzrunner/easyeditor/tree/master/easyeditor)
My testbed.

* [easyeditor0](https://github.com/xzrunner/easyeditor0)
Editor famework base.

* [easyeditor2](https://github.com/xzrunner/easyeditor2)
2D editor framework.

* [easyeditor3](https://github.com/xzrunner/easyeditor3)
3D editor framework.

## Editors

### Scene node editors

* [easycomplex](editor/easycomplex/index.md) 
Compose scene nodes.

* [easyanimation](editor/easyanimation/index.md) 
Animation editor.

* [easyscale9](editor/easyscale9/index.md) 
Scale9 editor.

### Level editors

* [sg](https://github.com/xzrunner/easyeditor/tree/master/sg)
[mmzb](https://www.immomogame.com/mmzb) level editor.

* [lr](https://github.com/xzrunner/easyeditor/tree/master/lr)
[lr](http://yjz.zisngame.com/) level editor.

### All in one editor

* [easyone](https://github.com/xzrunner/easyone)
Like Unity and Unreal editor.

## Game famework

* [dustengine](https://github.com/xzrunner/dustengine)

## Port game

* [quake](https://github.com/xzrunner/quake)
Only support quake1, will include quake3 and doom3 later.

## Demo

* [sample3rd](https://github.com/xzrunner/sample3rd)
Transplant love2d's samples.

# My games

* [Tilt Racing](https://play.google.com/store/apps/details?id=com.zz.thumbracing)

* [Bike Xtreme](https://play.google.com/store/apps/details?id=com.zz.motox)

* [陌陌争霸](https://www.immomogame.com/mmzb)

* [全民英杰传](http://yjz.zisngame.com/)