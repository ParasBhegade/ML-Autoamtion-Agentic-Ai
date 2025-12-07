SUPERVISED LEARNING
<style>
.red{
  color: pink;
}
</style>

<p class="red">This is styled text</p>

<summary>
-Supervised learning uses labeled data to train models that predict outcomes for new, unseen data.

-The training process involves feeding the model labeled examples, allowing it to learn the relationship between features and labels.

-Models are evaluated by comparing their predictions on unseen data to the actual values, helping to refine their accuracy.

-Once trained and evaluated, models can be used for inference, making predictions on new, unlabeled data in real-world applications.

-The quality of the dataset, including its size and diversity, significantly impacts the model's performance and ability to generalize.
</summary>
DATA
it can be in the form of words, numbers , tables , images or audios. 
ex - imgs of cats , housing prices , weather information.
<p class="red">Datasets contains feature and label</p>
feature are the values model uses to predict the label.

 label is the output that model wants to find or predict. ex- temp , raining , pressure , etc.

Examples that contain both features and a label are called labeled examples.



![Two labeled examples](labeled_example.png)

the model will predict  labels to the dataset if it does not have it specifically.

Dataset characteristics

 size- it indicates the number of examples
 diversity- It indicates the range of of examples i.e how different types of datasets are..

datasets with more features helps model to discover additional patterns and make better predictions.

Training 

before prediction  model needs to be trained so we provide dataset to the model for training . the model finds the best predicted values by comparing predicted and actual labels  and based on diff between pred. and actual values defines as loss the model gradually updates its solution . 
For example, if the model predicted 1.15 inches of rain, but the actual value was .75 inches, the model modifies its solution so its prediction is closer to .75 inches. After the model has looked at each example in the dataset—in some cases, multiple times—it arrives at a solution that makes the best predictions, on average, for each of the examples.

hence multiple comparing and updation makes better prediction hence dataset with large and diverse dataset produces better predictions.

EVALUATION

for evaluation we provide model with dataset containing only features. then,we compares the predicted and actual labels.

![evaluation simulation](evaluating-a-model.png)

