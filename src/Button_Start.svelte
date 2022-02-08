<script>

//자릿수가 중복되지 않는 3자리 숫자 생성, 생성값은 store 값에 저장
//시작 상태 변경하여 입력 창 표시
function generateNumber(){
    var number = Math.floor(Math.random() * 10);
}

</script>

<input type="button" value="start" on:click="{generateNumber}">