# promptEngineering_week1_Experiment5
# Zero-Shot vs Few-Shot Prompting

## 1. Aim
To compare zero-shot and few-shot prompting techniques for sentiment classification of customer reviews using a Large Language Model (LLM).

## 2. Problem Statement
Classify customer reviews into three sentiment categories:
- Positive
- Neutral
- Negative

Compare both prompting techniques based on accuracy, format adherence, and agreement between predictions.

## 3. Technologies Used
- Python
- Google Colab
- Google Gemini API
- Pandas

## 4. Dataset
The experiment uses five predefined customer reviews with known sentiment labels.

## 5. Methodology

### Zero-Shot Prompting
The model classifies customer reviews without receiving any examples.

### Few-Shot Prompting
The model receives three labeled examples before classifying the test reviews.

## 6. Algorithm
1. Define five customer reviews and their correct sentiment labels.
2. Create a zero-shot prompt.
3. Create a few-shot prompt containing three examples.
4. Send the reviews to the same LLM using both methods.
5. Record the predicted sentiment labels.
6. Calculate accuracy, format adherence, and agreement.
7. Display the comparison table and save the results as a CSV file.

## 7. Execution
Open `main.ipynb` in Google Colab and run the notebook cells in order.

Configure your Gemini API key securely before executing the experiment.

## 8. Output
The experiment produces:
- Zero-shot predictions
- Few-shot predictions
- Comparison table
- Accuracy for both methods
- Format adherence scores
- Agreement between methods

The execution screenshot and results CSV are stored in the `output/` folder.

## 9. Conclusion
This experiment compares zero-shot and few-shot prompting using the same five customer reviews. The results help evaluate how providing examples influences sentiment classification performance.

## 10. Repository Structure

```text
zero-shot-vs-few-shot-prompting/
├── main.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── output/
    ├── output_1.png

**Note:** The reported accuracy depends on the actual model predictions. No performance improvement is assumed in advance.
