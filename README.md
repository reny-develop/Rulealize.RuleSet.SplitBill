# Rulealize.RuleSet.SplitBill

Who paid for what on a trip or a night out, and what each one pays or gets back when the total is shared equally. A [Rulealize](https://github.com/reny-develop/Rulealize) rule set.

| | |
| --- | --- |
| Rule set id | `Rulealize.RuleSet.SplitBill` |
| Package | [`Rulealize.RuleSet.SplitBill`](https://www.nuget.org/packages/Rulealize.RuleSet.SplitBill) |
| Inputs | `join`, `pay`, `rename`, `leave`, `clear`, `undo` |
| Holds | nothing |
| Draws on | TypeSchema, State, Sequence, Record, Comparison, Logic, Arithmetic, Branch, Binding, Definition |

People are added, renamed and removed; a payment is recorded as who paid, for what and how much, and the last one can be taken back. Removing someone takes what they paid with them, and renaming keeps it.

## Opening it

[Rulpane](https://github.com/reny-develop/Rulpane) opens it from the
[Rulealize Registry](https://github.com/reny-develop/Rulealize.Registry) by its identifier and
version: `#r=Rulealize.RuleSet.SplitBill@1.0.0`.

## License

[Apache-2.0](LICENSE).
