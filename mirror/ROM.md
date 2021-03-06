## Contents

    

1. Read-only memory 
    

1.1. 종류

    

1.1.1. 마스크롬(Mask ROM)

1.1.2. 피롬(PROM Programmable ROM)

1.1.3. 이피롬(EPROM Erasable PROM)

1.1.4. 이이피롬(EEPROM Electrically EPROM)

1.1.5. [플래시메모리](%ED%94%8C%EB%9E%98%EC%8B%9C%20%EB%A9%94%EB%AA%A8%EB%A6%AC.md)(Flash
Memory)

2. Read Only Member 
3. 롬파일을 줄여 부르는 말 

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=1)]

# 1. Read-only memory ¶

  * [컴퓨터 관련 정보](%EC%BB%B4%ED%93%A8%ED%84%B0%20%EA%B4%80%EB%A0%A8%20%EC%A0%95%EB%B3%B4.md)  

첫 내용 작성에 특수 기기가 필요하고, 특성상 동적으로 쓸 수가 없는 장비. 현재에 와선 write작업이 쉬워졌지만 과거엔 굉장히 복잡해,
한번 데이터를 write하면, 바꾸지 못했다. 그래서 Read-only memory(읽기 전용 기억장치)

  

일반적으로 한번 기록한 정보가 전원 유지와 상관없이 (반)영구적으로 기억되며, 삭제나 수정이 불가능한 기억 장치를 가리킨다. 이와는 반대로
원할 때 쓰고 지울 수 있으나, 전원이 유지되지 않으면 내용이 사라지는 기억 장치는 [RAM](RAM.md)(Random Access
Memory)이라고 부른다. 그래서 CD-ROM의 ROM이 바로 이 뜻. 참고로 CD-RW의 RW는 Re-Writable(재기록 가능)의
약자다.

  

보통은 [컴퓨터](%EC%BB%B4%ED%93%A8%ED%84%B0.md)의
[바이오스](%EB%B0%94%EC%9D%B4%EC%98%A4%EC%8A%A4.md)나 게임기에 들어가는 게임 패키지 등 광범위한
분야에 쓰인다.

  

단점으로만 보이는 특성 외에, 전력 공급과 무관하게 데이터가 유지되는 비휘발성이라는 강력한 특징이 있어서, 모든 종류의 기계에 쓰인다.
ROM이 없다면 전기 아깝다고 전기밥솥 전기코드를 뽑는 순간 당신의 전기밥솥은 먹통이 된다. 당장 전기밥솥도 일종의 프로그램된 로봇이기
때문에 한 번 데이터가 날아가면 코드를 연결해도 전기가 흐르는 고철덩이 그 이상도 이하도 아니게 된다. 그래서 로봇, 전자기기의 기판 등을
가리지 않고 사용되며, 2012년의 상황에서도 다양하게 사용되고 있다.

  

ROM에 Write작업을 하기 위한 장비를 롬라이터(ROM Writer)라고 하며, 보통 전자공학과에 몇 개쯤 존재하며,
<del>부유한</del> 전자계열 [동아리](%EB%8F%99%EC%95%84%EB%A6%AC.md)의 경우 동아리 내부에 몇 개
정도 가지고 있기도 하다. 실은 롬라이터 자체는 전자과 1학년생도 제작이 가능할 정도로 단순한 놈이라 가격도 그리 비싸진 않은데 요즘엔
롬라이터 없이 재기록 가능한 제품이 많이 나와 있기 때문에 없다고 큰 문제가 되지는 않는다. 대표적으로 [플래시메모리](%ED%94%8C%EB%9E%98%EC%8B%9C%20%EB%A9%94%EB%AA%A8%EB%A6%AC.md)가 롬라이터 없이
제한된 횟수 만큼 재기록이 가능한 ROM이긴 하다. 전자과 계열 학생이라면 ISP(In-system programming)라는 용어를 들을
기회가 있을텐데 ISP가 적용된 칩은 롬라이터가 필요없다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=2)]

