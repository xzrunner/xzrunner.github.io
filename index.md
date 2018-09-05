# Struct

* utility

cu, fs, logger, ds, guard, cpputil

* tools

sm, memmgr, tasks, multitask, glp, stat

* assets

camera25, gtxt, polymesh, ps, mtrail, rigging, uniaudio, anim, emitter

* preprocess tools

pimg, texpack

* scene graph

sprite series: sprite2, flatten

node series: node0, node2, node3

entity series: entity0, entity2, entity3

* render

unirender, RapidVG, ShaderLab, dtex2, dtex, cooking, painting0, painting2, painting3, terr, vtex

* serializer

gimg, bs, js, playdb, lexer

sprite series: bimp, timp, simp, s2serializer, s2loader, s2storer

base: serializerx

node series: nserializer

entity series: eserializer

* wrapper

gum, facade, moon

* editor framework

easyeditor, easyeditor0, easyeditor2, easyeditor3

* editor library

eanim, blueprint, shadergraph

* editors

easycomplex, easyanimation, easyscale9, easyone

* game engine and toolchain

runtime, toolchain

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

* [cpputil](https://github.com/xzrunner/cpputil)
Utility for cpp.

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

* [entity0](https://github.com/xzrunner/entity0)
ECS base.

* [entity2](https://github.com/xzrunner/entity2)
ECS 2D scene graph.

* [entity3](https://github.com/xzrunner/entity3)
ECS 3D scene graph.

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

* [painting0](https://github.com/xzrunner/painting0)
Render base.

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

* [eserializer](https://github.com/xzrunner/eserializer)
Entity scene tree's serializer.

* [serializerx](https://github.com/xzrunner/serializerx)
Base for nserializer and eserializer.

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

## Editor library

* [eanim](https://github.com/xzrunner/eanim)
Animation editor library.

* [blueprint](https://github.com/xzrunner/blueprint)
Visual scripting.

* [shadergraph](https://github.com/xzrunner/shadergraph)
Visible shader editor. Front end.

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

## Game engine and toolchain

* [runtime](https://github.com/xzrunner/runtime)

* [toolchain](https://github.com/xzrunner/toolchain)

## Port game

* [quake](https://github.com/xzrunner/quake)
Only support quake1, will include quake3 and doom3 later.

## Demo

* [sample3rd](https://github.com/xzrunner/sample3rd)
Transplant love2d's samples.

## Study project

* [raytracer](https://github.com/xzrunner/raytracer)
Study raytracer from the book "Ray Tracing from the Ground Up".

* [t3d](https://github.com/xzrunner/t3d)
Soft render from the book "Tricks of the 3D Game Programming Gurus".

## Old code

* [sde](https://github.com/xzrunner/sde)
Spatial database engine. Old code during 2008 - 2011

* [doodle_editor](https://github.com/xzrunner/doodle_editor)
Game editor during 2011-2013

# My games

* [Tilt Racing](https://play.google.com/store/apps/details?id=com.zz.thumbracing)

* [Bike Xtreme](https://play.google.com/store/apps/details?id=com.zz.motox)

* [陌陌争霸](https://www.immomogame.com/mmzb)

* [全民英杰传](http://yjz.zisngame.com/)