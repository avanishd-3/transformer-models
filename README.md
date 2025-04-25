# transformer-models

Collection of transformer models (and educational stuff) using PyTorch and Hugging Face.

## Models
Rankings based on the Papers with Code leaderboard (for respective tasks) as of April 8, 2025

| Model                                                                                                                       | Task                 | Evaluation Metric   | Ranking |
|-----------------------------------------------------------------------------------------------------------------------------|----------------------|---------------------|---------|
| [Distilbert-base-uncased finetuned on emotion dataset](https://huggingface.co/avanishd/distilbert-base-uncased-finetuned-emotion) | Text classification  | 92.4% accuracy      | N/A     |
| [Distilbert-base-uncased finetuned on imdb dataset](https://huggingface.co/avanishd/distilbert-base-uncased-finetuned-imdb) | Text classification  | 92.9% accuracy      | 29     |
| [xlm-roberta-base finetuned on Xtreme dataset for german, french, english, italian](https://huggingface.co/avanishd/xlm-roberta-base-finetuned-panx-de-fr-en-it) | Token classification | 83.80 f1 score      | N/A     |
| [pegasus-cnn-dailymail finetuned on samsum dataset](https://huggingface.co/avanishd/pegasus-finetuned-samsum)                | Summarization        | 44.0 Rouge-1 score  | 10      |
| [vit finetuned on CIFAR-10 dataset](https://huggingface.co/avanishd/vit-base-patch16-224-in21k-finetuned-cifar10)                | Image Classification        | 98.77% accuracy  | 30      |
| [vit finetuned on CIFAR-100 dataset](https://huggingface.co/avanishd/vit-base-patch16-224-in21k-finetuned-cifar100)                | Image Classification        | 90.54% accuracy  | 23      |
| [Finetuned DeespSeek-R1-Distill-Qwen-1.5B](https://huggingface.co/avanishd/DeepSeek-R1-Distill-Qwen-1.5B-finetuned-smoltalk-everyday-conversations)                | Text Generation        | N/A  | N/A      |