## 1.1. 종류 ¶

롬의 종류는 다음과 같은 종류가 있다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=3)]

### 1.1.1. 마스크롬(Mask ROM) ¶

제작할 때 미리 기억시키는 것으로 한 번 기억시킨 내용은 변경할 수 없다. 가장 강력한 비휘발성을 가지지만 그냥 제조공장에서 회로를
구워버리는 방식으로 제조하기 때문에 현재는 더 이상 제조되지 않는다.

  

그 이유는 저장된 프로그램을 고치려면 생산라인을 들어내야 할 판이며, 일단 생산된 제품의 사소한 문제점을 해결하려고 해도 칩 자체를 교환해야
하기 때문이다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=4)]

### 1.1.2. 피롬(PROM Programmable ROM) ¶

초기에 내용이 들어있지 않은 롬으로 사용자가 내용을 한 번만 기록할 수 있는 롬이다. 비트를 기록하는 각 셀마다 퓨즈가 들어있는데 퓨즈가
이어져 있으면 1, 끊어져 있으면 0하는 식으로 정보를 기록한다. PROM을 기록하는 롬라이터는 0을 기록하려는 셀에 과전류를 흘려서 퓨즈를
끊는 식으로 프로그래밍하며 따라서 한 번 기록한 PROM은 내용을 바꿀 수 없다.

  

역시 피롬도 마스크롬만큼은 아니지만 한번 피롬이 장착된 기계의 프로그램을 수정하려면 롬 자체를 기판에서 뜯어낸 후 새 롬을 다시 납땜질해야
하는 불편이 있으므로 사용처가 상당히 적다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=5)]

### 1.1.3. 이피롬(EPROM Erasable PROM) ¶

[자외선](%EC%9E%90%EC%99%B8%EC%84%A0.md)을 이용하여 기억된 내용을 지우고 다시 기록할 수 있는 롬이다.
이피롬은 읽기나 쓰기에는 전기를 사용하는데 쓰기는 한 번만 가능하고 내용을 지울 때에는 자외선을 사용한다. 그래서 EPROM에는 투명 창이
동그랗게 나 있다. 이 창은 자외선을 잘 통과시키는
[석영유리](%EC%84%9D%EC%98%81%EC%9C%A0%EB%A6%AC.md)로 만들어진다. 일단 데이터를 기록한 후에는 이
창을 검은 테이프로 막아 내용이 지워지는 걸 막는다.

  

내용을 지울 때에는 롬 이레이저라고 부르는 장치에 넣고 20분 정도 돌리는데 롬 이레이저 안에는 자외선 형광등이 들어있다. 여기서 지워버린
EPROM은 모든 셀이 1로 초기화된다. 즉 부분 삭제는 불가능하다는 얘기. 굳이 롬 이레이저가 아니라도 식기건조기나 컵 살균기의 자외선
형광등을 써도 되는데 이 형광등은 자외선이 약해서 롬 이레이저보다 훨씬 오래 기다려야 한다. 일반 형광등은 자외선이 거의 안 나오니까 이걸론
불가능. 태양빛에 노출시켜도 언젠간 지워진다고 한다. 그래서 의외로 데이터의 불휘발성이 약한 편이다.

  

그리고 EPROM을 기록할 때에는 읽을 때보다 고전압으로 써야 하므로 EPROM을 다룰 때에는 롬 라이터와 롬 이레이저 둘 다 구입해야
한다.

  

아무래도 데이터 지우기가 상당히 불편하기 때문에 요즘은 거의 EEPROM이나 플래시 메모리로 대체되었다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=6)]

### 1.1.4. 이이피롬(EEPROM Electrically EPROM) ¶

