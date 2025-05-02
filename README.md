Here is a list of descriptive Git commits that chronologically capture the development and refinement of the project:

Initial commit: basic log monitor structure
Set up core Python script with log parsing, processing, and reporting logic.

Add log file parser for timestamp, description, status, and PID
Implemented CSV parsing and datetime conversion for log entries.

Add log processing to compute durations and severity levels
Calculates task duration and classifies them as INFO, WARNING, or ERROR.

Add report output formatting with duration display
Outputs severity level, PID, description, and duration in human-readable form.

Add basic unit tests for parse_time and process_logs functions
Validates correct time parsing and log processing for typical inputs.

Add edge case tests for missing START/END, duplicates, invalid times
Improves test coverage to handle log inconsistencies and anomalies.

Organize project structure with src, tests, and docs directories
Adds modular folder layout for better maintainability.

Add README documentation with usage, thresholds, and test instructions
Provides an overview of the tool, how to run it, and test setup.

Include sample logs.log file for testing and demonstration
Adds real-world log entries to validate and demo the monitor functionality.
