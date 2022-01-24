# Quick Reference
### C++
```cpp
prim.SetMetadata(pxr::SdfFieldKeys->Comment, "I am a comment");
```


### Python
```python
prim.SetMetadata("comment", "I am a comment")
```


### USD
```usda
#usda 1.0
(
    doc = "This is an example of adding a comment. You can add comments inside any pair of ()s"
)

def Sphere "SomeSphere" (
    "I am a comment"
)
{
}
```
