# Enable secure access to resources using IAM roles and temporary credentials?

AWS enables secure access to resources using IAM roles and temporary credentials by allowing a user to assume an IAM role and receive a set of temporary credentials that are used to securely access AWS resources.

&#x20;The credentials are associated with the IAM role and are generated by the AWS Security Token Service (STS).&#x20;

The credentials are valid only for the duration specified by the IAM role and can be used to access AWS resources until they expire. Additionally, IAM roles can be configured to require multi-factor authentication (MFA) to further increase security.
