# CD12352 - Infrastructure as Code Project Solution

# [AN NGUYEN NGOC]

## Spin up instructions

Create network

```bash
bash create.sh network network.yml network-parameters.json
```

Upload `index.html` to s3

```bash
bash create.sh project-2 s3-bucket.yml s3-bucket-parameters.json aws s3api put-object --bucket myudagrambucket0810 --key index.html
```

Create udagram

```bash
bash create.sh udagram udagram.yml udagram-parameters.json
```

## Tear down instructions

Delete network

```bash
bash delete.sh network
```

Delete udagram

```bash
bash delete.sh udagram
```

## Other considerations

TODO (optional)
