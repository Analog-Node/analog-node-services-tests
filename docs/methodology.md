# Test Methodology

Analog Node testing is focused on **practical, real-world usability** rather than
formal certification or synthetic benchmarks.

The goal is to determine whether a given piece of hardware or service is suitable
for use in legacy and analog communication scenarios such as BBS operation, fax
transmission, and modem connectivity.

## Guiding Principles

- Tests are performed using real hardware and real network conditions
- Results reflect observed behavior, not vendor claims
- Configuration is kept as simple and realistic as possible
- Repeatability is preferred but not always guaranteed

## Test Environment

Test environments vary and may include:

- SBCs, Mini PCs, and industrial Mini PCs
- Linux-based hosts
- External analog modems and fax machines
- Serial and USB adapters
- Local and remote network connections

Environmental details are documented in individual test reports.

## Test Execution

Tests typically involve:

- Establishing basic functionality
- Running common real-world scenarios
- Observing stability over time
- Noting configuration requirements and limitations

Testing is exploratory and iterative rather than exhaustive.

## Verdict Categories

Each test concludes with a plain-language verdict:

- **Suitable**  
  Works reliably for the intended use case without special workarounds.

- **Limited**  
  Works, but requires configuration tweaks or has notable limitations.

- **Experimental**  
  Functions intermittently or under specific conditions only.

- **Not Suitable**  
  Fails core requirements or is impractical for real-world use.

## Limitations

- Provider behavior and firmware may change over time
- Network conditions vary
- Hardware revisions may differ

Test results represent a snapshot in time and should be interpreted accordingly.
