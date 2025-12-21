# 대학생의 양자컴퓨팅 도전기

> 7일간 실제 IBM 양자컴퓨터로 배우는 양자 알고리즘 여정

## 프로젝트 개요

- **기간**: 2025년 12월 15일 ~ 21일 (7일)
- **목표**: Bell부터 Grover까지 5개 알고리즘 마스터
- **하드웨어**: IBM Quantum (ibm_kyiv, 127 qubits)
- **평균 충실도**: 96%+

## 완료한 알고리즘

| Day | 알고리즘 | 충실도 | 상태 |
|-----|---------|--------|------|
| 1-2 | Bell State | 97.95% | ✅ |
| 3-4 | Deutsch-Jozsa | ~95% | ✅ |
| 5 | Bernstein-Vazirani | ~96% | ✅ |
| 6 | Simon's Algorithm | 96.8% | ✅ |
| 7 | Grover's Algorithm | 95.6% | ✅ |

## 주요 성과

### Bell State (Day 1-2)
- 양자 얽힘(Entanglement) 첫 경험
- 97.95% 충실도 달성
- 노이즈 2.05% 분석

### Deutsch-Jozsa (Day 3-4)
- Oracle 개념 이해
- Constant vs Balanced 함수 구별
- 3→4 큐비트 확장 성공

### Bernstein-Vazirani (Day 5)
- Hidden bit string 찾기
- Dot product 개념 적용
- Secret '110' 1회 측정으로 발견

### Simon's Algorithm (Day 6)
- Periodicity & Orthogonality 이해
- Secret string '110' 발견
- 96.8% 유효 측정

### Grover's Algorithm (Day 7)
- Amplitude Amplification 경험
- Target '10': 95.6% 성공률
- Target '11': 93.7% 성공률

## 기술 스택

- **언어**: Python 3.x
- **프레임워크**: Qiskit
- **하드웨어**: IBM Quantum Platform
- **시각화**: Matplotlib, Qiskit Visualization

## 프로젝트 구조

```
quantum-journey/
├── week1-foundations/    # 알고리즘 코드
├── results/              # 실험 결과 이미지
├── docs/                 # 학습 노트
└── requirements.txt      # 의존성
```

## 실행 방법

```bash
# 1. 저장소 클론
git clone https://github.com/jeondusan-cloud/quantum-journey.git

# 2. 라이브러리 설치
pip install -r requirements.txt

# 3. IBM Quantum 계정 설정
# https://quantum.ibm.com 에서 API 토큰 발급

# 4. 코드 실행
python week1-foundations/05_grover_algorithm.py
```

## 학습 자료

- [IBM Quantum Learning](https://learning.quantum.ibm.com/)
- [Qiskit Textbook](https://qiskit.org/textbook/)
- [Nielsen & Chuang - QCQI](http://mmrc.amss.cas.cn/tlb/201702/W020170224608149940643.pdf)

## 다음 계획

- [ ] Grover 3큐비트 확장
- [ ] Quantum Fourier Transform
- [ ] Shor's Algorithm
- [ ] VQE (Variational Quantum Eigensolver)

## 학습 통계

- **총 학습 시간**: 7일
- **알고리즘 수**: 5개
- **실험 횟수**: 15+
- **평균 충실도**: 96%+
- **코드 라인**: 500+

## 감사의 말

- IBM Quantum Platform
- Qiskit Community
- 모든 양자컴퓨팅 학습자들

## 라이선스

MIT License

---

** 이 프로젝트가 도움이 되었다면 Star를 눌러주세요! **
