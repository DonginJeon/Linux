# 배운 내용
- 파이프
    - date | rev : 내용이 뒤집힘

- ls /usr/bin : 명령어 조회
- less 
- 리다이렉션과 파이프 차이 잘 알기
- tr
    - cat msg | tr d D : 문서의 d를 D로 바꿈
    - cat data.txt | tr -d [:alpha:] -> 모든 알파벳을 다 지움(대소문자 포함)

- 크기순으로 파일 조회
    - ls /usr/bin -lh | sort -k5hr | head -3

- tee

# 실습
https://plum-poppy-0ea.notion.site/Piping-Exercise-2be75864d4bb42beabb6b3d89cda2be3