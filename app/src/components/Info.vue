<template >
<div class="cont">
  <div>
    <h1>
      Лабораторна робота 7
    </h1>
    <p><br><br><br>
      Ім'я <span class="boldtext">{{name}}</span> <br>
      Курс <span class="boldtext">{{course}}</span> <br>
      Факультет <span class="boldtext">{{faculty}}</span> <br>
      Спеціальність <span class="boldtext">"{{speciality}}"</span><br>
      Група <span class="boldtext">"{{group}}"</span><br>
      Варіант <span class="boldtext">{{variant}}</span><br>
    </p>
  </div>
  
</div>
</template>


<script>

export default {
  data(){
     return {
        name: 'Хомин Н.Р.',
        course: '4',
        variant:'8',
        faculty: 'ФМЦТ',
        speciality: 'Прикладна математика',
        group: 'ПМ',
    }
     
}
}
</script>



<style >
  .cont{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
    background-color: blanchedalmond;
  }
  
  .boldtext{
    font-weight: 600;
  }
</style>
