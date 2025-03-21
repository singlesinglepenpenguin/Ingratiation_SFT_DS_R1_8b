# Ingratiation_SFT_DS_R1_8b
Locally Deployed DeepSeek-R1:8B LoRA Fine-Tuning Example on Online Classroom Fawning Behavior Dataset

Using a locally deployed large model in an online classroom setting, this project defines Ingratiation text behaviors based on teacher-student interactions. 
The dataset consists of real online classroom teaching data combined with mixed synthetic data. Sample data can be found in train_data_demo.json and test_data_demo.json(Chinese).

Implementation Details:
1.Implement automated recognition of fawning behavior in the education domain using a locally deployed 8B DeepSeek model.
2.Design a LoRA fine-tuning method with an expert-annotated dataset of 2,807 samples, covering five behavioral categories: Opinion Conformity(18.4%), Compliment(18.4%), Self-Presentation(22.1%), Favor Rendering(4.0%), None(37.1%). Approximate the real data distribution of fawning behavior in teaching scenarios using the sample ratio from experimental data. The dataset includes both the bullet chat content and course information, guiding LLM to consider the classroom context, thereby reducing misclassifications caused by in-class question answering.
3.Split the dataset 7:3 for fine-tuning, train for three epochs, and observe a significant improvement in accuracy.
