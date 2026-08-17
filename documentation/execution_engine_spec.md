# Code Execution & Judge0 Sandbox Specification

## Judge0 CE Architecture
- Containerized code runner isolated with Linux cgroups and seccomp profiles
- Multi-language compilation and execution support:
  - C++ (GCC 9.2+)
  - Java (OpenJDK 13+)
  - Python (Python 3.8+)
  - JavaScript (Node.js 12+)
- Per-test-case validation:
  - Time Limit Exceeded (TLE) enforcement (default: 2.0s)
  - Memory Limit Exceeded (MLE) enforcement (default: 128MB)
  - Compile Error (CE) extraction and output formatting
  - Wrong Answer (WA) diff comparison with whitespace trimming
  - Accepted (AC) confirmation across all test cases

### Revision Log
- 2026-08-17: Execution engine NFRs and Judge0 spec drafted by Harshvardhan Sarvaiya.

- 2026-08-17: Sandbox isolation constraints detailed by Harshvardhan Sarvaiya.
