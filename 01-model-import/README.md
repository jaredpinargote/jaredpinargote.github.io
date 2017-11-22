# Importing Models

A-frame makes it incredibly easy to import models into your scene!

From their [documentation][doc] you can see how to do this:

We can load an .OBJ model by pointing to assets that specify the path to an .OBJ and .MTL file.

```html
<a-scene>
  <a-assets>
    <a-asset-item id="tree-obj" src="/path/to/tree.obj"></a-asset-item>
    <a-asset-item id="tree-mtl" src="/path/to/tree.mtl"></a-asset-item>
  </a-assets>

  <a-entity obj-model="obj: #tree-obj; mtl: #tree-mtl"></a-entity>
</a-scene>
```
[doc]: https://github.com/aframevr/aframe/blob/master/docs/components/obj-model.md