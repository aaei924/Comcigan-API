# Comcigan-API
컴시간알리미 API를 제공합니다.
모두 GET으로 요청하시면 됩니다.
데이터 기본값은 JSON이며, XML을 원할 경우 type 값에 xml을 입력하시면 됩니다.

파라미터 전달 방식은 GET입니다.

## ComciganString
URL: http://api.prws.kr/ComciganString

컴시간알리미 URL에 있는 정체불명의 문자열을 찾아줍니다.

## ComciganSchoolSearch
URL: http://api.prws.kr/ComciganSchoolSearch

Parameter(필수): SchoolName(학교명) or SchoolCode(학교코드)

Parameter(선택): Region(지역)

입력된 정보를 기반으로 학교를 검색합니다. 지역명은 경기, 서울 등 두 자리 약칭으로만 가능합니다.
지역, 학교명, 학교코드를 반환합니다.

## ComciganTimeTable
URL: http://api.prws.kr/ComciganTimeTable

Parameter(필수): SchoolName(학교명) & Region(지역) or SchoolCode(학교코드)

시간표 데이터를 호출합니다.

## 예시
http://api.prws.kr/ComciganSchoolSearch?SchoolName=컴시간&Region=강원
