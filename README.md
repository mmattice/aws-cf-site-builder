# aws-cf-site-builder

## shell/
	suite of scripts to build a cloudfront based, s3 backed site.
	
## terraform/
	*unfinished* terraform configuration recipies -- there is some functionality still missing from cloudfront
	
## ./
	create-site-aws will build a [Nikola](https://getnikola.com) based website and a codecommit, codebuild, and codepipeline stack to deploy to.  The latter stack will autobuild the static website and push it to the S3 bucket created with the shell scripts above.
