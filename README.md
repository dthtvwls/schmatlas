[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

IAM Policy:

    {
        "Version": "2012-10-17",
        "Statement": {
            "Effect": "Allow",
            "Action": [
                "s3:DeleteObject",
                "s3:GetObject",
                "s3:PutObject"
            ],
            "Resource": "arn:aws:s3:::hypr-catalog/*"
        }
    }
