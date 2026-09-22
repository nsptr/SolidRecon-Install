<!-- 게시 전 <DOWNLOAD_HOST>와 <SUPPORT_CONTACT>를 실제 값으로 변경하십시오. -->

# SolidRecon 설치 가이드

SolidRecon은 Windows 10/11 64비트 환경을 지원합니다.

## 설치 전 확인

- Windows 10 또는 Windows 11 64비트
- 인터넷 연결
- 프로그램 설치 권한
- GPU 기능 사용 시 NVIDIA 그래픽 카드와 최신 드라이버

## SolidRecon 설치

### [SolidRecon 설치 시작](https://kr.object.ncloudstorage.com/solidrecon-install/SolidReconV1/Publish.html)

1. 위 링크에서 `setup.exe`를 내려받습니다.
2. 내려받은 파일을 실행하고 화면의 안내에 따라 설치합니다.
3. 설치가 끝나면 SolidRecon을 실행합니다.

## GPU 기능 사용

GPU 기반 AI 기능을 사용하려면 NVIDIA 드라이버와 다음 구성 요소가 필요합니다.
자세한 사항은 [설치 페이지의 AI 기능 설정](https://kr.object.ncloudstorage.com/solidrecon-install/SolidReconV1/Publish.html)을 참고하세요.

1. [CUDA Toolkit 12.8 다운로드](https://developer.nvidia.com/cuda-12-8-0-download-archive)
2. [cuDNN 9.3 다운로드](https://developer.nvidia.com/cudnn-9-3-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=Agnostic&cuda_version=12)
3. 설치 후 Windows를 다시 시작합니다.
4. SolidRecon을 실행하여 AI 기능을 확인합니다.

## 문제 해결

### 설치 파일이 내려받아지지 않는 경우

- 인터넷 연결을 확인합니다.
- 회사 또는 기관의 보안 프로그램이 다운로드를 차단했는지 확인합니다.
- 다른 브라우저에서 다시 시도합니다.

### 프로그램이 실행되지 않는 경우

- Windows를 다시 시작한 후 실행합니다.
- 기존 SolidRecon이 실행 중이면 종료한 뒤 다시 시도합니다.
- 설치 오류 화면을 캡처하여 지원 담당자에게 전달합니다.

### GPU 기능을 사용할 수 없는 경우

- NVIDIA 그래픽 드라이버가 최신 버전인지 확인합니다.
- CUDA Toolkit 12.8과 cuDNN 9.3이 설치되어 있는지 확인합니다.
- Windows를 다시 시작한 뒤 SolidRecon을 실행합니다.

## 문의

문제가 계속되면 아래 정보를 포함하여 담당자에게 문의하십시오.

- 오류 화면 캡처
- Windows 버전
- SolidRecon 버전
- NVIDIA GPU 모델과 드라이버 버전(GPU 기능 사용 시)

지원: **dev@neospectra.co.kr**
