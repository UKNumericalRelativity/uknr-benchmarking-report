# UKNR Benchmarking Report

LaTeX source for the [UK Numerical Relativity (UKNR)](https://www.uknumericalrelativity.org/)
Collaboration's report *Numerical Relativity Code Assessment*, which
presents strong-scaling and profiling benchmarks of numerical relativity codes
(including the Einstein Toolkit, GRChombo/GRTeclyn, MHDuet, and BAM) on UK
supercomputing facilities such as COSMA8 and Tursa.

The report accompanies the main
[uknr-benchmarking](https://github.com/UKNumericalRelativity/uknr-benchmarking)
repository, which contains the benchmark harness, scripts, and raw data used to
produce the figures in this report.

## Building

Compile with `latexmk` (uses BibLaTeX):

```sh
latexmk -pdf main.tex
```

This produces `main.pdf`. The required figures are included in `figures/`.

## License

This report is licensed under the Creative Commons Attribution 4.0 International
License (CC-BY 4.0); see [LICENSE](LICENSE).
