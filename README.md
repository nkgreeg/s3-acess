# S3 check

[![npm](https://img.shields.io/npm/v/s3-check?label=npm)](https://www.npmjs.com/package/s3-check)
[![downloads](https://img.shields.io/npm/dt/s3-check?label=downloads)](https://www.npmjs.com/package/s3-check)

Check access to S3 using credentials

## Run

```shell
npx s3-check -e <endpoint> -r <region> -a <access> -s <secret> -b <bucket>
```

* `-e, --endpoint <endpoint>` - URL to endpoint e.g. `https://s3.provider.store`
* `-r, --region <region>` - region e.g. `us-east-1`
* `-a, --access <access>` - access key e.g. `31d4f5...`
* `-s, --secret <secret>` - secret key e.g. `986ac4...`
* `-b, --bucket <bucket>` - bucket name e.g. `backup`

## Version

```shell
npx s3-check -v
```

## Help

```shell
npx s3-chek -h
```

## Development

* [Development](docs/DEVELOPMENT.md)
