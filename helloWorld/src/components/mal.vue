<template>
  <div class="mal">
    <div class="malPainel">
      <h4>Estou mal.</h4>
    </div>
  <h5 id='mal'>{{pergunta}}</h5>
  <div slot="footer" class="secondary toolbar absolute-bottom flex wrap">
    <button type="button" name="button">Tenho dúvidas sobre o que estou sentindo</button>
    <button type="button" name="button">Não estou me sentindo bem!</button>
    <button type="button" name="button">Outro</button>
</div>
</div>
</template>
<script>
  export default {
    name: 'Explicacao',
    data () {
      return {
        pergunta: 'Qual o problema ?'
      }
    }
  }
</script>
<style>
  .mal {
    text-align: center;
    color: #808B96;
  }
  .malPainel {
    background-color: #A569BD;
    color: #f5f6f1;
    padding: 2%;
    border-radius: 10px;
    margin-bottom: 3%;
  }

  #mal {
    margin-bottom: 5%;
  }
  .mal button {
    font-size: 13px;
    width: 100%;
    padding: 4%;
  }

</style>
