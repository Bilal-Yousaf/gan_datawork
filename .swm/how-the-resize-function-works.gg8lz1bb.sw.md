---
title: How the resize function works
---
<SwmSnippet path="/transformations.py" line="4">

---

This function takes three arguments:

- img: (np.ndarray): Image to be resized
- size (tuple or int): Desired output size. If size is a sequence like
- interpolation (str, optional): Desired interpolation. Default is BILINEAR

And returns a resized image (np.ndarray).

```python
def resize(img, size, interpolation='BILINEAR'):
```

---

</SwmSnippet>

<SwmToken path="/transformations.py" pos="4:7:7" line-data="def resize(img, size, interpolation=&#39;BILINEAR&#39;):">`size`</SwmToken> must be an int, otherwise code can have unknown behavior

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBZ2FuX2RhdGF3b3JrJTNBJTNBQmlsYWwtWW91c2Fm" repo-name="gan_datawork"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
