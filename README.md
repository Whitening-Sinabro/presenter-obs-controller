# Presenter OBS

A small Windows controller for simpler OBS lessons and broadcasts.

Free beta for Windows. The current installer is unsigned.

## See it in action

[![Watch the Presenter OBS demo](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.5/PresenterOBS-Demo-Preview-v0.2.5.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.5/PresenterOBS-Demo-v0.2.5.mp4)

The 35-second silent clip above is the presenter side: standby, recording, teaching materials, pause, wait, break and
stop/save.

[![Class side output](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.6/PresenterOBS-StudentView-Preview.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.6/PresenterOBS-StudentView.mp4)

And this 36-second clip is the class side, recorded by the app itself: the starting screen, a lesson page, the
please-wait screen, the break countdown and back to the lesson. The teacher's controls never appear, because they are
excluded from the broadcast.

Both clips predate 0.2.6 and do not show the additions below.

## New in 0.2.6

- The interface is English by default and switches to Korean at any time with the `한` button.
- The audience `ready`, `wait` and `break` wording is editable, and the break length is configurable from 1 to 120 minutes.
- Teacher-only windows are kept out of Windows display capture, so the controller and its dialogs stay out of the
  recording even when the captured display is the same monitor. This is an accidental-disclosure guard, not DRM, and it
  does not stop an external camera.

## Download and install

1. Download `PresenterOBS-Setup-v0.2.6.exe` only from the [official v0.2.6 release](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/tag/v0.2.6).
2. Confirm the SHA-256 shown below.
3. If Windows shows `Windows protected your PC`, select `More info`, then `Run anyway`.
4. If `Run anyway` is unavailable, stop and ask the device administrator. Do not disable Windows security protection.

SHA-256: `9426395DA67C20353085091EEAD3702CB12F07AD0639EA397826447E26D34C73`

There is no automatic update channel yet. A later version has to be downloaded and installed the same way.

## 한국어

OBS 수업과 방송을 간단하게 진행할 수 있게 만든 Windows용 컨트롤러입니다.

현재 무료 베타 버전이며 설치 파일은 아직 전자서명되지 않았습니다.

### 사용 영상

[![Presenter OBS 사용 영상 보기](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.5/PresenterOBS-Demo-Preview-v0.2.5.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.5/PresenterOBS-Demo-v0.2.5.mp4)

위의 35초 무음 영상은 송출자 시선입니다. 대기 화면, 녹화, 수업 자료, 일시정지, 잠시만, 쉬는 시간, 중지·저장 흐름을
볼 수 있습니다.

[![학생 시선 영상](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.6/PresenterOBS-StudentView-Preview.jpg)](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/download/v0.2.6/PresenterOBS-StudentView.mp4)

아래 36초 영상은 학생 시선, 즉 앱이 직접 녹화한 송출 화면입니다. 곧 시작합니다 화면, 수업 자료, 잠시만 기다려 주세요,
쉬는 시간 카운트다운, 그리고 다시 수업 자료로 돌아옵니다. 선생님 조작 창은 송출에서 제외되어 한 번도 보이지 않습니다.

두 영상 모두 0.2.6 이전에 촬영해서 아래 변경점은 담겨 있지 않습니다.

### 0.2.6 변경점

- 화면 언어가 기본 영어이며 `한` 버튼으로 언제든 한국어로 바꿀 수 있습니다.
- 학생 화면의 `준비`, `잠시만`, `쉬는 시간` 문구를 직접 고칠 수 있고, 쉬는 시간은 1~120분으로 설정합니다.
- 선생님용 창은 Windows 화면 녹화 대상에서 제외되어, 같은 모니터를 녹화할 때도 조작 창과 대화창이 녹화에 남지
  않습니다. 실수 노출을 막는 장치이며 DRM이 아니고 외부 카메라 촬영은 막지 못합니다.

### 다운로드 및 설치

1. [공식 v0.2.6 릴리스](https://github.com/Whitening-Sinabro/presenter-obs-controller/releases/tag/v0.2.6)에서 `PresenterOBS-Setup-v0.2.6.exe`를 받습니다.
2. 아래 SHA-256 값이 같은지 확인합니다.
3. `Windows의 PC 보호`가 나오면 `추가 정보(More info)`를 누른 뒤 `실행(Run anyway)`을 선택합니다.
4. `실행` 버튼이 없다면 중단하고 PC 관리자에게 문의하세요. Windows 보안 기능을 끄지 마세요.

SHA-256: `9426395DA67C20353085091EEAD3702CB12F07AD0639EA397826447E26D34C73`

자동 업데이트 기능은 아직 없습니다. 다음 버전도 같은 방법으로 직접 받아 설치해야 합니다.
