# Question-Generation-And-MCQ-Answer-Generation
This project aims to generate questions and MCQ answers given context

Introduction:

MCQ-Generation is a project designed to streamline the creation of multiple-choice questions (MCQs) through two distinct processes. This README provides an overview of the project, its key components, and the benefits it offers to educators, content creators, and individuals seeking efficient MCQ generation.

First Process:

1. Question Generation using flan_T5 Model
The first process begins with the utilization of the flan_T5 model, a transformer-based model specialized in question generation. This step involves taking a provided passage or context as input and leveraging the model to generate pertinent questions based on the content.

2. Question Answering using distilbert Model
After generating questions, the distilbert model is employed for question answering. This model evaluates the generated questions and identifies the most appropriate answer within the provided passage or context.

3. Distractor Generation using T5 Model
Following the identification of the correct answer, the T5 model is enlisted to generate distractors. Distractors are the incorrect options offered in MCQs. The T5 model generates credible distractors to complement the correct answer.

4. Integration for MCQ Generation
In the final step, all components are seamlessly integrated to create a comprehensive MCQ. The question generated in step 1, the correct answer identified in step 2, and the distractors generated in step 3 are combined to produce a fully formed multiple-choice question.

Second Process:

The second process harnesses the power of Large Language Models (LLaMA v1) for MCQ generation. LLaMA v1 comprises a set of highly proficient language models trained on extensive text data. These models possess the capability to comprehend context, generate text, and respond to questions.

In this process, the LLaMA v1 model is directly employed to generate MCQs without the need for separate question generation, question answering, or distractor generation steps. The model can grasp a provided passage or context and autonomously generate MCQs with options, including the correct answer and plausible distractors.

Conclusion:

The MCQ-Generation project provides two distinct processes for automating the creation of multiple-choice questions. The first process encompasses question generation, question answering, and distractor generation using specific models, while the second process leverages Large Language Models (LLaMA v1) to generate MCQs directly. These processes deliver efficient and automated solutions for MCQ generation, offering time and effort savings for educators, content creators, and anyone requiring the generation of substantial quantities of multiple-choice questions.





