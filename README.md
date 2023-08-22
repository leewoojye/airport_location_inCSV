# airport_location_inCSV

## Description
'주요공항csv파일'(주요공항이름, IATA코드...등으로 구성)과 '세계공항위치csv파일'(각공항의위도경도, 공항이름..등으로 구성) 두 데이터를 기반으로 합니다.
주요공항파일은 국토교통부에서 제공하는 데이터를 사용하였으며, 사용자가 이 파일을 수정하여 원하는 공항을 선택할 수 있습니다.
전세계 공항이 매우 많아 시험 데이터 겸 주요공항데이터를 사용하게 되었습니다.
세계공항 중 IATA 코드가 없는 공항도 있습니다.

### How to use
1. src/resource/airport_codes.csv 파일을 수정합니다.
2. src/test.py 파일에서 csv 파일들의 경로를 설정해줍니다.
3. src/test.py 파일을 실행합니다.
4. 프로젝트 폴더 안에 output.csv 파일이 생성됩니다.

### Stacks
pandas 라이브러리
파이썬 3.11.4
