# Saltmarsh Sampler Mk-I

Controller firmware and sample-log utilities for the Mk-I intertidal pore-water
sampler.

## Release status

**Released - v2.0.1 (2025-10-08).**  The sampler controller and the log parser
are feature-complete and have been used in two intertidal campaigns.  The
`data/site_registry.yaml` file lists the plots used by the released build.

## Layout

- `src/sampler_control.py` - syringe rack sequencing and sleep scheduling
- `src/sample_log.py` - binary log reader
- `data/site_registry.yaml` - plot registry
- `experiments/intertidal_survey.md` - field campaign notes
