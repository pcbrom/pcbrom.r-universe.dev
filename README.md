# pcbrom.r-universe.dev

The R-universe of Pedro Carvalho Brom. Packages listed in `packages.json`
are built and served at <https://pcbrom.r-universe.dev>.

- `gpumetropolis`: a generic GPU-portable, vendor-agnostic Metropolis-Hastings
  sampler. Distributed here rather than on CRAN because its vendored Rust
  dependency tree, the CUDA and Vulkan stacks, exceeds the CRAN tarball-size
  limit.
