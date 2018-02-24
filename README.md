# A CI for github to AWS S3 via travis

[![Build Status](https://travis-ci.org/orangeflame/S3CI.svg?branch=master)](https://travis-ci.org/orangeflame/S3CI)

Here is a seed project which build react to s3 via travis

Here is the some setting for S3 Policy

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadForGetBucketObjects",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::lekong/*"
        }
    ]
}



Here comes the website
http://les3.s3-website-us-east-1.amazonaws.com/
