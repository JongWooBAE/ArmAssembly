## arm assembly입니다.
vi name.s		>> 수정
as -g name.s -o name.o
ld name.o -o name


<라인별로 읽기>
gdb name
b 1
b _start	분기
l	코드보기
s	한줄씩 읽기