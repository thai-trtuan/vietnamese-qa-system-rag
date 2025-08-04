# 📚 Vietnamese Question Answering System using RAG

This project is the final thesis of Tran Tuan Thai, focused on building a Vietnamese-language question answering (QA) system using **Retrieval-Augmented Generation (RAG)**. It combines dense document retrieval with a generative language model to provide accurate and context-aware answers.

## 🎯 Project Objectives

- Build a QA system that accepts user questions in Vietnamese
- Retrieve relevant documents or passages using dense retrieval (FAISS + embeddings)
- Generate natural-language answers using a pretrained language model
- Evaluate the system using real QA datasets and metrics (EM, F1)

## 🧠 Key Techniques

- ✅ **RAG Architecture**: Combines retriever + generator
- 🔍 **Dense Passage Retrieval (DPR)** using sentence-transformers or BERT embeddings
- 🧾 **Vector store with FAISS**
- 💬 **Generative model**: GPT-3.5 Turbo, Mixtral 8x7B

## 🧪 Technologies

- Python
- FAISS
- Hugging Face Transformers
- sentence-transformers

## 🧾 Dataset

- Vietnamese Wikipedia corpus (custom indexed)
- Sample QA pairs created or translated manually


## 📈 Sample Output

**Question**: Tác phẩm nổi tiếng nhất của Nguyễn Du là gì?  
**Retrieved docs**: “Truyện Kiều là tác phẩm tiêu biểu nhất của Nguyễn Du, được xem là kiệt tác của văn học trung đại Việt Nam. Tác phẩm còn có tên là Đoạn Trường Tân Thanh.”, “Nguyễn Du là đại thi hào dân tộc, sống vào cuối thế kỷ 18 và đầu thế kỷ 19. Ông để lại nhiều tác phẩm bằng chữ Nôm, trong đó nổi bật nhất là Truyện Kiều.”  
**Answer**: Tác phẩm nổi tiếng nhất của Nguyễn Du là Truyện Kiều.


## 📜 License

This project is for academic and research purposes only.
