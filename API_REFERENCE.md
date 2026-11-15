# API reference

The package keeps terminal side effects behind four explicit host externs. `ioPrint` and `ioPrintLine` enforce a 1 MiB input bound before forwarding. Status and color helpers are deterministic and portable; ANSI policy belongs to the host.

