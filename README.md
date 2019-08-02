{
  "Id": "Policy1564634397825",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1564634342348",
      "Action": [
        "s3:GetObject"
      ],
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::neewbuckets/*",
      "Principal": "*"
    }
  ]
}
