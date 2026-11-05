# 반도체 엔지니어를 위한 AI 리터러시 실습

실습용 코드입니다. 기본적으로 ipynb로 구성되어있으며, 한 셀씩 읽고 실행하는 식으로 구성되어있습니다.

## Colab에서 바로 열기

설치 없이 아래 버튼을 누르면 Colab에서 열립니다. 첫 셀부터 순서대로 실행하면 실습 데이터도 자동으로 내려받습니다. 6주차 PyTorch 실습은 **런타임 → 런타임 유형 변경 → T4 GPU**를 선택한 뒤 실행합니다.

| 실습 | 열기 |
|---|---|
| 준비 · 환경 확인 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/00_%ED%99%98%EA%B2%BD%ED%99%95%EC%9D%B8.ipynb) |
| 준비 · 파이썬 기초 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/01_%ED%8C%8C%EC%9D%B4%EC%8D%AC%EA%B8%B0%EC%B4%88.ipynb) |
| 준비 · 데이터 안내 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/02_%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%95%88%EB%82%B4.ipynb) |
| 2주차 · 비슷한 공정 묶기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/02%EC%A3%BC%EC%B0%A8_%EB%B9%84%EC%8A%B7%ED%95%9C_%EA%B3%B5%EC%A0%95_%EB%AC%B6%EA%B8%B0.ipynb) |
| 3주차 · 막 두께 예측하기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/03%EC%A3%BC%EC%B0%A8_%EB%A7%89_%EB%91%90%EA%BB%98_%EC%98%88%EC%B8%A1%ED%95%98%EA%B8%B0.ipynb) |
| 4주차 · 불량 후보 분류하기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/04%EC%A3%BC%EC%B0%A8_%EB%B6%88%EB%9F%89_%ED%9B%84%EB%B3%B4_%EB%B6%84%EB%A5%98%ED%95%98%EA%B8%B0.ipynb) |
| 5주차 · 뉴런 하나 학습시키기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/05%EC%A3%BC%EC%B0%A8_%EB%89%B4%EB%9F%B0_%ED%95%98%EB%82%98_%ED%95%99%EC%8A%B5%EC%8B%9C%ED%82%A4%EA%B8%B0.ipynb) |
| 6주차 · 신경망 검증하기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/06%EC%A3%BC%EC%B0%A8_%EC%8B%A0%EA%B2%BD%EB%A7%9D_%EA%B2%80%EC%A6%9D%ED%95%98%EA%B8%B0.ipynb) |
| 6주차 · PyTorch로 신경망 학습하기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SeokJH-TAs/semiconductor_ai_beginner/blob/main/notebooks/06%EC%A3%BC%EC%B0%A8_PyTorch%EB%A1%9C_%EC%8B%A0%EA%B2%BD%EB%A7%9D_%ED%95%99%EC%8A%B5%ED%95%98%EA%B8%B0.ipynb) |

수업 구성

| 주차  | 진행 방식                                                        | 실습 파일                                                                       | 필수 범위                         |
| ----- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------- | --------------------------------- |
| 1주차 | AI 정의·역사·반도체 적용 사례 설명과 토론. 별도 코드 실습 없음 | 없음. 대신 파이썬 환경 설정                                                     | 과제·입력·출력의 예를 말로 구분 |
| 2주차 | 비슷한 공정 묶기                                                 | [02주차_비슷한_공정_묶기.ipynb](notebooks/02주차_비슷한_공정_묶기.ipynb)         | 1~4번 구역                        |
| 3주차 | 막 두께 예측하기                                                 | [03주차_막_두께_예측하기.ipynb](notebooks/03주차_막_두께_예측하기.ipynb)         | 1~6번 구역                        |
| 4주차 | 불량 후보 분류하기                                               | [04주차_불량_후보_분류하기.ipynb](notebooks/04주차_불량_후보_분류하기.ipynb)     | 1~3번 구역                        |
| 5주차 | 뉴런 하나 학습시키기                                             | [05주차_뉴런_하나_학습시키기.ipynb](notebooks/05주차_뉴런_하나_학습시키기.ipynb) | 1~4번 구역                        |
| 6주차 | 신경망 검증하기                                                  | [06주차_신경망_검증하기.ipynb](notebooks/06주차_신경망_검증하기.ipynb)           | 1~4번 구역                        |

