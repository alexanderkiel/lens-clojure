# Lens Clojure

Docker container containing common Libs for Lens. Projects use this container instead of `clojure:lein-2.5.3` with the benefit that many libs are already in the local Maven repository. Having the libs already cached saves additional Docker image layers foreach individual container.

## Usage

In your `Dockerfile`:

```
FROM lens-clojure:0.1
```

## License

Copyright © 2016 Alexander Kiel

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
