# Methodology

## Test Approach

The model was tested with progressively larger context inputs.
The same question was asked repeatedly while only the amount of
irrelevant filler text was changed.

## Key Rule

Only ONE variable was changed per test:
- Context size

The rules and questions were kept constant.

## Evaluation Criteria
- Did the model use only the provided context?
- Did it follow explicit rules?
- Did it hallucinate or ignore constraints?
- Did answers change as context grew?

No token counting was performed.
Accuracy was evaluated qualitatively.