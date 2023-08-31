# CD12352 - Infrastructure as Code Project Solution

# [AN NGUYEN NGOC]

## Spin up instructions

Create network

```bash
bash create.sh network network.yml network-parameters.json
```

Create s3 bucket

```bash
bash create.sh s3-bucket s3-bucket.yml s3-bucket-parameters.json
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

Delete s3 bucket

```bash
bash delete.sh s3-bucket
```

Delete udagram

```bash
bash delete.sh udagram
```
