# Branch Contribution

## Pull Requests

> [!todo]
> ```dataview
> TABLE WITHOUT ID
> file.link as "Pull Requests"
> FROM #PR
> SORT file.name ASC
> ```

- [ ] add missing screenshots for *Charts* examples
- [ ] add sample hint at top of [[Dataview Query Template]] for indication of required additional plugins (like in [[Plot a Category-Series DQL query]]) and fix corresponding instructions in [[00 Meta/Vault Infos/Contribution#Integrating other community plugins]], also fix to `visualization` for consistency over the vault
- [ ] add issue template to get rid of long explanation in [[00 Meta/Vault Infos/Contribution#When you used a downloaded local copy]]

## Test Query

[[My Data Query]]

## Contributions

```dataview
LIST WITHOUT ID
FROM #Merged
SORT file.name ASC
```


# Tinkering

%% Zeigt Daily Notes nach Datum im Dateinamen %%
```dataview
CALENDAR file.day
FROM "10 Example Data/dailys"
```