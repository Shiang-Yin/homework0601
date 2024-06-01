<script>
</script>

<template>
    <!-- 搜索區域 -->
    <div class="searchArea">
        <label for="searchName">問卷名稱</label>
        <input class="searchName" id="searchName" type="search">
        <label for="searchStartDay">開始時間</label>
        <input class="searchStartDay" id="searchStartDay" type="date">
        <label for="searchEndDay">結束時間</label>
        <input class="searchEndDay" id="searchEndDay" type="date">
    </div>

    <button>
        <i class="fa-solid fa-trash-can"></i>
    </button>
    <button>
        <i class="fa-solid fa-plus"></i>
    </button>
    
    <!-- 問卷區域 -->
    <div class="questionnaire">
        <!-- 第一區域 勾選區、問卷編碼、名稱、狀態、開始時間、結束時間、結果 -->
        <div class="tittleArea">
            <div class="check"></div>
            <div class="quizAi">問卷編碼</div>
            <div class="quizName">名稱</div>
            <div class="statuses">問卷狀態</div>
            <div class="quizStartDay">開始時間</div>
            <div class="quizEndDay">結束時間</div>
            <div class="quizResult">問卷結果</div>
        </div>


        <!-- 第二區域 將資料匯入-->
        <div class="material">
            <input type="checkbox">
            <div class="quizAiArea"></div>
            <div class="quizNameArea"></div>
            <div class="statusesArea"></div>
            <div class="quizStartDayArea"></div>
            <div class="quizEndDayArea"></div>
            <div class="quizResultArea"></div>
        </div>

    </div>


    <div class="pageArea">
        <button class="firstPage"><i class="fa-solid fa-angles-left"></i></button>
        <button class="prevPage"><i class="fa-solid fa-angle-left"></i></button>
        <button class="pageNum"></button>
        <button class="nextPage"><i class="fa-solid fa-angle-right"></i></button>
        <button class="lastPage"><i class="fa-solid fa-angles-right"></i></button>
    </div>
    
</template>

<style>

</style>
