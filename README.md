# usbserial

원본소스는 아두이노 폴더의 \Resource\Java\hardware\arduino\firmware\atmegaxxu2 아래에 있다. 컴파일을 하려면 LUFA 라이브러리가 필요하다.

arduino-usbserial 폴더와 같은 위치에 LUFA를 복사하고 make 파일에서 다음과 같은 내용을 수정한다.

**LUFA_PATH**

LUFA_PATH = ../

**MCU**

MCU = at90usb162  <= atmega16u2와 pin to pin 호환이다.