# Batch export [Wavefront .obj files](https://en.wikipedia.org/wiki/Wavefront_.obj_file)

A tiny add-on for Blender that allows to export multiple scene objects at once and comes with the usual settings.

<img width="522" alt="j1tkH" src="https://github.com/p2or/blender-batch-export-wavefront-obj/assets/512368/80ef69a0-e759-4fe8-b13c-18470983efd0">

### Background

This repository has emerged from [Export multiple objects to .obj](https://blender.stackexchange.com/q/5382/3710) to keep track of all the changes over the years and having all downloads in one place. The add-on itself is basically just a wrapper of [`wm.obj_export`](https://docs.blender.org/api/current/bpy.ops.wm.html?highlight=obj_import#bpy.ops.wm.obj_export) or [`export_scene.obj`](https://docs.blender.org/api/blender_python_api_2_74_5/bpy.ops.export_scene.html?highlight=import_scene.obj#bpy.ops.export_scene.obj) operator in versions prior to Blender `3.3.0` until exporting multiple .obj files is officially supported.

## Versions

| Blender/Branch | Latest Version | Release | 
| :------ | :--- | :------ |
| [Blender 2.74+](../../tree/Blender-2.74+)    | 0.1.0 | [Download](../../releases/download/0.1.0/io_batch_export_objs.py) |
| [Blender 2.80+](../../tree/Blender-2.80+)    | 0.2.0 | [Download](../../releases/download/0.2.0/io_batch_export_objs.py) |
| [Blender 3.1+](../../tree/Blender-3.1+)      | 0.3.0 | [Download](../../releases/download/0.3.0/io_batch_export_objs.py) |
| [Blender 3.3+](../../tree/Blender-3.3+)      | 0.4.0 | [Download](../../releases/download/0.4.0/io_batch_export_objs.py) |
| [Blender 3.6+](../../tree/Blender-3.6+)      | 0.5.0 | [Download](../../releases/download/0.5.0/io_batch_export_objs.py) |


## Installation

1. Download the correct [release version of the add-on](#Versions) to match your version of Blender
1. In Blender open up *Preferences > Addons*
1. Click *Install*, select `io_batch_export_objs.py` and activate the add-on

----

Might also be of interest: [Batch import Wavefront .obj files](https://github.com/p2or/blender-batch-import-wavefront-obj)
