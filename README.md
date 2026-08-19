# Presenter OBS

A small Windows controller for simpler OBS lessons and broadcasts.

Free beta for Windows. The current installer is unsigned.

## See it in action

**The teacher's screen**

[![Presenter side demo](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-Demo-Preview-v0.2.5.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-Demo-v0.2.5.mp4)

35 seconds: standby, recording, teaching materials, pause, wait, break and stop/save.

**What the class sees**

[![Class side output](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-StudentView-Preview.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-StudentView.mp4)

36 seconds, recorded by the app itself. The teacher's controls never appear, because they are excluded from the broadcast.

**A worksheet, one problem at a time**

[![Worksheet crops on the broadcast](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-WorksheetCrop-Preview.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-WorksheetCrop.mp4)

37 seconds: a worksheet PDF is split into separate problems, and each problem fills the class screen on its own.

## New in 0.2.8

- Draw on the class screen with the mouse: five pen colours, three thicknesses, an eraser and undo. The class sees each
  stroke as it is drawn, over whatever is on air. The drawing surface stays open across materials, and the ink clears
  when you close it, change material or quit. The original lesson file is never modified.

## From 0.2.7

- Worksheet crops keep enough space above the question number, so stacked exponents, fraction indices and summation
  limits on the first line are no longer cut off.

## From 0.2.6

- The interface is English by default and switches to Korean at any time with the `한` button.
- The audience `ready`, `wait` and `break` wording is editable, and the break length is configurable from 1 to 120 minutes.
- Teacher-only windows are kept out of Windows display capture, so the controller and its dialogs stay out of the
  recording even when the captured display is the same monitor. This is an accidental-disclosure guard, not DRM, and it
  does not stop an external camera.

## Download and install

1. Download `PresenterOBS-Setup-v0.2.8.exe` only from the [official v0.2.8 release](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/tag/v0.2.8).
2. Confirm the SHA-256 shown below.
3. If Windows shows `Windows protected your PC`, select `More info`, then `Run anyway`.
4. If `Run anyway` is unavailable, stop and ask the device administrator. Do not disable Windows security protection.

SHA-256: `4D04CDDF81091E778FCEEDE2D7C5ADBF2F9F7A3DEF4360496784AB0323706728`

There is no automatic update channel yet. A later version has to be downloaded and installed the same way.

## 한국어

OBS 수업과 방송을 간단하게 진행할 수 있게 만든 Windows용 컨트롤러입니다.

현재 무료 베타 버전이며 설치 파일은 아직 전자서명되지 않았습니다.

### 사용 영상

**선생님 화면**

[![송출자 시선 영상](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-Demo-Preview-v0.2.5.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-Demo-v0.2.5.mp4)

35초: 대기 화면, 녹화, 수업 자료, 일시정지, 잠시만, 쉬는 시간, 중지·저장.

**학생이 보는 화면**

[![학생 시선 영상](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-StudentView-Preview.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-StudentView.mp4)

36초, 앱이 직접 녹화한 송출 화면입니다. 선생님 조작 창은 송출에서 제외되어 한 번도 보이지 않습니다.

**문제지 문항별 송출**

[![문제지 crop 송출 영상](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-WorksheetCrop-Preview.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.8/PresenterOBS-WorksheetCrop.mp4)

37초: 문제지 PDF를 문항별로 잘라 한 문제씩 학생 화면에 띄웁니다.

### 0.2.8 변경점

- 마우스로 학생 화면에 판서합니다. 펜 5색, 굵기 3단계, 지우개, 되돌리기를 지원하고 긋는 과정이 그대로 송출됩니다.
  판서 창은 자료를 넘겨도 계속 유지되며, 창을 닫거나 자료를 바꾸거나 앱을 종료하면 판서가 함께 사라집니다. 원본
  자료 파일은 바뀌지 않습니다.

### 0.2.7 변경점

- 문항 crop이 문제 번호 위 여백을 충분히 확보해, 첫 줄의 지수·분수 지수·시그마 상한이 잘리지 않습니다.

### 0.2.6 변경점

- 화면 언어가 기본 영어이며 `한` 버튼으로 언제든 한국어로 바꿀 수 있습니다.
- 학생 화면의 `준비`, `잠시만`, `쉬는 시간` 문구를 직접 고칠 수 있고, 쉬는 시간은 1~120분으로 설정합니다.
- 선생님용 창은 Windows 화면 녹화 대상에서 제외되어, 같은 모니터를 녹화할 때도 조작 창과 대화창이 녹화에 남지
  않습니다. 실수 노출을 막는 장치이며 DRM이 아니고 외부 카메라 촬영은 막지 못합니다.

### 다운로드 및 설치

1. [공식 v0.2.8 릴리스](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/tag/v0.2.8)에서 `PresenterOBS-Setup-v0.2.8.exe`를 받습니다.
2. 아래 SHA-256 값이 같은지 확인합니다.
3. `Windows의 PC 보호`가 나오면 `추가 정보(More info)`를 누른 뒤 `실행(Run anyway)`을 선택합니다.
4. `실행` 버튼이 없다면 중단하고 PC 관리자에게 문의하세요. Windows 보안 기능을 끄지 마세요.

SHA-256: `4D04CDDF81091E778FCEEDE2D7C5ADBF2F9F7A3DEF4360496784AB0323706728`

자동 업데이트 기능은 아직 없습니다. 다음 버전도 같은 방법으로 직접 받아 설치해야 합니다.
