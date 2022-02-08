<script>
    //input에 입력된 값들 조합
    //Store 저장된 정답과 비교
    //결과 하단에 리스트로 표시
    function checkNumber(){};

    //정답인 경우
    //이름 입력 창 표시
    //이름 입력 후 순위표 출력
    function hitNumber(){};

</script>

<form>
	<input type='number' id='num' value='0' min='0' max='9'/>
	<input type='number' id='num' value='0' min='0' max='9'/>
	<input type='number' id='num' value='0' min='0' max='9'/>
    <input type='button' id='btn' value='Throw!' on:click="{checkNumber}"/>
</form>