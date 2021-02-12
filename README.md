# setup-z

github action to setup [zakuro9715/z](https://github.com/zakuro9715/z)

## Usage

```yaml
steps:
  - uses: actions/cehckout@v2
  - uses: zakuro9715/setup-z@v1
    with:
      version: latest # optional
  - run: z your-task
```
