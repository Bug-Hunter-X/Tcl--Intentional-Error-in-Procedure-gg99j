# Tcl Bug: Intentional Error Demonstration

This repository demonstrates a common but easily overlooked error in Tcl: improper error handling in procedures.

The `bug.tcl` file contains a procedure (`buggyProc`) that intentionally throws an error using the `error` command.  This can lead to unexpected program termination if not caught and handled gracefully.

The `bugSolution.tcl` file shows a corrected version with proper error handling using `try...catch`.

This example highlights the importance of robust error handling in Tcl applications to prevent crashes and improve stability.
