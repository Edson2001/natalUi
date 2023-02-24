<script setup lang="ts">
import Container from "./components/Container.vue"
import Menu from "./components/Menu.vue"
import Button from "./components/Button.vue"
</script>

<template>

  <header>

    <Container>
      <Menu />

      <div class="content">
        <div class="contentHeader">

          <h3>
            Feliz Natal e
          </h3>
          <h3>Feliz Ano Novo!</h3>
          <p>Nessas festas de fim de ano mande um presente para a pessoa amada e compartilhe a alegria do Natal.</p>
          <Button >
            Fazer uma doação
          </Button>
        </div>
        <div class="contentHeader">
          <img src="/images/send.png" />
        </div>
      </div>

    </Container>


  </header>

  <Container>

    <section class="firstSection">
      <h3>Acessórios</h3>
      <P>Nessas festas de fim de ano mande um presente para a pessoa amada e compartilhe a alegria do Natal.</P>
    </section>
    <div class="boxs">

      <div class="box">
        <h6>Presentes</h6>
        <p>Eles são os melhores presentes que existem.</p>
      </div>
      <div class="box">
        <h6>Presentes</h6>
        <p>Eles são os melhores presentes que existem.</p>
      </div>
      <div class="box">
        <h6>Presentes</h6>
        <p>Eles são os melhores presentes que existem.</p>
      </div>
      <div class="box">
        <h6>Presentes</h6>
        <p>Eles são os melhores presentes que existem.</p>
      </div>

    </div>
  </Container>

  <section class="lastSection">

    <Container>

      <div class="contentLast">
        <div class="contentLastSection">

          <img src="/images/shared.png" alt="">

        </div>
        <div class="contentLastSection"> 
          <h3>Comemore com muito amor!</h3>
          <p>Nestes feriados, festeje com muito amor e paz, oferecendo muitas bênçãos aos nossos entes queridos, amigos e vizinhos, desejando-lhes um Feliz Natal.</p>
          <Button>Fazer doação</Button>
        </div>

      </div>

    </Container>

  </section>

</template>

<style lang="scss" scoped>

  header{
    background-color: #f7c7b9;
    width: 100%;
    .content{
      display: flex;
      align-items: center;
      justify-content: space-between;
      
      p{
        margin-top: 12px;
        margin-bottom: 20px;
        color: #404040;
        width: 446px;
      }
    }
  }

  .firstSection{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin-top: 22px;
    
    h3{
      font-size: 43px;
      line-height: 72px;
    }
    p{
      width: 477px;
      color: #404040;
      text-align: center;
    }
   
  }
  .boxs{
      display: flex;
      margin-top: 48px;
      align-items: center;
      width: 100%;
      flex-wrap: wrap;
      .box{
        height: 100px;
        flex: 1 0 200px;
        margin-right: 12px;
        text-align: center;
        &:last-child{
          margin-right: 0;
        }
        p, h6{
          display: block;
        }
      }
    }

  .lastSection{
    background-color: #f7c7b9;
    .contentLast{
      display: flex;
      justify-content: space-between;
      align-items: center;
      h3{
        font-size: 43px;
        font-weight: bold;
        p{
          color: #404040;
          font-size: 16px;
        }
      }
    }
  }
</style>
