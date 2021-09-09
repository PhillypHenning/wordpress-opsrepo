# Bitops Operations Repo

This template will build a wordpress blog site for you to blog on! 

Ensure your AWS ACCESS KEY and SECRET are set as env vars. Run the command below, than in the AWS Cloudformation webconsole, watch your deployment go! 

This repo can be run as is with
```
docker run \
-e ENVIRONMENT="test" \
-e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID \
-e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY \
-e AWS_DEFAULT_REGION="us-east-2" \
-v $(pwd):/opt/bitops_deployment \
bitovi/bitops:latest
```

For more information, check out official bitops docs https://bitovi.github.io/bitops/
