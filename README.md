# wiedem GitHub Pages

## DVESecurity
The documentation for the [main](https://wiedem.github.io/dvesecurity-apple/main/documentation/dvesecurity/) and [develop](https://wiedem.github.io/dvesecurity-apple/develop/documentation/dvesecurity/) branches of the [DVESecurity](https://github.com/wiedem/dvesecurity-apple) package are generated with the `swift package` command.

```bash
swift package --allow-writing-to-directory [path-to-docs-directory] \
    generate-documentation --target DVESecurity \
    --disable-indexing \
    --transform-for-static-hosting \
    --hosting-base-path "dvesecurity-apple/develop" \
    --output-path [path-to-docs-directory]
```

```bash
swift package --allow-writing-to-directory [path-to-docs-directory] \
    generate-documentation --target DVESecurity \
    --disable-indexing \
    --transform-for-static-hosting \
    --hosting-base-path "dvesecurity-apple/main" \
    --output-path [path-to-docs-directory]
```

See [Generating the Documentation Site] for further details on how to generate the documentation site.

[DocC Main Branch]: https://wiedem.github.io/dvesecurity-apple/main/documentation/dvesecurity/
[DocC Develop Branch]: https://wiedem.github.io/dvesecurity-apple/develop/documentation/dvesecurity/
[Generating the Documentation Site]: https://apple.github.io/swift-docc-plugin/documentation/swiftdoccplugin/publishing-to-github-pages/#Generating-the-Documentation-Site


