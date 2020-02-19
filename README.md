ReactJS + [Amazon Cognito](https://aws.amazon.com/cognito/) + [Amazon Amplify Framework](https://aws-amplify.github.io/docs/js/start) Starter Project
===================================================

### Update the Cognito configuration
First and foremost, create a Cognito User Pool. Then open 'src/configs/aws-configs.js' and update the `aws_user_pools_id` and the `aws_user_pools_web_client_id` properties.
 
```
const awsConfig = {
    aws_app_analytics: 'false',
    aws_user_pools: 'enable',
    aws_user_pools_mfa_type: 'OFF',
    aws_user_settings: 'enable',
    aws_user_pools_id: 'us-west-2_0xX0xxx2X', //TODO: need to change this
    aws_user_pools_web_client_id: '3r47xxx2xxxxxxxx83395d3a2q', //TODO: need to change this
};

export default awsConfig
```

### Build the project and run it locally (the default url is 'http://localhost:3000')

```npm install && npm start```
