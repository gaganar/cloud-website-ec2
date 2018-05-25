# cloud-website-ec2
Cloud Website EC2



aws cloudformation create-stack --stack-name cloud-website  --template-body file:///cloud-formation.json  --parameters file:///parameters.json

# To delete the site

aws cloudformation delete-stack --stack-name cloud-website
