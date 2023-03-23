# Oss Proto

## add
```shell
# normal add
git submodule add -b master --name api/oss-proto https://github.com/go-cinch/oss-proto.git ./api/oss-proto

# or force add
git submodule add -f -b master --name api/oss-proto https://github.com/go-cinch/oss-proto.git ./api/oss-proto
```

## update
```shell
git submodule update --force --recursive --init --remote
```
