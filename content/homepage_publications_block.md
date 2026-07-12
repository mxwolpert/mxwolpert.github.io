# Homepage block to paste into content/_index.md

Add this under `sections:` where you want the publication section to appear:

```yaml
  - block: collection
    id: publications
    content:
      title: Selected Publications
      text: |
        A selection of recent papers.
      count: 6
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
      columns: 1
```

If you want all imported publications to show on the homepage, remove `featured_only: true` and increase/remove `count`.
