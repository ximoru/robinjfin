<template>
  <div class="hello text-center">
    <h1>网页地址</h1>
    <ul>
      <li>
        <router-link
          :to="{ name: 'classroomList' }"
        >
          课堂
        </router-link>
      </li>
      <li>
        <router-link
          :to="{ name: 'managementModular', query: { id: '018BBB73665748D3ACC32B19A08C248C' } }"
        >
          资管详情
        </router-link>
      </li>
      <li>
        <router-link
          :to="{ name: 'award' }"
        >
          注册抽奖
        </router-link>
      </li>
      <li>
        <router-link
          :to="{ name: 'recommand' }"
        >
          推荐有奖
        </router-link>
      </li>
      <li>
        <router-link
          :to="{ name: 'aptitude' }"
        >
          服务资质
        </router-link>
      </li>
      <li>
        <router-link
          :to="{ name: 'letter' }"
        >
          给用户的一封信
        </router-link>
      </li>
      <li>
        <router-link
          :to="{ name: 'register' }"
        >
          开户
        </router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  font-size: 20px;
}
ul {
  list-style-type: none;
  padding: 20px;
}
li {
  display: inline-block;
  margin: 0 10px;
  padding: 10px 0
}
a {
  color: #42b983;
}
</style>
