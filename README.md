## Techniques for analyzing & tagging social media video for optimal targeting and advert placement

This notebook is designed as accompanying code to the blog post "Techniques for analyzing & tagging social media video for optimal targeting and advert placement". 

## Usage
Ensure you have both the 'blip2' folder and the 'Analysing Video Blog.ipynb' file to run the notebook. 

Your environment must have python3, pip and conda installed. 

The IAM role that you are using to run the notebook will require access to the following services: 

- Amazon SageMaker to deploy and utilise endpoints (.eg. policy AmazonSageMakerFullAccess)
- Amazon Transcribe (e.g. policy AmazonTranscribeFullAccess)
- Amazon Rekognition (e.g. policy AmazonRekogntionFullAccess)
- Amazon Bedrock (e.g. policy AmazonBedrockFullAccess)
- An S3 bucket (e.g. a policy that allows Read and Write actions on your chosen bucket)

Additionally, you will need to ensure that Anthrophic Claude is enabled in your Amazon Bedrock console under "Model Access". 


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

