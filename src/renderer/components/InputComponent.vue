<template>
  <div>
    <span class="input-container">
      <input class="input" type="text" />
      <i class="fa fa-search icon"></i>
    </span>
  </div>
</template>

<script>
export default {

}
</script>

<style>
* {
  box-sizing: border-box;
}
.input-container {
  display: flex;
  width: 100%;
  margin-bottom: 15px;
  box-shadow: 5px 5px 5px grey;
}
.input {
  border: 1px solid #dedede;
  border-right: none;
  border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
  width: 100%;
  line-height: 50px;
  text-align: center;
  font-size: 2rem;
}

.icon {
  border: 1px solid #dedede;
  border-left: none;
  padding: 25px;
  background-color: white;
  border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
}
</style>