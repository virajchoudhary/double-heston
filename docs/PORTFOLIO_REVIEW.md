# Double-Heston engineering review

The project began with synthetic inverse calibration and a canonical Fourier
option pricer, then evolved into co-authored Bitcoin surrogate research.
Those phases have different data, evaluation goals, and attribution.

## Personally attributable historical work

Viraj implemented the canonical engine and independent-reference benchmark.
The recorded benchmark passed 36/36 controlled cases at 64 and 96 quadrature
nodes. Those are numerical controlled cases, not live-market validation.

- [Canonical-engine contribution](https://github.com/virajchoudhary/double-heston-inverse-calibration/commit/dea6a19238e13fccf5243935ffb6df8199135595).
- [Independent-reference contribution](https://github.com/virajchoudhary/double-heston-inverse-calibration/commit/47773b8a6ca7b35ce8fcf32db35b054f7aa20158).
- [`INDEPENDENT_PRICING_BENCHMARK.md`](INDEPENDENT_PRICING_BENCHMARK.md) defines the reference and case set.
- [`R2_PRIMARY_COMPARISON_RESULTS.md`](R2_PRIMARY_COMPARISON_RESULTS.md) reports the earlier synthetic comparison.

Close repricing did not establish reliable recovery of the model's ten
parameters. Practical non-identifiability is a research result, not a defect
to hide. The current main README links a later regular-PINN assessment, but its
historical G2 freeze/status paragraphs conflict. Use
[research control and current status](RESEARCH_CONTROL_AND_CURRENT_STATUS.md)
and experiment-specific handoffs rather than interpreting those paragraphs as
the current protocol.

## Evolved team research

The same academic project evolved into a physics-informed Bitcoin option-pricing
surrogate study across retrospective volatility episodes.
Current manuscript co-authorship is separate from implementation ownership.
Viraj's historical engine contribution does not imply personal ownership of
new PINN training, Bitcoin scoring, or conditional findings.

Public main is an older inverse-calibration snapshot. Detailed current manuscript
results are not reproduced here, and no paper PDF is attached. Current research
does not imply acceptance or publication.

Fixed literature-shaped parameters and retrospective evaluation do not establish
Bitcoin market calibration, universal two-factor superiority, a confirmatory
forecasting test, profitability, or a deployable trading signal.
Numerical surrogate fidelity must remain distinct from error against market prices.

## Source and setup

The implementation uses Python, a Fourier numerical reference, ANN and PyTorch
surrogate components, and experiment manifests. Use the
[current main research instructions](../README.md) and their linked handoffs
before any historical evaluator. Different experiments require different
dependencies and checkpoints.

Recorded historical software checks and benchmark results are not freshly
replayed in this portfolio review. Do not start training, acquire market data,
or publish manuscript material merely to verify presentation.
