MAESTRO Framework
MAESTRO (Multi-Agent Social Engineering Attack Recognition) is a lightweight cybersecurity framework designed to detect advanced, multi-turn social engineering attacks on professional platforms like LinkedIn.

Unlike traditional security systems that only analyze isolated messages, MAESTRO models the sequential flow of an entire conversation to identify attackers who slowly build trust before making a malicious request.

 How It Works
Dataset Generation: Custom simulation pipelines (benign conversation generator and malicious conversation generator) use LLMs to generate realistic, multi-turn conversational datasets spanning various victim personas, attack scenarios, and pressure styles.

Multi-Agent Detection: The core architecture (phishing_detector) processes the conversation turns using a frozen language encoder and a rule-based tactic agent. It analyzes the temporal flow of the interaction to classify whether the conversation is ultimately malicious or benign
