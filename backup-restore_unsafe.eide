#! VULNERABLE backup-restore — feeds the untrusted input straight to the tool, no extraction.
#! check -> UNSAFE: tainted data cannot reach a capability.
grant perform irreversible

let raw = fetch<web>
commit { perform(raw) }  # tainted -> tool: REJECTED
