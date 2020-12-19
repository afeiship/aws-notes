# cli usage

## s3 urls
```conf
s3://course-assets.saybot.net/test.txt
https://s3.cn-north-1.amazonaws.com.cn/course-assets.saybot.net/test.txt
```

## test cmd
```shell
aws s3 ls 
```

## configuration
> 一个配置都不能少，否则: 报下面的错误。
~~~
An error occurred (InvalidAccessKeyId) when calling the ListBuckets operation: The AWS Access Key Id you provided does not exist in our records.
~~~

```conf
[default]
aws_access_key_id = AKIATMK3T7SLFMYHLP5M
aws_secret_access_key = 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
region = cn-north-1
```

## list configuration
```shell
aws configure list
```
