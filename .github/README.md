# How to use

```bash
cd utilsWorkflows
```

```bash
chmod +x ./utilsWorkflows/update_w_from_parent.sh
```

```bash
./utilsWorkflows/update_w_from_parent.sh
```

## Update submodules

```bash
git submodule update --remote
git add .
git commit -m "git submodule updated"
git push origin
```

## Update submodule path

```bash
git mv old/submod new/submod
```