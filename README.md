# 게임이 실행 직후 강제로 종료될 경우
클라이언트 버전에 따라 번역 플러그인을 포함했을 때 게임이 실행 직후 강제 종료될 수 있습니다.  
사용하지 못 할 때에는 플러그인을 제외하여 번역을 사용하지 않은 상태로 플레이 해주세요.  
자세한 내용은 아래 이슈를 참고해주세요.  
https://github.com/StarlightPN/A25-KoreanPatch/issues/1

# A25-KoreanPatch
A25, '레슬레리아나의 아틀리에 \~잊혀진 연금술과 극야의 해방자~'의 일본판에 대한 자동 번역 플러그인과 번역 파일을 합친 패키지 입니다.

## ※ 주의사항 ※
### <p align="center">본 패치에서 사용하는 프로그램은<br>실행 중인 다른 프로그램의 요소를 읽고, 교체하는 프로그램입니다.<br>이에 따라, 본 페이지에서 제공되는 프로그램들의 사용으로 인해<br>원 서비스 제공자가 사용자를 제재할 수 있습니다.<br>이러한 상황이 발생한 경우 프로그램 사용자의 책임이며,<br>플러그인 및 패키지 제공자에는 책임이 없음을 명시합니다.</p>


본 패치(번역기)를 사용한 경우, 화면 내 모든 텍스트를 번역하기 때문에 검색을 비롯하여 텍스트 입력 및 그와 연관된 기능들이 올바르게 동작하지 않을 수 있습니다.  
해당 기능을 사용하기 위해서는 플러그인을 제거하여 번역을 사용하지 않거나, 모바일 버전에서 사용해주세요.

## 번역 정보
+ 자동 번역 : Papago 번역기
+ 번역 검수 : [별빛마루(starlightpn)](https://bsky.app/profile/starlightpn.bsky.social)

## 사용된 프로그램
+ [BepinEx 6.0.0-pre.2](https://github.com/BepInEx/BepInEx/releases/tag/v6.0.0-pre.2)
+ [XUnity.AutoTranslator 5.4.0](https://github.com/bbepis/XUnity.AutoTranslator)

## 패치 적용 방법(현재 사용 불가)
1. 오른쪽의 'Release'를 선택하여 패치 파일을 다운로드 합니다.
2. 다운로드 받은 패치 파일 중, 'Plugin Package' 폴더에 있는 파일들을 `게임 폴더(..\AtelierResleriana\)`에 배치합니다.
3. 다운로드 받은 패치 파일 중, 'Translation' 폴더에 있는 번역 파일 중, 사용할 번역 폴더를 `게임 번역 폴더(..\AtelierResleriana\BepInEx\Translation\ko\Text\)`에 배치합니다.
4. 게임을 시작합니다.

## 진척도
~ : 진행 중 혹은 진행 예정   
─ : 예정 없음   
○ : 작업 완료   
  
| 영역 | 텍스트 파일 존재 여부 | 데이터 정리 | 작업 상태 |
|-|-|-|-|
| 메인 화면 UI | 있음(CommonUI) | 진행 중 | ~ |
| 메인 스토리 | 있음(MainStory) | 진행 중 | ─ |
| 이벤트 스토리 | <b>없음</b> | 없음 | ─ |
| 아이템 이름 | 있음(Item) | 진행 중 | ~ |
| 특성(잠재 능력) 이름 | 있음(Ability) | 진행 중 | ~ |
| 이벤트 UI | 있음(EventUI) | 진행 중 | ~ |
| 전투 UI | 있음(BattleUI) | 진행 중 | ~ |
| 캐릭터 이름 | 있음(CharaName) | 진행 중 | ~ |
| 스킬 설명 | 있음(CharaSkill) | 진행 중 | ~ |
| 메모리아 | 있음(Memoria) | 진행 중 | ~ |
| 화면 도움말 | 있음(Help) | 미 진행 | ─ |
| 미션 | 있음(Mission) | 진행 중 | ~ |
| 엠블럼 | 있음(Emblem) | 진행 중 | ~ |
| 로그인 대사 | 있음(LoginDialogue) | 일부 진행 | ~ |
| 아틀리에 대사 | 있음(AtelierDialogue) | 일부 진행 | ~ |

<b>※ 번역 판본의 진행 여부는 예고 없이 변경될 수 있습니다.</b>   
<b>※ 아이템과 특성은 일부 정식 발매 번역을 사용합니다.</b>

## 번역 누락에 대해
번역기 플러그인 특성 상, 확인이 불가능한 텍스트는 번역이 누락되어 번역기의 결과로 표시될 수 있습니다.
확인된 해당 영역은 아래와 같습니다.
+ 메인 스토리 진행 중 하게되는 전투 챕터 이름
+ ★3 캐릭터 획득 시 표시되는 대사

## 알려진 문제
+ 스토리 진행 중, 화자 텍스트와 지문 텍스트의 표시 높이가 일치하지 않는 문제.
    + 해당 문제는 폰트 에셋 설정으로 최소화 하였으나, 현재 가진 지식으로는 해당 부분의 높이만 조정이 불가능 합니다.
    + 해당 부분의 높이를 아래로 조정하면 나머지 UI의 텍스트들도 함께 내려가게 되어, 체류 시간이 높은 UI 화면을 더 우선하기로 하였습니다.
+ 조합 필터 화면에서 캐릭터의 기프트 컬러가 한자어('홍', '청' 등)로 표기된 문제.
    + 해당 영역의 최대 텍스트 길이가 1자로 추정됩니다.
    + 해당 영역에 2글자를 입력하면 '...'로 표기되어 부득이하게 한자어로 표기하게 되었습니다.

## 예정 사항
+ 전체 번역 텍스트 추가
    + 번역 플러그인에서는 배포 시 텍스트 파일도 함께 배포하여 온라인 번역기의 부하를 줄이는 것을 권장하고 있습니다.
+ 전체 번역 텍스트 검수
+ 전체 텍스트 번역
    + 예시)'마법 대미지 상승' → '마법 피해 증가'
    + 예시)'스태미나' → '행동력'
    + 예시)'메모리아' → '추억'
    + 등등
