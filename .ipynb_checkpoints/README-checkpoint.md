# Fine-tune transformer language models for linguistic diversity with Hugging Face on Amazon SageMaker

In this notebook example, we summarize the challenges of low-resource languages and experiment with different solution approaches covering over 100 languages using Hugging Face transformers on Amazon SageMaker. 

We fine-tune various pre-trained transformer-based language models for a question and answering task. We use Turkish in our example, but you could apply this approach to other supported language. Our focus is on BERT variants, because a great feature of BERT is its unified architecture across different tasks. 

We demonstrate several benefits of using Hugging Face transformers on Amazon SageMaker, such as training and experimentation at scale, and increased productivity and cost-efficiency.

You can experiment with NLP tasks on your preferred language in SageMaker in all AWS Regions where SageMaker is available. 


## Solution Architecture

![](./images/workflow.png)

## Solution Overview

1.	Prepare the dataset in an Amazon SageMaker Studio notebook environment and upload it to Amazon Simple Storage Service (Amazon S3).
1.	Launch parallel training jobs on SageMaker training deep learning containers by providing the fine-tuning script.
1.	Collect metadata from each experiment.
1.	Compare results and identify the most appropriate model. 


## License

This library is licensed under the MIT-0 License. See the LICENSE file.


