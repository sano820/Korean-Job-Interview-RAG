# Korean-Job-Interview-RAG  

이 프로젝트는 **채용면접 인터뷰 데이터셋**을 기반으로, Sentence-BERT 임베딩을 구현하고 API로 연동하는 과정을 담고 있습니다.   


## 🧩 주요 기술 스택  
- **Python 3.11**  
- **FAISS**: Dense vector similarity search    
- **Sentence-BERT** (`jhgan/ko-sbert-nli`)  
- **google.genai** (API 서버 연결 시)  
- **JSONL 기반 커스텀 데이터셋**


## 🧠 데이터  
본 프로젝트는 **AI Hub의 "채용면접 인터뷰 데이터셋"**을 기반으로 진행되었습니다.   
해당 데이터셋은 면접 상황을 시뮬레이션하여 수집된 **질문-응답 페어(QA pair)**와 이에 대한 감정, 의도, 요약 등 메타 정보를 포함합니다.  

  
## 💾 디렉토리 구조  
```
📁 Korean-Job-Interview-RAG/
├── 📁 notebooks/
│   ├── 1_data_preparation.ipynb   
│   ├── 2_vector_indexing.ipynb   
│   ├── 3_retriever_module.ipynb   
│   └── 4_api_interface.ipynb   
├── 📁 products/ 
│   ├── merged_interview_data.json             
│   ├── rag_chunks.json      
|   ├── rag_faiss.index     
|   └── rag_texts.json     
└── README.md 
```
