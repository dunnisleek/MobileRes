<template>
  <div class="wrapper">
    <h3>Open Positions</h3>
    <section class="grid-container">
      <div class="wht-bg">
        <div class="flexbox">
          <span class="material-symbols-outlined">Brush</span>
          <h2>Designs</h2>
        </div>
        <button>4 open positions</button>
      </div>

      <div class="wht-bg">
        <div class="flexbox">
          <span class="material-symbols-outlined"> engineering </span>
          <h2>Engineering</h2>
        </div>
        <button>8 open positions</button>
      </div>

      <div class="wht-bg">
        <div class="flexbox">
          <span class="material-symbols-outlined"> settings </span>
          <h2>Operations</h2>
        </div>
        <button>2 open positions</button>
      </div>

      <div class="wht-bg">
        <div class="flexbox">
          <span class="material-symbols-outlined"> group </span>
          <h2>People</h2>
        </div>
        <button>4 open positions</button>
      </div>

      <div class="wht-bg">
        <div class="flexbox">
          <span class="material-symbols-outlined">Brush</span>
          <h2>Sales</h2>
        </div>
        <button>4 open positions</button>
      </div>

      <div class="wht-bg">
        <div class="flexbox">
          <span class="material-symbols-outlined"> school </span>
          <h2>University</h2>
        </div>
        <button>4 open positions</button>
      </div>

    </section>
    <footer>
       <div>We are proud to be an equal opportunity emploer that values diversity. We don not discrimiate on the basis of race, religion, color, national origin, gender, sexual orientation, age, marital stats, veteran status, or disability status.</div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.wrapper {
  /* width: 900px;
  max-width: 900px; */
  margin: 0 auto;
  padding: 100px 0px;
}
.wrapper h3 {
  font-size: 40px;
  text-align: center;
  padding-bottom: 30px;
}
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* Create three equal columns */
  gap: 10px; /* Add gap between items */
  text-align: center;
  padding:0px 40px;
}

.wht-bg {
  background: #ffffff;
  /* width:300px; */
  height: 24vh;
  border-radius: 5px;
  box-sizing: border-box;
  padding: 30px;
}
span{
       transition:.2s ease-in;
}
span:hover{
       transform: scale(1.075);
}
.grid-container div:first-child span {
  background: #cabdfd;
  padding: 10px;
  border-radius: 5px;
}
.grid-container div:nth-child(2) span{
       background: #FCAFB0;
  padding: 10px;
  border-radius: 5px;
}
.grid-container div:nth-child(3) span{
       background: #CCC6FD;
  padding: 10px;
  border-radius: 5px;
}
.grid-container div:nth-child(4) span{
       background: #75ffcf;
  padding: 10px;
  border-radius: 5px;
}
.grid-container div:nth-child(5) span{
       background: #effdc6;
  padding: 10px;
  border-radius: 5px;
}
.grid-container div:nth-child(6) span{
       background: #5f51cb;
  padding: 10px;
  border-radius: 5px;
}
.flexbox {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
button{
       background: transparent;
       padding:15px 23px;
       border:1px solid grey;
       border-radius:5px;
       margin-top: 20px;

}

footer div{
       padding-top:80px;
       width:600px;
       text-align: center;
       margin:0 auto;
}
/* START OF TABLETS RESPON. */
@media only screen and (min-width: 428px) and (max-width: 600px){
	/*Big smartphones [426px -> 600px]*/
  .wrapper{
   width:100%;
   max-width: 100%;

  }
  .grid-container{
    padding:10px 20px;
    grid-template-columns: 1fr;
  }
  .wht-bg{
    width:375px;
  }
  footer div {
    padding-top: 80px;
    width: 331px;
    /* text-align: center; */
    margin-left: 3rem;
  }
  .wrapper h3{
    font-size:25px;
    text-align: left;
    padding-left: 20px;
  }
}
/* START OF MOBILE */
@media only screen and (max-width: 425px){
	/*Small smartphones [325px -> 425px]*/
  .wrapper{
    width:inherit;
    max-width:inherit ;

  }
  .grid-container{
    grid-template-columns: 1fr;
    padding:0px 20px;
  }
  .wrapper h3 {
    font-size: 30px;
    text-align: center;
    padding-bottom: 20px;
}
footer div{
width:340px;
max-width:340px;
}
}
@media screen and (min-width: 601px) and (max-width:768px){
  .grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  padding:0px 20px;
  }
}
</style>
