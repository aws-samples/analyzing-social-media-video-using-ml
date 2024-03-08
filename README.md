## Analyzing and tagging video for optimal ad targeting and placement

This Jupyter notebook is designed as accompanying code to the blog post "Techniques for analyzing & tagging social media video for optimal targeting and advert placement". 

## Usage

Your environment must have python3, pip and conda installed. You will also require an environment that can run Jupyter notebooks, such as Amazon SageMaker Notebooks or JupyterLab. 

The IAM role that you are using to run the notebook will require access to the following services: 

- Amazon Transcribe (e.g. policy AmazonTranscribeFullAccess)
- Amazon Rekognition (e.g. policy AmazonRekogntionFullAccess)
- Amazon Bedrock (e.g. policy AmazonBedrockFullAccess)
- An S3 bucket (e.g. a policy that allows Read and Write actions on your chosen bucket)

Additionally, you will need to ensure that Anthrophic Claude is enabled in your Amazon Bedrock console under "Model Access". 


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

