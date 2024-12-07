# FRD
A novel framework that generates retrieval-augmented counterfactuals using Generative AI to address these two challenges – scarcity of labelled datasets and cross-domain detection. It processes reviews from source domain and masks domain-specific tokens found using KeyBERT. Subsequently, Gemini-Pro model, combined with retrieval-augmented-generation(RAG) generates target-domain-specific counterfactuals, followed by classification of target reviews using Bi-LSTM.
Each step has a different file.
