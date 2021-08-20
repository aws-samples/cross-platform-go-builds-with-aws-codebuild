## Target Cross-platform Go Builds with AWS CodeBuild Batch Builds

This project shows how to create a single AWS CodeBuild project using a batch build and a single build spec to create concurrent builds for the 6 targeted platforms. You can learn more about batch builds in AWS CodeBuild in the documentation: https://docs.aws.amazon.com/codebuild/latest/userguide/batch-build.html

# Usage

The example application uses the bucket name provided, and lists all object keys in a bucket.

```sh
AWS_REGION=us-west-2 ./listObjects <bucket>
```

Output:
```
Page, 0
Object: myKey
Object: mykey.txt
Object: resources/0001/item-01
Object: resources/0001/item-02
Object: resources/0001/item-03
Object: resources/0002/item-01
Object: resources/0002/item-02
Object: resources/0002/item-03
Object: resources/0002/item-04
Object: resources/0002/item-05
```

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE 
