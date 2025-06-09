# Virtual Shopping AI Agent - Mattress Recommendation

이 프로젝트는 침대 매트리스 도메인에 한정하여 AI 기반 쇼핑 도우미 Agent를 구축하는 실습입니다.

## Term Project
- 주제: LLM과 RAG 이용한 AI Agent 개발
- 필수 조건
  .고급 Prompt Engineering  기법 사용
  .Function Calling 또는 ReAct 중 하나를 반드시 사용
  .VectorDB를 사용한 RAG 구성 및 적용
  .Github을 이용한 형상관리: 팀별 저장소 생성 필수
- AI Agent가 제공하는 서비스는 자유 주제로 무엇이든 가능함
- LLM과 Vector DB 는 자율 선택
- 프로젝트 평가:
  .각 팀원의 역할 분배와 협업(Github의 Contribution 상황 고려) (10%)
  .프로젝트 완성도 (50%)
  .소스 코드: github  형상 관리 내용(10%)
  .창의성(15%)
  .기술성(15%)
- 일정 : 6월 17일(화) 프로젝트 발표, 기말고사 문제 오픈

## 주요 기능
- RAG 기반 상품 추천
- VectorDB (FAISS) 검색
- SentenceTransformers 임베딩
- OpenAI 최신 Function Calling 기반 상세정보 제공

## 폴더 설명
- data/ : 샘플 데이터셋

## AI Agent 만드는 단계
- 1단계: 샘플 데이터셋 구축(필요시 실시간 API 연동)
- 2단계: 임베딩 생성 (Embedding)
- 3단계: 벡터 DB 구축 (VectorDB - FAISS)
- 4단계: 검색결과 + LLM 결합 → RAG 구성
- 5단계: Function Calling 기반 상품 상세정보 제공

일단 각자 1~5단계까지 모두 실습해 보는 것을 추천

## 프로젝트 업무분배에 대한 의견(한줄당 1인분 분량으로 작성하였습니다.)
- 1단계~3단계 데이터셋 구축부터 벡터 DB 구축하는 것까지는 파트를 나누기가 어렵고, 한번에 구축 필요합니다.
- 4단계 RAG 구성이 성능의 핵심이라, 그래도 개발 이해가 있는 사람이 맡을 필요 있음(Open API 사용시 비용 주의)
- 5단계 일단 RAG까지 구성되면, 어떤 결과까지 나오는지 기대치를 알려주면 Function calling은 어렵지 않음