+ 이 단계까지 진행이 완료되면 1차적으로 배포 예정입니다.
+ 정규 표현식을 사용하여 번역 데이터 정리

## 적용 화면
![주의 사항](https://github.com/StarlightPN/A25-KoreanPatch/blob/main/Readme_Resource/1.png)
![메인 화면](https://github.com/StarlightPN/A25-KoreanPatch/blob/main/Readme_Resource/2.png)
![설정 화면](https://github.com/StarlightPN/A25-KoreanPatch/blob/main/Readme_Resource/3.png)

## 일본판 설치 방법


## 수동 적용법
아래에서는 본 페이지의 파일을 사용하지 않고 사용자가 직접 적용하는 방법을 설명합니다.

### 1. BepinEx Bleeding Edge build 설치
[여기](https://builds.bepinex.dev/projects/bepinex_be)에서 BepinEx Bleeding Edge 빌드를 다운로드 합니다.
+ BepinEx-Unity.IL2CPP-win-x64-... 버전을 다운로드합니다.
+ XUnity.AutoTranslator가 지원하는 것으로 명시된 버전은 #672 버전입니다.

다운로드 받은 BepinEx Bleeding Edge 버전을 `게임 폴더(..\AtelierResleriana\)`에 설치합니다.

### 2. XUnity.AutoTranslator의 BepinEx Plugin 설치
[여기](https://github.com/bbepis/XUnity.AutoTranslator/releases/tag/v5.3.0)에서 XUnity.AutoTranslator의 BepinEx Plugin을 다운로드 합니다.
+ XUnity.AutoTranslator-BepInEx-IL2CPP..를 다운로드 해야합니다.
+ 240504 현재 최신 버전은 5.3.0입니다.

다운로드 받은 XUnity.AutoTranslator-BepInEx-IL2CPP 플러그인을 설치합니다.

1번과 2번을 통해 게임 폴더에 아래 폴더 및 파일들이 반드시 존재해야 합니다.  
파일 확장자가 없는 것을 폴더를 가리킵니다.
```
..\AtelierResleriana\BepInEx
..\AtelierResleriana\dotnet
..\AtelierResleriana\.doorstop_version
..\AtelierResleriana\doorstop_config
..\AtelierResleriana\winhttp.dll
..\AtelierResleriana\BepInEx\core\XUnity.Common.dll
..\AtelierResleriana\BepInEx\plugins\XUnity.AutoTranslator\ExIni.dll
..\AtelierResleriana\BepInEx\plugins\XUnity.AutoTranslator\XUnity.AutoTranslator.Plugin.BepInEx-IL2CPP.dll
..\AtelierResleriana\BepInEx\plugins\XUnity.AutoTranslator\XUnity.AutoTranslator.Plugin.Core.dll
..\AtelierResleriana\BepInEx\plugins\XUnity.AutoTranslator\XUnity.AutoTranslator.Plugin.ExtProtocol.dll
..\AtelierResleriana\BepInEx\plugins\XUnity.ResourceRedirector\XUnity.ResourceRedirector.BepInEx-IL2CPP.dll
..\AtelierResleriana\BepInEx\plugins\XUnity.ResourceRedirector\XUnity.ResourceRedirector.dll
```
### 3. 게임 실행
게임을 실행하면 게임과 함께 명령 프롬프트 창이 열려야 합니다.  
명령 프롬프트 창에서 작업이 끝나기 전에는 게임이 시작되지 않습니다.  
명령 프롬프트 창에서 작업이 끝난 후, 게임이 시작되면 게임을 종료합니다.

### 4. 폰트 에셋 추가 및 설정
게임 종료 후, 아래 파일이 생성된 것을 확인합니다.  
(생성되지 않았을 경우, 다시 게임을 켜고 타이틀 화면까지 대기한 후 종료합니다)
```
..\AtelierResleriana\BepInEx\config\AutoTranslatorConfig.ini
```

폰트 에셋(TextMesh Pro) 파일을 다운 받은 후, 위 설정 파일의 텍스트를 찾아 아래와 같이 변경합니다.  
※ 폰트 에셋 파일을 별도로 지정하지 않으면 텍스트가 올바르게 표시되지 않습니다

```
[Service]
Endpoint=PapagoTranslate

[General]
Language=ko
FromLanguage=ja

[Behaviour]
..
FallbackFontTextMeshPro=폰트에셋파일명
```

설정 파일의 자세한 정보는 [XUnity.AutoTranslator 페이지](https://github.com/bbepis/XUnity.AutoTranslator?tab=readme-ov-file#configuration)를 참조해주세요.

### 5. 게임 실행
게임을 실행하면 게임 내 텍스트가 원문으로 표시된 후, 번역문으로 대체됩니다.  
위 과정을 모두 따라했을 경우, 번역문은 아래 위치에 생성됩니다.
```
..\AtelierResleriana\BepInEx\Trnaslation\ko\Text\_AutoGeneratedTranslations.txt
```
