# Workspace Run

```
yarn workspace pkg1 run custom-script arg1 --option1`
```

and compare the **process.argv** results with

```
yarn workspace pkg1 run custom-script -- arg1 --option1
```

Note: `--` is deprecated.

# Root Run

For comparison

```
yarn run custom-script arg1 --option1
```
