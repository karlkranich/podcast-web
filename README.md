# podcast-web
Web form and javascript that adds episodes to podcast feed using AWS API Gateway, Lambda functions, DynamoDB, and S3.
Requires an auth.js file that looks like:
  apiKey = "thisistheapikeyforauthenticatingtoapigateway"
  apiUrl = "https://apiurlfromamazon.execute-api.us-east-1.amazonaws.com/prod/add-episode";

For more info, see [Karl's Podcast Hosting Project](https://karl.kranich.org/2020/09/25/serverless-podcast/)
