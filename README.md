# Bitcoin_like_scripts
Stack-based Execution Engine for Validating Bitcoin-like Scripts

1. 문제 설명
- 비트코인의 full 노드에서 진행되는 트랜잭션 검증을 흉내 내는 가상의 스택 기반 실행 엔진을 설계하고 구현한다
- full 노드는 실행 엔진을 사용
    - P2PKH, P2SH, Multisignature 형태의 스크립트를 실행시켜 결과를 도출
    - UTXO 집합과 트랜잭션 집합을 갖는다
    - 트랜잭션 집합의 각 트랜잭션 스크립트와 이 트랜잭션이 참조하는 UTXO의 스크립트를 연계하여 순차적으로 실행