# JGroups S3_CLIENT_PING

## Overview

S3_CLIENT_PING will communicate using AWS SDK for Java.
Credentials are resolved by Default Credential Provider Chain: for example, you can use Instance profile credentials with it, which exist within the instance metadata associated with the IAM role.

To enable S3_CLIENT_PING, you need the following code;

```java
ClassConfigurator.addProtocol((short) 1000, S3_CLIENT_PING.class);
```

## Contributing

[Pull requests] are welcome.

## License

S3_CLIENT_PING is released under version 2.0 of the [Apache License].


[Pull requests]: http://help.github.com/send-pull-requests
[Apache License]: http://www.apache.org/licenses/LICENSE-2.0