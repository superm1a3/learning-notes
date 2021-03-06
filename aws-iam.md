A request represents that _somebody_<sub>1</sub> wants to _do_ something<sub>2</sub> _with_ something<sub>3</sub>.

The first one is the Principal. It is the user, the role, the AWS service, or some special entity that sends the request. Principal can be IAM user or IAM role.

The second part is the Action. It defines what the Principal wants to do, such as reading an object or creating a new Lambda function.

The third is the Resource. It is the logical entity in the account that is the subject of the request. For example, the specific S3 bucket to delete, or the EC2 instance to launch.
