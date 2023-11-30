Preview

```bash
time PULUMI_EXPERIMENTAL=1 PULUMI_SKIP_CHECKPOINTS=true PULUMI_CONFIG_PASSPHRASE= pulumi preview --stack frank --diff
```

Deploy

```bash
time PULUMI_EXPERIMENTAL=1 PULUMI_SKIP_CHECKPOINTS=true PULUMI_CONFIG_PASSPHRASE= pulumi up --stack frank -f

time PULUMI_EXPERIMENTAL=1 PULUMI_SKIP_CHECKPOINTS=true PULUMI_CONFIG_PASSPHRASE= TF_LOG=TRACE pulumi up --stack frank -f --logtostderr --logflow -v=10 2> out.txt
```