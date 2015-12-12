# iptables dsl

Bash DSL for generating iptables configuration

iptables-dsl is a set of bash functions which let you write a script
outpitting iptables config fit for `iptables-restore`.

Using it you can simplify the ruleset and even split it to several
files. No more adding rules at specific index you need to count! Just
regenerate the ruleset and use `iptables-apply` to test & apply it.

