# tendermint_vagrant

```bash
vagrant up
```

`https://tendermint.readthedocs.io/projects/tools/en/master/getting-started.html`

## データ初期化
```bash
tendermint unsafe_reset_all
```

## 起動
```bash
tendermint init
tendermint node
```

### 空ブロックを作らない
```bash
tendermint node --consensus.create_empty_blocks=false
```
