# Portfolio

KANT 과정에서 진행한 프로젝트를 정리한 포트폴리오입니다. 각 프로젝트는 결과 수치와 근거, 회고를 함께 남깁니다.

## Projects

| 프로젝트 | 한 줄 요약 | 역할 | 기간 | 스택 |
|---|---|---|---|---|
| [shipping-rag](projects/shipping-rag/README.md) | 해운 PDF 50개에서 근거를 찾아 출처와 함께 답하는 RAG Q&A. 검색 방식 3종(Naive / Hybrid / Hybrid+Rerank)을 같은 조건으로 비교 | 4인 팀, 검색(Retriever) 모듈 담당 | 2026.11.05 ~ 11.13 | Python, Qdrant, E5, BM25, bge-reranker, FastAPI, Docker |

## 읽는 순서

1. [프로젝트 개요와 결과](projects/shipping-rag/README.md): 무엇을 만들었고 어떤 결과가 나왔는지
2. [회고](projects/shipping-rag/retrospective.md): 어떤 문제를 만났고 무엇을 배웠는지

## 구조

```text
portfolio/
├── README.md
└── projects/
    └── shipping-rag/
        ├── README.md
        ├── retrospective.md
        └── assets/
```
