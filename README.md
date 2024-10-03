# Archived and moved
## Please go to: https://github.com/paketo-buildpacks/builder-jammy-java-tiny

### Paketo Jammy Java Tiny Builder

#### `paketobuildpacks/builder-jammy-java-tiny`

This builder uses the [Paketo Jammy Tiny
Stack](https://github.com/paketo-buildpacks/jammy-tiny-stack) (Ubuntu Jammy
Jellyfish build image, distroless-like run image) and contains 
***only Java composite buildpacks**. To use this builder, 
you must specify buildpacks at build
time using whatever mechanisms your CNB platform of choice offers.

For example, with the `pack` CLI, use `--buildpack` as follows:
```
pack build great-java-app \
    --builder paketobuildpacks/builder-jammy-java-tiny:latest
```

To see which versions of build and run images and the lifecycle are in a given
builder version, see the
[Releases](https://github.com/paketo-buildpacks/builder-jammy-java-tiny/releases)
on this repository. This information is also available in the `builder.toml`.

For more information about this builder and how to use it, visit the [Paketo
builder documentation](https://paketo.io/docs/builders/).  To learn about the
stack included in this builder, visit the [Paketo stack
documentation](https://paketo.io/docs/stacks/) and the [Paketo Jammy Tiny Stack
repo](https://github.com/paketo-buildpacks/jammy-tiny-stack).
