
---

## ✅ 실습 진행 상황

### 📘 Pandas 기초 학습 (Kaggle Learn)

| Lesson | 주제                          | 진행상황 | 관련 파일 |
|--------|-------------------------------|----------|------------|
| 1      | Creating, Reading and Writing     | ✅ 완료 | `01_creating_reading_writing.ipynb`, `01_exercise_creating_reading.ipynb` |
| 2      | Indexing, Selecting & Assigning  | ✅ 완료 | `02_indexing_selecting_assigning.ipynb`, `02_exercise_indexing_selecting_assigning.ipynb` |
| 3      | Summary Functions and Maps       | ✅ 완료 | `03_summary function_maps.ipynb`, `03_exercise_summary function_maps.ipynb` |
| 4      | Grouping and Sorting             | ✅ 완료 | `04_grouping_sorting.ipynb`, `04_ex_grouping_sorting.ipynb` |
| 5      | Data Types and Missing Values    | ✅ 완료 | `05_data types_missing values.ipynb`, `05_ex_data types_missing values.ipynb` |
| 6      | Renaming and Combining           | ✅ 완료 | `06_Renaming_Combining.ipynb`, `06_ex_Renaming_Combining.ipynb` |

---

## 🔍 주요 목표

- Pandas 기본 문법 숙달  
- Jupyter Notebook을 활용한 실습 기반 학습 정리  
- 고객 이탈 예측을 통한 머신러닝 기초 이해  
- 실습 결과를 GitHub에 꾸준히 기록하며 포트폴리오화  

---

## 🚧 진행 중 어려웠던 점

- DataFrame은 2차원이기에 `{}`로 묶어주고, Series는 1차원이기에 `[]`로 묶어준다.  
- 실습 도중 `Unnamed: 0`을 읽어서 의도와는 다르게 데이터 값이 읽혔음. `read_csv` 뒤에 `index_col=0`을 추가해서 해결.  
- pandas에서 `and`, `or`을 썼더니 오류가 나서 확인해보니, pandas에서는 `&`, `|`을 연산 기호로 사용한다.  
- `axis=0`, `axis=1` 개념이 처음엔 헷갈렸지만, 행/열 기준으로 데이터를 어떻게 적용하는지를 통해 확실히 이해했다.  
- `rename()`에서는 `{}` 방식과 `dict()` 방식 둘 다 가능하지만, 특수문자가 있는 컬럼명일 때는 `{}` 방식이 더 안전하다.  

---

## 💡 배운 점 및 느낀 점

- DataFrame과 Series의 각 특징을 확실하게 이해하게 되었다.  
- `iloc`은 숫자 기반, `loc`은 라벨 기반이다.  
- `iloc`은 빠른 탐색, 테스트에 적합하고, `loc`은 필터링, 실무 코드 작성에 더 유용하다.  
- `iloc`은 슬라이싱 시 끝값을 포함하지 않지만, `loc`은 끝값을 포함한다.  
- `apply` 메소드에서 `axis=0`은 열마다, `axis=1`은 행마다 함수를 적용한다.  
- `groupby().agg()`를 통해 집계 연산을 유연하게 수행할 수 있다.  

---

## ✍️ 작성자

- 이름: 조민기  
- GitHub: [https://github.com/siloam72761](https://github.com/siloam72761)