이투피롬이라고 부르기도 한다. 전기적인 신호를 이용하여 기억된 내용을 지우고 다시 기록할 수 있는 롬이다. 자외선을 쓰지 않고 즉시 기록을
수정할 수 있기 때문에 매우 편리하다. 제품에 따라서는 롬 라이터 없이 기록이 가능한 제품도 있다.
[메인보드](%EB%A9%94%EC%9D%B8%EB%B3%B4%EB%93%9C.md)의 롬이나
[바이오스](%EB%B0%94%EC%9D%B4%EC%98%A4%EC%8A%A4.md)라고 하면 보통 이이피롬을 지칭한다.

  

아래의 [플래시메모리](%ED%94%8C%EB%9E%98%EC%8B%9C%20%EB%A9%94%EB%AA%A8%EB%A6%AC.md)에 밀려 점점
사용 빈도가 낮아지고 있는 제품이다. 그러나 플래시 메모리보다 제어가 쉽고 읽고 쓰기(=고치기) 모두 바이트 단위로 가능하며 수명이 길고
쓰기 가능 횟수가 플래시 메모리보다 훨씬 많으며`[1]` 소용량의 제품은 가격이 저렴하므로 밥솥이나 냉장고 같은 가전제품을 만들 때에는
아직도 현역으로 쓰이고 있으며 주로 임베디드 시스템용 마이크로컨트롤러(주로 메모리 통합 제품)에 데이터 저장용으로 소용량 포함되는 경우도
많다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=7)]

### 1.1.5. [플래시메모리](%ED%94%8C%EB%9E%98%EC%8B%9C%20%EB%A9%94%EB%AA%A8%EB%A6%AC.md)(Flash
Memory) ¶

상세한 내용은 위의 링크 참고. EEPROM에서 더 진보한 형태이며 롬 라이터가 필요없고 쓰기 속도가 많이 개선됐다. 현재 대용량 ROM은
거의 전부 플래시 메모리이다. 가전제품 중에도 뭔가 **스마트**한 제품에는 여지없이 플래시 메모리가 들어간다. 기존의 ROM과는 달리
보조기억장치로도 사용할 수 있다.

  

다만 지우고 쓰는 동작이 EEPROM에 비해 다소 복잡하다는 단점이 있다. [SSD](SSD.md)가 어째서 콘트롤러빨을 심하게 타는지
생각해보면 바로 답이 나온다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=8)]

# 2. Read Only Member ¶

<del>반댓말은 **Random Access Member**</del>  
[일본](%EC%9D%BC%EB%B3%B8.md) 웹 상에서 쓰이는 표현. [눈팅](%EB%88%88%ED%8C%85.md)족
혹은 [유령회원](%EC%9C%A0%EB%A0%B9%ED%9A%8C%EC%9B%90.md)에 준하는 의미.  
[한국](%ED%95%9C%EA%B5%AD.md)에 '[닥눈삼](%EB%8B%A5%EB%88%88%EC%82%BC.md)'이라는
표현이 있듯이, 일본에도 '반년 ROM해(半年ROMれ)'라는 표현이 있다. 기간은 반년부터 죽을 때까지 다양(…). 기간이 없이
'ROM해라'라는 표현의 경우, 쉽게 말해 닥치라는 의미.  
한국에서도 [PC통신](PC%ED%86%B5%EC%8B%A0.md) 시기에 잠깐 쓰였다.

  

[[edit](http://rigvedawiki.net/r1/wiki.php/ROM?action=edit&section=9)]

# 3. 롬파일을 줄여 부르는 말 ¶

[롬파일](%EB%A1%AC%ED%8C%8C%EC%9D%BC.md)항목 참고.

`\----`

  * `[1]` EEPROM 중에는 수십년 수명에 쓰기가 수천만번까지 가능한 제품도 있다. 반면 플래시 메모리는 최대 수십만번 정도고 블럭 단위로 삭제를 하므로 실제로 변경할 필요가 없는 부분도 같이 삭제가 되므로 실제 쓰기 가능 횟수는 훨씬 크게 차이가 난다.

