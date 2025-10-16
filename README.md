This is a hermetic test case that ensures zizmor can follow nested annotated Git tags.

In this case, we have:

```
v1.0 -> v1 -> v1.0.0 -> 3fdd4fca8fc76b254cefefca92381c41b28d1f0d
```

...where each of the tags is an annotated tag rather than a lightweight tag.
