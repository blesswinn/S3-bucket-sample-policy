use this code as a sample s3 bucket policy 

```JSON
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": [
                "s3:GetObject"
            ],
            "Resource": [
                "arn:aws:s3:::Buetck-Name/*"
            ]
        }
    ]
}



//for public access

{
  "Id": "Policy1691249178900",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1691249111183",
      "Action": [
        "s3:GetObject",
        "s3:PutObject"
      ],
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::Bucket-Name/*",
      "Principal": "*"
    }
  ]
}
```
