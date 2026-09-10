# QuickGrid Query Parameter Names Validation

This repository contains sample applications used to validate ASP.NET Core Issue #69129 - QuickGrid Query Parameter Names and evidence.

## Contents
- Static SSR sample application
- Interactive Server sample application
- Validation report and test results
- Video evidences

## Deployment / Running the Samples

```bash
cd QuickGridQueryParameterNamesSSR or cd QuickGridQueryParameterNamesServer
dotnet restore
dotnet build
dotnet run
```

The validation covers default query parameter names, custom prefixes, multiple QuickGrid instances, paging, sorting, URL state persistence, and browser navigation scenarios.