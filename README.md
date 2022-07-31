# SafeArea 위젯
- safeArea가 감싸고있는 자식 위젯을 상단의 상태바와 ios경우 하단의 홈버튼까지 삐져나가지 않도록 하게해준다.

# Column 위젯: 주축이 세로
# Row 위젯: 주축이 가로
## mainAxisAlignment : 주축정렬
- start - 시작
- end - 끝
- center - 가운데
- spaceBetween - 위젯과 위젯의 사이가 동일하게 배치된다.
- spaceEvenly - 위젯을 같은 간격으로 배치하지만 끝과 끝에도 위젯이 아닌 빈 간격으로 시작한다.
- spaceAround - spaceEvenly + 끝과 끝의 간격은 1/2로

## crossAxisAlignment : 반대축 정렬
- start - 시작
- end - 끝
- center - 가운데
- stretch - 최대한으로 늘린다.

## mainAxisSize : 주축 크기
- max - 최대
- min - 최소

# Expanded / Flexible 위젯
- Row, Column 위젯의 children안에서만 사용 할 수 있다. 다른곳에서 사용시 에러 발생
## Expanded 위젯
- 최대한으로 남아있는 사이즈를 모두 차지함

## Flexible 위젯
- 일단은 비율만큼 공간을 차지를 하되 child안에있는 위젯이 차지한 공간을 다 차지하지않으면 남는 공간을 버려버린다.
- 생각보다 잘 사용하지않는다.