## 처음 시작할 때

1. 아래 설치 절차를 따라 환경을 준비합니다.
2. VS Code에서 이 폴더 전체를 엽니다.
3. `00_환경확인.ipynb`로 커널·도구·파일을 확인합니다.
4. 코드가 처음이면 `01_파이썬기초.ipynb`, 데이터 뜻이 낯설면 `02_데이터안내.ipynb`를 봅니다. 이 둘은 준비 자료이며 주차별 과제가 아닙니다.
5. 해당 주차 파일 하나를 엽니다. 맨 위부터 필수 구역을 순서대로 실행합니다. “선택” 구역은 필요할 때만 진행합니다.

기존 차시별 초안은 `archive/차시별_이전초안/`에 보관합니다. 수업 진행에는 위 표의 주차별 파일을 사용합니다.

## VS Code·conda 설치부터 첫 실행까지

처음 한 번은 인터넷이 필요합니다. 설치를 마친 뒤에는 이 꾸러미의 CSV만 사용합니다. GPU나 유료 AI API가 필요하지 않습니다. 개인 PC 설정을 자동으로 변경하는 설치 스크립트는 없습니다.

## 1. 파일부터 준비하기

ZIP 파일을 압축 해제합니다. 폴더 이름 `semiconductor_ai_beginner` 아래에 `environment.yml`, `notebooks`, `data`가 함께 보여야 합니다. `notebooks`만 따로 옮기지 마세요. Windows에서는 예를 들어 `C:/ai-class/semiconductor_ai_beginner`처럼 짧은 경로를 쓰시면 편합니다. macOS에서는 Documents 아래에 두셔도 됩니다.

## 2. VS Code 설치하기

