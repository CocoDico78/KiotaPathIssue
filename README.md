# KiotaPathIssue

Repository to reproduce issue when a path appears twice in a row with Kiota 1.15.0

To reproduce

```pwsh
cd ClassLibrary1
kiota generate -l CSharp -d ./definition_works.json -o ./ClientWorks
kiota generate -l CSharp -d ./definition_problematic.json -o ./ClientProblematic
```
