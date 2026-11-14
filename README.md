# Portfolio

안녕하세요, **chanyeongg3-design**입니다. AI·LLM 서비스 개발을 공부하며, KANT 과정에서 팀 프로젝트로 RAG 시스템의 **검색(Retrieval) 품질**을 직접 구현하고 측정했습니다. 이 저장소는 그 결과와 과정을 근거와 함께 정리한 포트폴리오입니다.

## PROJECT 3 · 해운 문서 RAG Q&A (shipping_rag)

| 항목 | 내용 |
|---|---|
| 주제 | 해운 PDF 50개(3,750페이지)에서 근거를 찾아 문서명·페이지 출처와 함께 답하는 RAG Q&A. 검색 방식 3종을 같은 조건으로 비교 |
| 형태 / 기간 | 4인 팀 · 2026.11.05 ~ 11.13 |
| 내 담당 | **Retriever 3종**(Naive / Hybrid / Hybrid + Rerank)과 **검색 평가기** |
| 대표 결과 | 동일 조건(같은 인덱스·질문·k=5)에서 Hybrid + Rerank는 Naive 대비 **page Recall@5가 0.619 → 0.676, 약 5.7%p 상승** (채점 56문항) |

> 위 수치는 "정확한 근거 페이지를 검색해 오는 비율"이며, 답변의 정확도가 아닙니다.

- [PROJECT 3 상세 보기](projects/shipping-rag/README.md)
- [PROJECT 3 회고: 실패한 시도와 다음 실험](projects/shipping-rag/retrospective.md)
- [팀 원본 저장소 (kant-proj3-team3/shipping_rag)](https://github.com/kant-proj3-team3/shipping_rag)

## 구조

```text
portfolio/
├── README.md                      # 입구 (이 문서)
└── projects/
    └── shipping-rag/
        ├── README.md              # 프로젝트 상세
        ├── retrospective.md       # 회고
        └── assets/                # 구조도·결과 그래프
```

다른 프로젝트는 `projects/` 아래에 폴더를 추가해 이어서 정리할 예정입니다.
