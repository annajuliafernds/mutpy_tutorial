# MutPy Tutorial

Este projeto contém um exemplo simples de teste de mutação usando o MutPy.

mut.py --target calculator --unit-test test_calculator --report-html report

[*] Start mutation process:
   - targets: calculator
   - tests: test_calculator
[*] 4 tests passed:
   - test_calculator [0.00022 s]
[*] Start mutants generation and execution:
   - [#   1] AOR calculator: [0.00440 s] killed by test_add (test_calculator.TestCalculator.test_add)
   - [#   2] AOR calculator: [0.00348 s] killed by test_subtract (test_calculator.TestCalculator.test_subtract)
   - [#   3] AOR calculator: [0.00380 s] killed by test_multiply (test_calculator.TestCalculator.test_multiply)
   - [#   4] AOR calculator: [0.00429 s] killed by test_multiply (test_calculator.TestCalculator.test_multiply)
   - [#   5] AOR calculator: [0.00603 s] killed by test_multiply (test_calculator.TestCalculator.test_multiply)
   - [#   6] AOR calculator: [0.00435 s] killed by test_divide (test_calculator.TestCalculator.test_divide)
   - [#   7] AOR calculator: [0.00423 s] killed by test_divide (test_calculator.TestCalculator.test_divide)
   - [#   8] COI calculator: [0.00358 s] killed by test_divide (test_calculator.TestCalculator.test_divide)
   - [#   9] ROR calculator: [0.00568 s] killed by test_divide (test_calculator.TestCalculator.test_divide)
[*] Mutation score [0.11116 s]: 100.0%
   - all: 9
   - killed: 9 (100.0%)
   - survived: 0 (0.0%)
   - incompetent: 0 (0.0%)
   - timeout: 0 (0.0%)
