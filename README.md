# gwbenchmark-containers

Container images for generating GWBenchmark datasets.

- `2g` (`Dockerfile.2g`): generates the 2g datasets.
- `2g-pe` (`Dockerfile.2g-pe`): runs the 2g reference posteriors with
  bilby_pipe. It is the `2g` image plus bilby_pipe, with numpy lowered to
  2.3.5 and every package pinned in `constraints-2g-pe.txt`.
