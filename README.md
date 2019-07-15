### Upload files to S3 bucket

```bash
$ cd mypage

$ aws s3 sync . s3://ykarakita.com/ --exclude ".git/*"
```
