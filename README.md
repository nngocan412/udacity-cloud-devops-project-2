# CD12352 - Infrastructure as Code Project Solution

# [AN NGUYEN NGOC]

## Spin up instructions

Create network

```bash
bash create.sh network.yml network-parameters.json
```

Upload `index.html` to s3

```bash
bash create.sh s3-bucket.yml s3-bucket-parameters.json aws s3api put-object --bucket myudagrambucket0810 --key index.html
```

Create udagram

```bash
create.sh udagram.yml udagram-parameters.json
```

## Tear down instructions

```bash
bash delete.sh
```

## Other considerations

TODO (optional)
