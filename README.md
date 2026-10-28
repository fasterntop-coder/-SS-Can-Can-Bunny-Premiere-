==================================================================
 세가새턴 캉캉 버니 프르미에르 (Can Can Bunny Premiere, SEGA SATURN) 한글 패치 v1.0
==================================================================

■ 내용
  - 대사·선택지·메뉴 전부 한국어 번역 (17,456 문장)
  - 한글 폰트(Neo둥근모 2350자) 탑재
  - 타이틀, 벽지 선택, 이름 입력(한글 입력판), 백업 저장 화면, 상태 패널
    (월/일/요일/소지금/만 엔/강수확률) 그래픽 한글화
  - 오프닝 캐릭터 이름 자막 / 엔딩 크레딧(배역·항목명) 한글화
  - 기본 주인공 이름: 프르미에르
  ※ 엔딩 크레딧의 스태프·성우 이름은 원본(일본어) 그대로 두었습니다.

■ 준비물 (원본 이미지: Redump 덤프)
  Can Can Bunny Premiere (Japan) (1M)  — BIN/CUE 12트랙
  패치 대상: "Can Can Bunny Premiere (Japan) (1M) (Track 01).bin"
    크기  158,219,040 바이트
    CRC32 2D17460A
    MD5   3e815c1a7ac505c07af95fce622981c5
    SHA-1 374b507cd390d4fcdd72a16bf2ab7e637f8e16e9
  Track 02~12(오디오)는 수정하지 않습니다.

■ 적용 방법 (둘 중 하나)
 1) xdelta 패치  patch/CanCanBunnyPremiere_KO_Track01.xdelta  (권장)
    - Windows: Delta Patcher 또는 xdeltaUI 에서
        원본 = Track 01.bin, 패치 = .xdelta 파일 → 적용
    - 명령줄: xdelta3 -d -s "원본 (Track 01).bin" CanCanBunnyPremiere_KO_Track01.xdelta "한글 (Track 01).bin"
 2) PPF 3.0 패치  patch/CanCanBunnyPremiere_KO_Track01.ppf
    - PPF-O-Matic 3 등으로 Track 01.bin 에 직접 적용 (원본 파일이 덮어써지므로 백업 필수)
    - 블록 체크가 들어 있어 다른 이미지에는 적용되지 않습니다.

 적용 후 Track 01 결과 확인값:
    CRC32 9E13C2C4
    MD5   00f21c8f4a7d782be199b53c00c6f827
    SHA-1 f5a5641fb5712c6c43c57020ca8f77a2198db22b
  (다른 트랙 포함 전체 체크섬: checksums_sha1.txt / checksums_md5.txt)

 CUE 파일: 원본 .cue 를 그대로 쓰거나(파일명이 같다면),
   함께 제공되는 "Can Can Bunny Premiere (Japan) (1M) [T-Ko].cue" 를 쓰고
   트랙 파일 이름을 그에 맞춰 바꾸세요.

■ 실행 / 실기
  - 에뮬레이터: Mednafen/Beetle Saturn, Kronos, SSF, Yaba Sanshiro 등.
    (Yabause 0.9.11 은 트랙별 FILE 이 여러 개인 CUE 를 못 읽습니다 → 단일 BIN 으로 합친 뒤 사용)
  - 실기: ODE(Fenrir/Satiator/Rhea·Phoebe) 또는 CD-R. 데이터 트랙의 EDC/ECC 는 전 섹터 재계산되어 있습니다.
  - 저장: 본체 내장 백업 메모리 사용. 백업 파일 이름/주석은 원본과 같으므로 일본판 세이브와 호환됩니다.

■ 알려진 사항
  - 이름 입력 최대 6글자(원본과 동일). 한글은 입력판에 있는 글자(162자)만 쓸 수 있습니다.
  - 엔딩 스태프/성우 이름은 일본어 원문 표기입니다.

■ 제작
  - 번역·해킹·그래픽: 보는_TV 나만 (Grok Bot 작업 지원)
  - 도구: 자체 제작(LZSS/아카이브/스프라이트/FILM-Cinepak/폰트/EDC·ECC/PPF), ffmpeg, xdelta3

■ 글꼴 라이선스 (SIL Open Font License 1.1)
  - Neo둥근모 — Copyright (c) 2017-2021 Eunbin Jeong (Dalgona.) <project-neodgm@dalgona.dev>
    Reserved Font Name "Neo둥근모". 게임 내 기본 한글 폰트로 사용. 전문: licenses/OFL_Neo둥근모.txt
  - 주아체/도현체(우아한형제들), 검은고딕(Zess Type), 개구체(JIKJI SOFT), 나눔고딕(NAVER) — OFL 1.1
    자세한 내용: licenses/FONTS.txt

■ 저작권
  원작 © 1996 아이데스 / 칵테일소프트 / 키드. 이 패치는 팬 번역이며 원작 게임 데이터를 포함하지 않습니다
  (패치 파일만 배포하세요. 패치 적용된 BIN 은 개인 확인용입니다).
