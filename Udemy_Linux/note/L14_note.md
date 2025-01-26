# 배운 내용
- locate
- find
    - find ~ -type f -name "*.txt"
    - find ~ -type f -empty : 빈 파일 찾기
        - find ~ -type f -empty -exec ls -l '{}' ';'
    - find -size +1G
    - find -user ddd
    - 시간 기반
        - touch last_week -d "1 week ago"
        - find -mmin +30
- xargs

# 실습
- https://plum-poppy-0ea.notion.site/Find-Exercise-1258f6c24327427888e3662cab37b4f9