<template>
  <div id='app'>
    <div>
      <van-cell
        v-for='(item, index) in list'
        :key='index'
        :title='item'
        :value='item'
      />
    </div>
    <van-tabbar fixed :placeholder='true'>
      <van-tabbar-item
        v-for='(item, index) in tabbars'
        :icon='item.icon'
        :key='index'
      >
        {{ item.title }}
      </van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      tabbars: [
        {
          title: '首页',
          icon: 'home-o'
        },
        {
          title: '我的',
          icon: 'user-o'
        }
      ],
      list: [
        '1',
        '2',
        '3',
        '4',
        '5',
        '6',
        '7',
        '8',
        '9',
        '10',
        '11',
        '12',
        '13',
        '14',
        '15',
        '16',
        '17',
        '18',
        '19',
        '20',
        '21',
        '22',
        '23',
        '24',
        '25',
        '26',
        '27',
        '28',
        '29',
        '30',
        '31',
        '32',
        '33',
        '34',
        '35',
        '36',
        '37',
        '38',
        '39',
        '40'
      ]
    }
  }
}
</script>
