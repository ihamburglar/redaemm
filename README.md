# redaemm

This is a vulnerable by design mock metadata service for use in CTFs and offensive security education.

This is a fork of the amazon-ec2-metadata-mock project available at https://github.com/aws/amazon-ec2-metadata-mock under the Apache 2.0 license.

### Run w/ Docker
```
git clone https://github.com/ihamburglar/redaemm
cd redaemm
docker build -t redaemm .
docker run -dp 3000:1338 redaemm
curl http://localhost:3000
```
