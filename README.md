# CLIN-LLM-Research-Project
CLIN-LLM is a hybrid biomedical LLM pipeline for safe, evidence-based diagnosis and treatment. It achieves 98% F1 on the Symptoms2Disease dataset, outperforms ClinicalBERT/GPT-3.5, and integrates uncertainty estimation, retrieval, and safety-aware generation.

# CLIN-LLM: Safety-Constrained Biomedical Language Model for Diagnosis and Treatment

CLIN-LLM is a hybrid framework combining fine-tuned biomedical LLMs, real-time evidence retrieval, and safety-aware treatment generation. It achieves 98% F1-score on the Symptoms2Disease dataset and outperforms existing models like ClinicalBERT and GPT-3.5.
## Methodology:

<img width="2832" height="1360" alt="CILIN-LLM Methodology" src="https://github.com/user-attachments/assets/6328e4c8-fff1-4f19-b7c6-70f0d368287d" />


## 🚀 Highlights
- ✅ 98% Accuracy and F1-score on multi-label diagnosis
- 🔍 Evidence retrieval using Sentence-BERT
- 💡 Treatment generation via FLAN-T5
- 🛡️ Monte Carlo Dropout for uncertainty estimation
- ⚠️ Flags 18% high-risk cases for expert review
- 💊 Reduces inappropriate antibiotic suggestions by 67%

📚 Datasets

Symptoms2Disease (1,200 annotated clinical cases) from Kaggle
MedDialog (context-aware treatment dialogs)
Datasets will be auto-downloaded or can be manually placed in /data.
🧠 Model Components

Fine-tuned encoder: BioClinicalBERT
Retrieval: Sentence-BERT
Generator: FLAN-T5 (tuned for treatment context)
Uncertainty: Monte Carlo Dropout
🔒 Safety & Ethics

CLIN-LLM includes a triage module to defer ambiguous or high-risk cases to human clinicians. Designed for augmenting—not replacing—clinical judgment.

📄 License

MIT License (see LICENSE file)

👥 Author

Md Mehedi Hasan

🤝 Contributing

Pull requests are welcome. Please open an issue first to discuss major changes.

📫 Contact

For inquiries, contact: mehedi.hasan.ict@mbstu.ac.bd
