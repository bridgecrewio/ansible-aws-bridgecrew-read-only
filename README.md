# Role
role name
arn:aws:iam::680235478471:role/james-bc-read-bridgecrewcwssarole

managed policy
arn:aws:iam::aws:policy/SecurityAudit
arn:aws:iam::aws:policy/AWSCloudFormationReadOnlyAccess

inline
BridgecrewDescribePolicy

Outputs
ExternalID	6ba0ea21-eb55-4dc8-a7ec-1ced1269495b	ExternalID to share with Bridgecrew for CloudTrail integration	-
RoleARN	arn:aws:iam::680235478471:role/james-bc-read-bridgecrewcwssarole	Cross-account access role ARN to share with Bridgecrew for CloudTrail integration	-
TemplateVersion	1.5	Bridgecrew.io template version

curl https://s3.us-west-2.amazonaws.com/bc-cf-template-890234264427-prod/read_only_template.yml -o readonly_template.yml
