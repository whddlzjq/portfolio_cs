# portfolio_cs


1. 컴퓨터가 이해하는 정보
  * 데이터: 컴퓨터가 처리하는 정적인 정보.
  * 명령어: 데이터를 어떻게 처리할지 지시하는 정보 (실질적으로 컴퓨터 작동).

2. 컴퓨터의 4가지 핵심 부품
  * Memory (주기억장치): 현재 실행되는 프로그램의 명령어와 데이터를 저장하는 부품.
  * CPU (중앙처리장치): 저장된 명령어를 읽어 들이고, 해석하고, 실행하는 '두뇌' 역할. 내부 구성:
    * ALU (산술논리연산장치): 산술 연산 및 논리 연산을 수행하는 계산기 역할.
    * Register (레지스터): CPU 내부의 아주 빠른 임시 저장 장치.
    * Control Unit (제어장치): 제어 신호를 보내 부품들을 통제하고, 명령어를 해석.
  * 보조기억장치: 전원이 꺼져도 정보를 보관하는 영구 저장 장치 (HDD, SSD, USB).
  * 입출력장치: 외부와 정보를 주고받는 장치 (마이크, 마우스, 키보드 등).

3. 부품 간 연결
  * 메인보드(Main Board)에 탑재되어 서로 연결.
  * System Bus (시스템 버스): 부품 간 정보를 주고받는 통로.
    * Address Bus: 위치 정보를 전송.
    * Data Bus: 실제 명령어나 데이터를 전송.
    * Control Bus: 제어 신호를 전송.

4. 정보 표현 단위
  * bit: 0 또는 1을 나타내는 가장 작은 정보 단위.
  * byte: 8개의 bit를 묶은 단위 (1 Byte = 8 bits).
  * word: CPU가 한 번에 처리할 수 있는 정보의 크기(단위).
  * 단위: KB -> MB -> GB -> TB 로 확장.

5. 수 표현 방법
  * Binary (2진법): 0과 1 두 개의 숫자로 수를 표현하는 방법.
    * 양수, 음수(**2의 보수**법 사용) 표현 가능.
    * flag를 사용하여 양/음수 구분.
  * Hexadecimal (16진법): 0~9, A~F를 사용하여 수를 표현하는 방법.

6. 문자 집합 및 인코딩
  * Character Set: 부호화(Encoding)하는 과정과 해석(Decoding)하는 과정의 집합.
  * 주요 문자 집합:
    * ASCII: 7비트로 하나의 문자 표현, 1비트는 패리티 비트.
    * 한국어 인코딩: 완성형 인코딩, 조합형 인코딩.
    * EUC-KR: 완성형 한국어 인코딩.
    * Unicode: 전 세계 문자를 통일된 코드로 표현하는 조합.
    * UTF-8: 가변 인코딩 방식 (1-4 바이트 사용).

7. 언어 번역 및 프로그램 실행
  * 언어 레벨: high-level language, low-level language.
  * 번역기: 컴파일러(Compiler, 한꺼번에 번역), 인터프리터(interpreter, 한 줄씩 번역).
  * 프로그램 코드: 기계어(Machine Code), 어셈블리어(assembly language).
  * C언어 컴파일 과정: 전처리기(preprocessor) -> 컴파일러(Compiler) -> 어셈블러(assembler) -> 링커(linker).

8. 명령어 구성 및 주소 지정 방식
  * 명령어 구성:
    * Operation code (Opcode): 연산 종류.
    * Operand: 연산에 사용할 데이터가 저장된 위치.
  * 주소 지정 방식 (Addressing Mode):
    * immediate addressing mode
    * direct addressing mode
    * indirect addressing mode