1. [VS Code 공식 다운로드](https://code.visualstudio.com/Download)에서 운영체제에 맞게 설치합니다.
2. Windows는 설치 프로그램을 실행합니다. macOS는 앱을 Applications로 옮긴 뒤 실행합니다.
3. VS Code 왼쪽의 네모 네 개 모양 **Extensions(확장)**를 누릅니다.
4. **Python**을 검색해 발행자가 Microsoft인 확장 `ms-python.python`을 설치합니다.
5. **Jupyter**를 검색해 Microsoft 확장 `ms-toolsai.jupyter`를 설치합니다.
6. File → Open Folder에서 압축 해제한 **실습 전체 폴더**를 엽니다. 폴더를 직접 확인하고 신뢰할 수 있을 때만 작업영역 신뢰를 선택합니다.

VS Code는 코드를 읽고 쓰는 작업장입니다. 실제 코드를 실행하는 Python은 다음 단계에서 준비합니다.

## 3. conda 설치하기

이미 conda가 있다면 새로 설치하지 말고 `conda --version`부터 확인합니다. 이 안내는 conda-forge 패키지를 사용하는 **Miniforge3**를 기준으로 합니다. Miniforge는 conda를 포함한 배포판입니다. Miniconda도 conda 명령은 같지만 설치 화면과 기본 저장소는 다를 수 있습니다.

[Miniforge 공식 설치 안내](https://github.com/conda-forge/miniforge#install)

- Windows 일반 Intel/AMD PC: Windows x86_64 설치 파일을 선택하고 기본 사용자 설치를 진행합니다. 시작 메뉴에서 **Miniforge Prompt**를 엽니다. 임의로 전역 PATH를 바꾸지 않아도 됩니다. Windows ARM 등 다른 장치는 공식 지원 목록을 확인합니다.
- Mac의 Apple M1/M2/M3/M4 등: macOS **arm64**를 고릅니다. Intel Mac은 macOS **x86_64**를 고릅니다. Apple 메뉴 → 이 Mac에 관하여에서 칩 종류를 확인합니다. 공식 안내의 설치기를 실행하고 셸 초기화 질문에 동의한 뒤 터미널을 닫았다 다시 엽니다.
- macOS에서 shell 설치 파일을 받았다면 터미널에 `bash `를 입력한 뒤 다운로드한 `.sh` 파일을 끌어 넣고 Enter를 누릅니다. 파일명 앞의 `bash`는 그 설치 파일을 실행하라는 뜻입니다.

**터미널**은 컴퓨터에게 짧은 명령을 입력하는 창입니다. Windows는 위의 Miniforge Prompt, macOS는 Terminal 앱을 사용합니다. 아래 명령을 노트북 코드 셀에 넣지 마세요. `>>>` 같은 표시도 입력하지 않습니다.

```text
conda --version
```

conda와 버전 숫자가 나오면 성공입니다. 찾을 수 없다고 나오면 터미널을 다시 열고 Windows에서는 Miniforge Prompt가 맞는지 확인합니다. macOS 셸 초기화를 건너뛰었다면 Miniforge 설치 안내의 초기화 절차를 따릅니다. 예를 들어 기본 설치 위치일 때 `~/miniforge3/bin/conda init zsh`를 실행한 뒤 터미널을 다시 엽니다. 설치 위치가 다르면 그 위치로 바꿔야 합니다.

## 4. 실습 폴더로 이동하기

터미널에서 `cd `를 입력하고 실습 전체 폴더를 끌어 넣은 뒤 Enter를 누릅니다. 경로에 공백이 있으면 큰따옴표로 감쌉니다. `cd`는 폴더를 바꾼다는 뜻입니다. Windows에서는 다른 드라이브로 이동할 때 `cd /d "전체경로"`를 사용합니다.

예시 경로는 본인 파일 위치로 바꾸세요.

```text
cd /d "C:\ai-class\semiconductor_ai_beginner"
```

Mac 예시:

```text
cd "/Users/본인계정/Documents/semiconductor_ai_beginner"
```

Windows에서는 `dir`, Mac에서는 `ls`를 입력해 `environment.yml`이 보이는지 확인합니다.

## 5. 수업 전용 환경 만들기

다음 세 줄은 **한 줄씩** 터미널에서 실행합니다. 첫 줄은 설치에 시간이 걸릴 수 있습니다. 완료되기 전에 다음 줄을 넣지 마세요.

```text
conda env create -f environment.yml
conda activate semi-ai
python -m ipykernel install --user --name semi-ai --display-name "Python (semi-ai)"
```

| 명령 부분                       | 쉬운 뜻                                 |
| ------------------------------- | --------------------------------------- |
| `conda env create`            | 수업용 도구 상자를 새로 만듭니다.       |
| `-f environment.yml`          | 설치 목록을 이 파일에서 읽습니다.       |
| `conda activate semi-ai`      | 수업용 도구 상자를 사용합니다.          |
| `python -m ipykernel install` | 이 Python을 노트북 실행기로 등록합니다. |
| `--user`                      | 지금 사용자 계정에 등록합니다.          |
| `--name semi-ai`              | 내부 구분 이름을 지정합니다.            |
| `--display-name ...`          | 화면에 보일 실행기 이름을 정합니다.     |

`environment.yml`의 name은 환경 이름, channels는 도구를 가져올 저장소, dependencies는 도구 목록입니다. `nodefaults`는 다른 기본 저장소를 섞지 않게 합니다. Python·NumPy·pandas·scikit-learn·matplotlib·Jupyter 실행 도구와 PyTorch를 함께 설치합니다. conda 도구 설치 뒤 파일 안의 pip 목록을 자동으로 설치합니다. 버전 범위는 `guides/검증환경.txt`에 적은 실행 환경을 기준으로 정했습니다. 운영체제가 다르면 의존 패키지 구성은 달라질 수 있습니다.

같은 이름의 환경이 이미 있다면 지우지 말고 `conda activate semi-ai` 후 필요한 패키지 버전을 확인하세요. 이 꾸러미 환경으로 맞출 때는 `conda env update -n semi-ai -f environment.yml`를 사용할 수 있습니다. 해당 환경을 다른 용도로 쓰셨다면 강사와 상의해 다른 환경 이름을 사용하세요.

## 6. VS Code에서 실행기 선택하기

1. VS Code로 돌아가 `notebooks/00_환경확인.ipynb`를 엽니다.
2. 오른쪽 위 **Select Kernel(커널 선택)**을 누릅니다. 이미 이름이 보이면 그 이름을 눌러 바꿀 수 있습니다.
3. 필요하면 **Select Another Kernel → Jupyter Kernel** 또는 **Python Environments**로 들어갑니다. 목록은 설치 상태에 따라 다릅니다.
4. **Python (semi-ai)** 또는 경로에 `envs/semi-ai`가 들어간 Python을 선택합니다.
5. 각 코드 셀 왼쪽 ▶ 버튼 또는 Shift+Enter로 실행합니다. 첫 두 셀의 출력으로 환경을 확인합니다.
6. 노트북 위쪽 **Restart**는 기억을 지우고 실행기를 다시 시작합니다. **Run All**은 위에서부터 모두 실행합니다. 예제를 바꾼 뒤에는 Restart 후 Run All을 권합니다.

**커널**은 노트북 코드를 실행하는 엔진입니다. 터미널의 환경 활성화와 노트북의 커널 선택은 따로 확인해야 합니다. Python: Select Interpreter만 바꿔도 기존 노트북의 커널은 그대로일 수 있습니다.

## 7. 혼자 해보기

VS Code에서 실습 전체 폴더를 열고 원하는 노트북을 연 뒤, Python (semi-ai) 커널을 선택합니다. 새 노트북은 첫 셀부터 실행합니다. 앞 노트북의 변수는 자동으로 이어지지 않습니다. 수업이 끝나면 저장합니다. 터미널 환경을 끝내려면 `conda deactivate`를 입력합니다.

## 자주 생기는 문제

| 화면에 보이는 말                  | 뜻과 해결                                                                                                                                                                       |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `conda`를 찾을 수 없음          | 터미널을 다시 열고, Windows는 Miniforge Prompt를 사용합니다.                                                                                                                    |
| `environment.yml`이 없음        | 명령을 넣은 폴더가 실습 전체 폴더인지 `dir`/`ls`로 확인합니다.                                                                                                              |
| `ModuleNotFoundError`           | 실행기가 다른 환경일 수 있습니다. 노트북 커널과 환경 확인 셀부터 확인합니다.                                                                                                    |
| `FileNotFoundError`             | 압축을 풀었는지, data와 notebooks가 나란히 있는지 확인합니다. 전체 폴더를 엽니다.                                                                                               |
| `NameError`                     | 앞 셀에서 만든 이름이 없습니다. 첫 셀부터 순서대로 실행합니다.                                                                                                                  |
| `IndentationError`              | if·for 아래 줄의 공백 네 칸과 줄 끝 콜론을 확인합니다.                                                                                                                         |
| 셀 왼쪽 `[*]` 또는 실행 중 표시 | 계산 중입니다. 기다린 뒤 계속 멈춰 있으면 정지 버튼을 누르고 커널을 재시작합니다.                                                                                               |
| 커널 목록에 없음                  | VS Code를 다시 열고 환경 등록 명령을 semi-ai 활성화 상태에서 다시 실행합니다. 아니면 conda 를 연결합니다. 그래도 안되면 터미널에 jupyternotebook 을 실행하고 커널을 연결합니다. |

## 그외

- [VS Code 노트북 사용법](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
- [VS Code 커널 선택](https://code.visualstudio.com/docs/datascience/jupyter-kernel-management)
- [conda 환경 관리](https://docs.conda.io/projects/conda/en/stable/user-guide/tasks/manage-environments.html)
- [Miniforge 설치](https://github.com/conda-forge/miniforge)

## 그림으로 비교하는 구역

- **2주차:** 1-1번에서 군집화 이전의 회색 점, 4번에서 군집화 이후의 색칠한 점을 봅니다. 축 범위를 같게 맞췄습니다. 점 위치는 그대로이고 묶음 번호만 생깁니다.
- **3주차:** 2-1번은 학습 전 측정 점, 5번은 유량·전력을 학습 평균에 고정한 회귀 예측선, 6번은 시험 행마다 실제값과 예측값의 비교입니다. 6번의 대각선은 실제값=예측값인 기준선입니다.

## PyTorch 설치도 environment.yml에 포함

`environment.yml` 하나로 기본 도구와 **torch 2.0.1**을 함께 설치합니다. 파일의 `pip` 항목을 conda가 이어서 실행하므로 별도의 pip 설치 명령을 입력할 필요가 없습니다. GPU, torchvision, torchaudio는 사용하지 않습니다.

**처음 환경을 만드는 경우** 실습 전체 폴더의 터미널에서 실행합니다.

```text
conda env create -f environment.yml
conda activate semi-ai
python -m ipykernel install --user --name semi-ai --display-name "Python (semi-ai)"
```

**이미 semi-ai 환경을 만든 경우** 아래처럼 설치 목록을 업데이트합니다. 환경을 삭제할 필요가 없습니다.

```text
conda env update -n semi-ai -f environment.yml
conda activate semi-ai
python -c "import torch; print(torch.__version__)"
```

설치 후 VS Code에서 **Python (semi-ai)** 커널을 선택하고 Restart를 누릅니다. 출력은 `2.0.1`인지 확인합니다. `No module named torch`가 나오면 터미널과 노트북이 같은 환경인지 확인합니다.

이 버전은 기존 Python 3.10·NumPy 1.24 수업 환경과 저장된 실행 결과에 맞추었습니다. 다른 Python 버전이나 장치의 지원 여부는 [공식 이전 버전 설치 안내](https://pytorch.org/get-started/previous-versions/)에서 확인할 수 있습니다. `requirements-torch.txt`는 이전 수동 설치 방식과의 호환용이며, 수업 설치는 `environment.yml`을 사용합니다.

## PyTorch 실습 파일과 실행 순서

[06주차_PyTorch로_신경망_학습하기.ipynb](notebooks/06주차_PyTorch로_신경망_학습하기.ipynb)를 엽니다. 3주차의 공정 조건과 막 두께를 다시 사용하므로 새 데이터 다운로드가 없습니다. 기존 6주차 불량 분류·검증 실습은 그대로 있습니다.

| 구역 | 확인할 내용 |
|---|---|
| 1~2 | 공정 표, 입력 3개·정답 1개, 텐서 모양 |
| 3 | Dataset의 입력·정답 짝과 DataLoader의 16행 배치 |
| 4 | class, nn.Module, __init__, forward와 파라미터 |
| 5 | zero_grad 전후, backward 기울기, step 전후 가중치 출력 |
| 6~7 | main의 전체 학습 순서와 손실 곡선 |
| 8~9 | 학습 전·후 시험 예측, RMSE와 역할 정리 |
| 선택 A | 가상 영상의 CNN 입력 (N, C, H, W)와 중간 출력 |
| 선택 B | 합성 시간 기록의 RNN 입력 (N, L, F)와 마지막 시점 출력 |

CNN·RNN 구역은 공식 문서의 모양 약속에 맞춰 입력과 출력을 연결하는 연습입니다. 이 두 모델은 학습하지 않았으며 출력 숫자는 성능을 뜻하지 않습니다. 기존 공정 표를 임의로 접어 영상이나 시계열로 간주하지 않습니다.

## 코드·실행 결과 발표자료

`slides/반도체_AI_리터러시_코드실습_20261104.pptx`를 사용합니다. 각 실습 슬라이드에 열 노트북 이름과 구역을 적었습니다. 코드는 배포 노트북에서, 텍스트·플롯은 실행 결과에서 가져왔습니다. 코드 캡처는 노트북의 내용을 읽기 좋게 렌더링한 이미지이며 VS Code 화면을 촬영한 이미지는 아닙니다.

주차마다 필요한 실습을 골라 진행합니다. 1주차에 별도 코드를 강제로 추가하거나 모든 이론 차시를 각각 실습으로 만들지는 않습니다.

슬라이드별 파일·구역의 전체 목록은 [슬라이드 이용 안내](guides/슬라이드이용안내.txt)에 있습니다.


## 4주차 결정 트리 그림과 판정 경로

`notebooks/04주차_불량_후보_분류하기.ipynb`의 2번 학습 뒤에 **2-1 전체 트리 그림**, **2-2 시험 기록 하나의 노드 경로**를 추가했습니다. 1번부터 순서대로 실행합니다. `samples`는 그 노드의 학습 기록 수, `value`는 수업 환경 1.3에서 정상·불량 학습 기록 수, `gini`는 섞임 정도, `class`는 다수 클래스입니다. 왼쪽은 조건이 참, 오른쪽은 거짓입니다. 뒤의 3번 채점은 랜덤 포레스트 결과입니다. 추가 설치는 필요하지 않습니다.
