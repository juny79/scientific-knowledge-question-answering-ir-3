# 🧪 Scientific Knowledge Question Answering System  
## 한국어 과학 상식 질의응답 시스템 (RAG Optimization)

본 프로젝트는 **"과학 지식 질의 응답 시스템 구축" 대회**를 위해 개발된 **고성능 RAG(Retrieval-Augmented Generation) 파이프라인**입니다.  
초기 베이스라인(**MAP 0.66**)에서 시작하여, **다단계 검색 전략**, **지능형 게이팅**, **합성 데이터 파인튜닝**, 그리고 **정밀한 LLM Judge 전략**을 통해 최종 **MAP 0.9470**을 달성했습니다.

---

## 📋 Executive Summary

- **목표**: 한국어 과학 상식 문서(약 **4,200개**) 기반의 정확한 정보 검색 및 답변 생성  
- **최종 성과**: **MAP 0.9470 / MRR 0.9470 (리더보드 1위 달성)**  
- **핵심 기술**
  - **Retrieval**: BGE-M3 (Dense + Sparse) Hybrid Search + RRF Fusion
  - **Optimization**: Solar Pro 2 기반 지능형 게이팅 & Query Expansion
  - **Reranking**: BGE-Reranker-v2-m3 Cross-Encoder
  - **Final Strategy**: Synthetic Data Fine-tuning & LLM Judge 기반 Surgical Strike

---

## 📈 Performance Evolution

프로젝트 기간 동안 총 **90회 이상의 실험**을 통해 단계적으로 성능을 향상시켰습니다.
