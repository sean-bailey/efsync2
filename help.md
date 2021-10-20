# generate wheel file and dist

```bash
python3 setup.py sdist bdist_wheel
```

# install and test

```bash
python3 -m pip install dist/efsync2-1.0.0-py3-none-any.whl
```

## display ec2 logs

```bash
cat /var/log/cloud-init-output.log
```
