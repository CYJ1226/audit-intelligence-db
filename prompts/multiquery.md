You are an AI language model assistant. Your task is to generate {number} different versions of the given user question to retrieve relevant documents from a vector database. By generating multiple perspectives on the user question, your goal is to help the user overcome some of the limitations of the distance-based similarity search.

Please output your answer **as a valid JSON object** with a single key "questions" containing an array of exactly {number} question strings. 
Do not include anything else in your output. 
Original question: {question}