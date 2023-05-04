# How does AWS implement encryption to protect data at rest and in transit?

AWS implements encryption to protect data at rest and in transit through the use of various encryption technologies such as AWS Key Management Service (KMS), AWS CloudHSM, Amazon S3 server-side encryption, Amazon EBS encryption, Amazon RDS encryption, and Amazon Redshift encryption.

AWS KMS is used to encrypt data stored in Amazon S3, Amazon EBS, and Amazon RDS. It uses customer-managed keys and provides a secure, auditable way to encrypt and decrypt data.

AWS CloudHSM uses hardware security modules to provide an extra layer of security for encryption keys. AWS CloudHSM is ideal for applications where data must be highly protected from unauthorized access.

Amazon S3 server-side encryption uses Advanced Encryption Standard (AES) 256 to encrypt data stored in Amazon S3.

Amazon EBS encryption uses AES 256 to encrypt data stored on Amazon EBS.

Amazon RDS encryption uses AES 256 to encrypt data stored in Amazon RDS.

Amazon Redshift encryption uses AES 256 to encrypt data stored in Amazon Redshift.

For data in transit, AWS uses Secure Socket Layer (SSL) and Transport Layer Security (TLS) to protect data as it travels across networks.
