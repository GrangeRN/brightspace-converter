# Brightspace NCLEX Question Converter

**By GrangeRN**

A tool to convert NCLEX-style questions from ChatGPT output into Brightspace-compatible CSV format for easy import.

## Features

- ✅ Converts custom GPT NCLEX question output to Brightspace CSV
- ✅ Supports Multiple Choice (MC), Multiple Select (MS), and True/False (TF) questions
- ✅ **Automatic difficulty mapping from Bloom's Taxonomy**
- ✅ Configurable points: Exams (1.6667 points) or Quizzes (5 points)
- ✅ Includes metadata (Bloom's, Nursing Process, NCLEX Category, Tanner's)
- ✅ Single-file HTML app - no installation required

## Usage

1. **Generate questions** using your custom GPT with nursing textbooks
2. **Copy the output** (Title, question, options, rationale, metadata)
3. **Paste into the converter**
4. **Select assessment type** (Exam or Quiz)
5. **Generate CSV** and download
6. **Import to Brightspace** quiz/exam tool

## Question Format Expected

```
Title: [Question Title]

[Question text]

a. [Option A]
b. [Option B]
c. [Option C]
d. [Option D]

Correct answer: a

~
Rationale: [Explanation]

Bloom's Taxonomy Level: [Remember/Understand/Apply/Analyze/Evaluate/Create]
Nursing Process: [Assessment/Diagnosis/Planning/Implementation/Evaluation]
NCLEX Category: [Category]
Tanner's Clinical Judgment: [Stage]
```

## Bloom's Taxonomy Difficulty Mapping

| Bloom's Level | Difficulty Score |
|---------------|------------------|
| Remember | 1 |
| Understand | 2 |
| Apply | 3 |
| Analyze | 4 |
| Evaluate/Create | 5 |

## Points Configuration

- **Exam**: 1.6667 points per question (60 questions = 100 points)
- **Quiz**: 5 points per question

## Deployment

Hosted on GitHub Pages: [https://grangern.github.io/brightspace-converter](https://grangern.github.io/brightspace-converter)

## License

© 2025 GrangeRN - For educational use
