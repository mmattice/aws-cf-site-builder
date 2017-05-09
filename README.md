# aws-cf-site-builder

## create-site/aws

build a cloudfront based, s3 backed site

### shell/

suite of scripts to execute create-site 
	
### terraform/
	
*unfinished* terraform configuration recipies -- there is some functionality still missing from cloudfront
	
## create-blog/aws

nikola-aws-blog.create will build a [Nikola](https://getnikola.com) based website and a codecommit, codebuild, and codepipeline stack to deploy to.  The latter stack will autobuild the static website and push it to the S3 bucket created with the shell scripts above.
