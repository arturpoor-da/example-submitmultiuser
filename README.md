Short example to demonstrate `submitMulti` capability through users in Daml.

Compile with

```
daml build
```

Run with 
```
daml sandbox --dar .daml/dist/submitmulti-0.0.1.dar
```
in one terminal and
```
daml script --script-name Main:main --dar .daml/dist/submitmulti-0.0.1.dar --ledger-host localhost --ledger-port 6865
```
in another.
