# Personal Data Assistant

Chatbot that reads a document and creates a summary of its information.
It uses [Llama2 LLM](https://llama.meta.com/llama2/) and retrieval augmentation generation (RAG).
The web interface is done with Flask.
The [LangCahin](https://www.langchain.com/) framework is used to integrate the RAG.
<!-- 
 It chains together the retrieval, extraction, processing, and generation operations from the large amounts of text and multiple sources.
 -->

<!-- 
Retrieval-augmented generation (RAG) is a sophisticated technique that enhances LLMs by integrating external information retrieval into the text generation process. RAG represents a significant leap forward in making AI-generated content more contextually aware and precise.

Beenefits:

- Intelligent model response: RAG offers accurate and relevant responses by dynamically incorporating additional information on which the model was not trained.

- Auto update: RAG reduces the need for users to continuously train the model on new data and update its parameters based on the given conditions.
-->

![Interface](https://github.com/MartinezAgullo/GenAI_5_SummariseData/blob/main/PersonalDataAsistant.jpg)


# Download the code
Original code from[build_own_chatbot_without_open_ai](https://github.com/sinanazeri/build_own_chatbot_without_open_ai.git).  Download it with:

> git clone https://github.com/sinanazeri/build_own_chatbot_without_open_ai.git
> mv build_own_chatbot_without_open_ai build_chatbot_for_your_data
> cd build_chatbot_for_your_data
> pip install -r requirements.txt

# Execution
> python3 server.py


#  Bot Architecture diagram
![DocumentProcessing](https://github.com/MartinezAgullo/GenAI_5_SummariseData/blob/main/document_processing.jpg)
Original picture  from [Satish Srinivasan](https://www.linkedin.com/in/satish-srinivasan-209b605a/?lipi=urn%3Ali%3Apage%3Ad_flagship3_pulse_read%3B8VYOM%2FAVTx6NgCBWwwwCzw%3D%3D)