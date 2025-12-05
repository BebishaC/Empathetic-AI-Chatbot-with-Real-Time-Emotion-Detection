# Empathetic-AI-Chatbot-with-Real-Time-Emotion-Detection
An emotion-aware conversational AI chatbot that combines state-of-the-art NLP models with empathetic response templates. Detects emotions in real-time using a fine-tuned BERT model and generates contextually appropriate, emotionally intelligent responses using Facebook's BlenderBot Model.
An AI chatbot that detects emotions in real-time and generates empathetic responses using BERT for emotion detection and BlenderBot for conversation.

## Features
- **Real-time Emotion Detection**: Identifies 7 emotions with confidence scores
- **Hybrid Response Generation**: Combines AI models with empathetic templates
- **Conversation Tracking**: Saves chats and provides emotion statistics
- **Easy to Use**: Interactive terminal interface with simple commands

## Quick Start
1. Click the "Open in Colab" badge above
2. Run all cells (Runtime → Run all)
3. Start chatting!

## Example
You: I got a promotion!
Bot [joy 🟢 92%]: That's wonderful news! Tell me more about it!


## Commands
- `quit`/`exit` - End conversation
- `stats` - Show emotion statistics
- `history` - View conversation
- `save` - Export to JSON
- `clear` - Start new chat

## Technical Stack
- PyTorch + HuggingFace Transformers
- BERT (emotion detection)
- BlenderBot (conversation)
- JSON for data export
