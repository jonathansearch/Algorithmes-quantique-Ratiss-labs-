# Local Audit Report — Algorithmes-quantique-Ratiss-labs-

> Scope: local clone only. No remote repository was modified and no push was performed.

## Repository Structure

| Check | Result |
|---|---|
| Tracked/local file count | 46 |
| Python file count | 9 |
| README | PASS |
| RATISS Labs logo (`docs/assets/logo.png`) | PASS |
| Apache 2.0 LICENSE | PASS |
| `CITATION.cff` | PASS |

## Test Validation

- Command: `python3 -m pytest -v`
- Exit status: `0`

```text
============================= test session starts ==============================
platform linux -- Python 3.12.3, pytest-9.1.1, pluggy-1.6.0 -- /usr/bin/python3
cachedir: .pytest_cache
rootdir: /home/ubuntu/ratiss-labs-repos/Algorithmes-quantique-Ratiss-labs-
configfile: pyproject.toml
plugins: anyio-4.14.2
collecting ... collected 8 items

tests/test_documentation_contract.py::test_grover_artifact_preserves_raw_stage_outputs_and_dynamic_sidecar PASSED [ 12%]
tests/test_documentation_contract.py::test_grover_documentation_figures_exist PASSED [ 25%]
tests/test_documentation_contract.py::test_grover_qpu_validation_artifact_is_real_hardware_with_traceable_jobs SKIPPED [ 37%]
tests/test_documentation_contract.py::test_reality_mode_keeps_fake_backend_scope_and_separate_sensitivity_flag PASSED [ 50%]
tests/test_grover_ratiss.py::test_grover_circuit_has_three_qubits_and_measurements PASSED [ 62%]
tests/test_grover_ratiss.py::test_marked_mass_uses_raw_counts PASSED     [ 75%]
tests/test_grover_reality_mode.py::test_reality_flag_uses_observed_divergence_without_ground_truth_noise PASSED [ 87%]
tests/test_grover_reality_mode.py::test_reality_profile_declares_offline_fake_backend_scope PASSED [100%]

========================= 7 passed, 1 skipped in 0.53s =========================

```

## Compliance Notes

- Branding and common repository metadata were applied locally.
- Scientific claims were not upgraded from proxy evidence to full validation.
- The three required technical Bible documents were not present in the supplied workspace.
- This report is an engineering audit snapshot, not a claim of zero defects.
