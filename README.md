bool judge = true;

void main() {
  String name = 'K';
  String group = 'B';

  print('K는 세가지 팀 중 한가지 팀을 선택한다.');

  list();

  print('$name는 $group팀을 선택했다');

  print('----------------------------');

  print('Q.다음 보기를 보고 원소의 개수를 맞추시오.');

  list2();

  print('A.5');

  print('----------------------------');

  print('카드에는 다음과 같은 숫자가 적혀있다');

  body();

  print('숫자의 총합은');

  z();

  print('이다.');
}

void list() {
  List cList = [
    '1.A',
    '2.B',
    '3.C',
  ];

  for (String tName in cList) print('$tName');
}

void list2() {
  List dlist = [
    '가',
    '나',
    '다',
    '라',
    '마',
  ];
  print(dlist.first);
  print(dlist.isEmpty);
  print(dlist.isNotEmpty);
  print(dlist.last);
  print(dlist.reversed);
}

void body() {
  E();

  if (judge) {
    F();
    J();
  } else {
    J();
    F();
  }
}

void E() {
  print('1');
}

void F() {
  print('2');
}

void J() {
  print('3');
}

void z() {
  int total = 0;
  List numbersList = [1, 2, 3];

  for (int number in numbersList) {
    total += number;
  }

  print(total);
}
