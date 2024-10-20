# java-calculator-precourse

1. 기본 구분자 처리: 쉼표와 콜론을 기준으로 숫자를 분리
   + 사용자가 입력한 문자열에서 숫자를 추출하여 그 합을 반환하는 기능
   + 문자열이 비어 있거나 null일 경우 0을 반환
2. 기본 구분자(쉼표, 콜론)를 기준으로 문자열 분리
   + 쉼표(,) 또는 콜론(:)을 기준으로 문자열을 분리하여 숫자들을 추출
3. 커스텀 구분자를 구분
   + 문자열의 시작이 "//"로 시작하고, 그 뒤에 커스텀 구분자가 있는 경우 해당 구분자를 사용하여 문자열을 분리
   + 커스텀 구분자는 "//" 와 "\n" 사이의 문자로 지정됨
4. 음수 값에 대한 예외 처리
   + 입력 문자열에 음수가 포함될 경우 IllegalArgumentException을 발생시키며, 음수 값을 포함한 에러 메시지를 출력
