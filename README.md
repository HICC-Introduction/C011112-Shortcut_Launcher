@@ -0,0 +1,51 @@
# Python GUI - Shortcut Launcher

## 목표 및 목적
지정된 명령어를 클릭 한 번으로 바로 실행할 수 있는 단축키 프로그램을 개발한다.

### 문제 분석

* 최종 목적 : 단축키 실행 프로그램인 Shortcut Launcher를 완성한다.
    * 상위 목적 : 버튼을 생성한다.
		* 하위 목적 : 가로 800, 세로 200의 단일 윈도우 창을 만든다.
		* 하위 목적 : 2행 4열 그리드의 버튼을 만든다.
	* 상위 목적 : 버튼을 클릭할 때 프로그램을 실행할 수 있도록 한다.
		* 하위 목적 : 버튼 1은 메모장을 실행한다.
		* 하위 목적 : 버튼 2는 계산기를 실행한다.
		* 하위 목적 : 버튼 3은 폴더 C:\를 연다.
		* 하위 목적 : 버튼 4는 google.com을 연다.

## 개발 사양

### 하드웨어
* CPU : Intel(R) Core(TM) i5-1035G7 CPU @ 1.20GHz, 1498Mhz, 4 코어, 8 논리 프로세서
* RAM : 8.00GB
* HDD/SSD : VIVA400NX80 512GB
* GPU : Intel(R) Iris(R) Plus Graphics

### 소프트웨어
* OS : Microsoft Windows 10 Pro
* 개발 스택 : Tkinter(정보가 많고 더 다루기 괜찮아 보이기 때문이다.)
* 개발 프로그램 : Visual Studio 
* 개발 언어 : Python v3.5

### 코드룰
* 예시 프로그램

```
    # 변수명
    test_variable = 13
    # 클래스명
    class TestClass:
        def __init__(self):
            # 프로퍼티명
            self.testProperty = 41
        # 메소드명
        def TestMethod(self):
            print(self.testProperty)
    
    if __name__ == "__main__":
        test_variable = TestClass(43)
        test_variable.TestMethod()
```

* 본인의 코드 룰 

```
    # 변수명
    test_variable = 13
    # 클래스명
    class TestClass:
        def __init__(self):
            # 프로퍼티명
            self.testProperty = 41
        # 메소드명
        def TestMethod(self):
            print(self.testProperty)
    
    if __name__ == "__main__":
        test_variable = TestClass(43)
        test_variable.TestMethod()
```