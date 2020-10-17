## My resume

POC a tool like https://jsonresume.org/ for maintaining my resume.

pdf generation:

```
npm run pdf
```

html generation:

```
npm run html
```

### My conclusion so far

- Some fields like "summary" are inherently multi-line in nature. JSON makes it difficult to write long text, which is present in most resumes.
- The pdf / html generation is great
- Lots of good themes

### Wishlist

- Using markdown format instead to write the resume, this would make it easily maintainable from a CMS like [forestry](https://forestry.io/)
