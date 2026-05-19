# use_case5_code_comment

## Purpose
Demonstrates prompt injection placed inside source-code comments.

## Example Injection
$(System.Collections.Hashtable.Example)

## Risk Note
Medium risk because comments look harmless but can still affect downstream tools.

## Files
- Program.cs prints the scenario summary and calculated risk score.
- Calculator.cs defines the scenario model and the scoring logic.
- CalculatorTests.cs contains simple validation helpers for the scenario.
