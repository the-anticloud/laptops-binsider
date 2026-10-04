# Technical Whitepaper — BINSIDER

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/orhun/binsider
**Category:** LAPTOPS

## Abstract

This whitepaper describes the Anticloud integration of `BINSIDER` (Binary inspector for laptops/embedded)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local AI assistant running offline on consumer hardware
2. AIOSS secure boot measurement chain (TPM2-backed)
3. AES-256 full-disk encryption with AIOSS key audit log
4. Single-binary power management and system optimizer
5. Zero-cloud: all AI features work without internet
6. GPU/CPU equalizer: routes inference to discrete GPU when present, CPU otherwise
7. Zero-telemetry: removes all OEM telemetry and Microsoft/Apple cloud sync defaults
8. Open firmware integration: coreboot/UEFI compatibility layer

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.