<template>
  <div class="my">
    <div class="myinfo">
      <div class="name"><span>刘</span><span>天</span><span>泽</span></div>
      <div class="namespell">
        <span>L</span>
        <span>I</span>
        <span>U</span>
        <span>T</span>
        <span>I</span>
        <span>A</span>
        <span>N</span>
        <span>Z</span>
        <span>E</span>
        <!-- <ul>
        <li>L</li>
        <li>I</li>
        <li>U</li>
        <li>T</li>
        <li>I</li>
        <li>A</li>
        <li>N</li>
        <li>Z</li>
        <li>E</li>
      </ul> -->
      </div>
    </div>
    <div class="description">
        一名不断学习的{{ occupation[0] }}
    </div>

  </div>
</template>

<script>
export default {
    data(){
        return {
            occupation:["学生"],
        }
    }
};
</script>

<style>
.my{
    display: flex;
    flex-direction: column;
  justify-content: center;
  align-content: center;
}
.myinfo {
  width: 120px;

  flex-direction: column;
  justify-content: center;
  align-content: center;
}
.name {
  display: flex;

  font-size: 36px;
  font-family: 黑体;
  justify-content: space-between;
}
.namespell {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  width: 108px;
  height: 120px;
}
.namespell span {
  padding: 0;
  margin: 0;
  display: inline;
  font-size: 18px;
  font-family: consolas;
}
.namespell ul {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  width: 120px;
  height: 120px;
  justify-content: space-between;
  align-content: space-between;
  flex-wrap: wrap;
}
.namespell ul li {
  padding: 0;
  margin: 0;
  display: inline;
  font-size: 18px;
  font-family: consolas;
  /* 
    width: 36px;
    height: 36px; */
  list-style: none;
}
/* .namespell ul li:nth-child(3n){
    display: table-cell;
    list-style:none;
} */
.description{
    display: flex;
    display: incline;
  font-size: 46px;
  font-family: 黑体;
/*     justify-content: center; */
}

</style>