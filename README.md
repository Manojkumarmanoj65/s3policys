# s3policys
Object inside a particular  folder is accessible now to everyone
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
      "Resource": "arn:nameofthearnofyourbucket/*",
      "Principal": "*"
    }
  ]
}
