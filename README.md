# Emotional_Support_ChatBot
A therapy chatbot trained on the ESConv dataset to support empathetic and contextually accurate responses in client-therapist conversations. The project employs T5, GPT2, and BART models, custom tokenizer augmentation, and sharded dataset processing for efficient training.


The chatbot was trained on a diverse array of datasets to ensure generalization and robust response generation:
  Nart 100k Synthetic: Simulated 100k therapeutic conversations.
  Mental Health Counseling Conversations: Real-world dialogues for emotional depth.
  Counsel Chat: Transcripts of live counseling sessions.
  Synthetic Therapy Conversations: Focused on common mental health scenarios.
  Therapy Alpaca: Simulated supportive dialogues.
  Mental Health Therapy: Therapy session records for specialized insights.
  ESConv: Categorized dialogues by therapeutic strategies.

The project evaluated multiple transformer-based models:
  BART: Best overall performer with high coherence and empathetic responses.
  GPT-2: Effective in generating fluent text but struggled with long dialogues.
  T5: Versatile but less emotionally attuned.
  
